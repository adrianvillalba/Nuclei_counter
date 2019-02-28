# **Nuclei Counter: Tutorial**

This is an imageJ macro to count nuclei i routinely use as part of image processing pipelines and to integrate with complementary stainings like insulin, glucagon or CK19.


## **1. Introduction.**
This is a simple imageJ macro i wrote to quickly count nuclei stained in DAPI or HOECHST and then to integrate in other image processing pipelines in order to quantify the number of cells within an area.

## **2. How to use a pre-made macro in imageJ.**
Note: You can download for free the last version imageJ at the official repository (https://imagej.nih.gov/ij/download.html) or at the FIJI repository (remember, Fiji Is Just ImageJ: https://fiji.sc/#download). 

2.1 You need to download directly the macro file (i.e. Nuclei_Counter) or copy-paste the code in a .txt file. 
2.2 Then you have to run imageJ and open the image you want to apply the macro by **File>Open** and selecting the desired image.
2.3 Finally you can run the macro by **Plugins>Macro>Run** and selecting the .txt file where the macro code is located. 

## **3. Results.**
After loading a single-channel 8-bit image with the acquired data for DAPI or HOECHS stains, the image will be duplicated and processed to avoid modifications in the original data. Once the macro performed all the operations you will obtains all the nuclei ROIs (Regions of Interest) loaded in the ROI manager and the resulting ones counted, measured and stored in the display of imageJ. 


<p align="center">
  <img src=https://github.com/adrianvillalba/Nuclei_counter/blob/master/Captura.PNG width="350"/>
</p>

This is the expected output with all the information you may get after Nuclei_Counter processing.
