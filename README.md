# Increasing image resolution using a pre-trained Enhanced Super Resolution (ESR) GAN -and-segmenting high-resolution images-using-K-Means-clustering

Creating a high resolution image from one single-molecule microscopy image and thereafter segmenting the super-resolved image using K-Means clustering. 

## **Segmenting an image to count and analyze only colocalized spots** ##
![image1_original](https://github.com/user-attachments/assets/90b4e30f-85bd-4d77-89c6-a504fc4cc512)

In this case we used a construct made of AMPA receptor subunit GluA1 tagged with both mEGFP and SNAP-tag at the end of the C-terminal domain. This was used to analyze the labeling efficiency of SNAP-tag intracellular and to understand why a certain fraction of fluorophores are non-fluorescent in the Xenopus oocytes. Therefore we wanted to segment only yellow colocalized spots i.e. the spots where we have both GFP and SNAP-tag giving fluorescence.


## **Segmenting an image to count and analyze all spots** ##
![image2_original](https://github.com/user-attachments/assets/c1a35958-9e94-4cab-a74f-2000f46f78f8)

In this case we wanted to analyze the stoichiometry of GluA1/GluA2 heteromers. GluA1 and GluA2 can form homotetramers when expressed alone. GluA1/GluA2 hetermers assemble in 2:2 stoichiometry. Therefore we need to segment all the spots including only green (GluA1 was tagged with mEGFP) and red spots (GluA2 was tagged with SNAP-tag). 
