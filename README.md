# SMLM at high density / UNLOC:  UNsupervised particle LOCalization
[ImageJ] Single Molecule Localization Microscopy (SMLM) plugin: UNLOC

[Mailfert et al. Biophys.J, 2018](https://www.cell.com/biophysj/fulltext/S0006-3495(18)30761-6) A Theoretical High-Density Nanoscopy Study Leads to the Design of UNLOC, a Parameter-free Algorithm

[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_7.png)](https://youtu.be/hlHCQPL3Em8)



## Aim
As an open-source and user-friendly Fiji plugin, UNLOC is designed for processing SMLM data. UNLOC generates a list of single-molecule localizations with their respective precisions, allowing the reconstruction of super-resolution images. UNLOC is robust on data with high density of particles/frame, large differences of SNR and variation of spatio-temporal background. As an effective unsupervised algorithm, UNLOC requires only the size of the point spread function (PSF) of the optical setup used for the data acquisition or for the generation of synthetic data.

## Versioning

<ul>
      <li> v1.1 (2018): published version</li>
      <li> v2.2 (2020): updated version of the java plugin code, UNLOC is identical to the published version</li>
      <li> v2.3 (2020): the RAW data from PCO cameras are now being processed</li>
      <li> v2.4 (2024-03): private version</li>
      <li> v2.5 (2024-04): updated version of the java plugin code</li>
      <li> v2.51 (2024-04): the RAW data from PCO cameras are once again being processed</li>
      <li> v2.52 (2024-08): updated version of the java plugin code, simplified graphical user interface, corrected problem with nd2 files (if your nd2 files are not processed, please convert them to tiff!)</li>
      </ul>

## Prerequisites
UNLOC only needs two free software (see the installation procedure below):
- Fiji
- A matlab compiler runtime (MCR)

## Installing: just 3 steps !!!
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_0.png)](https://youtu.be/5JKW7ERvdkI)

1. Fiji

To download its latest version, visit its website [here](https://imagej.net/Fiji/Downloads) [Schneideret al., Nat. Meth., 2012].

2. Matlab Compiler Runtime
   
Download the MCR 2024a, version 24.1 which corresponds to your operating system is available [here](https://www.mathworks.com/products/compiler/mcr.html?s_tid=srchtitle). Install the MCR following the Matlab instructions.

3. UNLOC

<ul>
      <li> Go to the <i>UNLOC_plugin folder</i></li>
      <li> Download the <i>UNLOC.zip</i> file and unzip its content</li>
      <li> Copy/paste the entire folder named <i>UNLOC</i> to the <i>Plugins</i> folder of Fiji (for example C:\Fiji.app\plugins\)</li>
      <li> Download the UNLOC_v2.52.jar file and copy/paste it to the <i>Plugins</i> folder</li>
      </ul>
      
![Fiji folder](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_Fiji.png)


## Running the tests

#1 | UNLOC: First use!
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_2.png)](https://youtu.be/a0wCX3nqlxM)

#2 | UNLOC: PSF size determination
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_2.png)](https://www.youtube.com/watch?v=eUesmBXYbqA)

#3 | UNLOC: a simple example on simulated data
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_3.png)](https://www.youtube.com/watch?v=AfKZNcJovx0)


#4 | UNLOC: a simple example on a DNA-PAINT dataset
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_4.png)](https://www.youtube.com/watch?v=SEu8VFmdj5Q)


#5 | UNLOC: batch mode to analyze multiple files & folders automatically
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_5.png)](https://www.youtube.com/watch?v=3EJgBsAiJYk)


#6 | UNLOC: how to use the debug mode?
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_6.png)](https://www.youtube.com/watch?v=AQrCPhSbxLE)


## Authors
Initial publication:
Sébastien Mailfert, Jérôme Touvier, Lamia Benyoussef, Roxane Fabre, Asma Rabaoui, Marie-Claire Blache, Yannick Hamon, Sophie Brustlein, Serge Monneret, Didier Marguet, Nicolas Bertaux


Updates and current new developments:
Sébastien Mailfert, Nicolas Bertaux with the kind and precious help of Jérôme Touvier


## Licence
Please read and agree the "SOFTWARE LICENSE FOR RESEARCH USE.docx" file


## Acknowledgments
This work was supported by institutional funding from the CNRS, Inserm, Aix-Marseille University and Centrale Marseille and program grants from the Research National Agency (ANR-10-BLAN-1214 to N.B. and D.M.), the French “Investissements d’Avenir” (ANR-11-IDEX-0001-02 A∗MIDEX to N.B. and D.M., ANR-10-INBS-04 France BioImaging, ANR-11-LABX-0054 Labex INFORM, and ANR-14-CE09-0008-02 to D.M.), the Fondation pour la Recherche Médicale (FRM-DEQ-20090515412 to D.M.), and the Institut National du Cancer (C15005AS to D.M.).