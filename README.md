<!---https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage--->

# UNLOC:  UNsupervised particle LOCalization
[ImageJ] Single Molecule Localization Microscopy (SMLM) plugin: UNLOC

[Mailfert et al. Biophys.J, 2018](https://www.cell.com/biophysj/fulltext/S0006-3495(18)30761-6) A Theoretical High-Density Nanoscopy Study Leads to the Design of UNLOC, a Parameter-free Algorithm

## Aim
As an open-source and user-friendly Fiji plugin, UNLOC is designed for processing SMLM data.
UNLOC is available for Windows, Linux and Mac OS.
UNLOC generates a list of single-molecule localizations with their respective precisions, allowing the reconstruction of super-resolution images.
UNLOC is robust on data with high density of particles/frame, large differences of SNR and variation of spatio-temporal background. UNLOC is well adapted to analyze stacks of images acquired at the same focal plane (2D), with performances close to the CRB.
As an effective unsupervised algorithm, UNLOC requires only the size of the point spread function (PSF) of the optical setup used for the data acquisition or for the generation of synthetic data.


## Prerequisites
UNLOC only needs two software (see the installation procedure below):
- Fiji (or ImageJ)
- A matlab compiler runtime (MCR)

Disable the multi-thread option in the BIOS to optimize the speed of analysis.

UNLOC has been tested on the following operating systems:
* Windows 7 (SP1) / 8 / 8.1 / 10 / 11.
* OS X Yosemite (10.10) / El Capitan (10.11) / Sierra (10.12).
* Linux Ubuntu ($\geq$ 14.04) / Mint ($\geq$ 17).

Since the processing of SMLM data used to be computationally demanding, we recommend to use a computer with high amount of RAM (at least 8 GB) and a processor with a high number of cores. For instance, UNLOC has been tested on a DELL Precision T1700, Intel Core i7-4770 CPU at 3.4 GHz, with 64 GB with Windows 10 (64-bit).


## Installing: just 3 steps !!!

1. Fiji

To download its latest version, visit its website [here](https://imagej.net/Fiji/Downloads) [Schneideret al., Nat. Meth., 2012].

For help with Fiji, please consult its official website. Please check that your Fiji software and Java are up-to-date. In Fiji, the subdirectory "java" must contain a recent JDK version (> 1.8).



2. Matlab Compiler Runtime
   
Download the MCR 2017a, version 9.2 which corresponds to your operating system is available [here](https://www.mathworks.com/products/compiler/mcr.html?s_tid=srchtitle). Install the MCR following the Matlab instructions.

3. UNLOC

<ul>
      <li> Go to the <i>UNLOC_plugin folder</i></li>
      <li> Download the UNLOC.zip file and unzip its content</i></li>
      <li> Copy/paste the entire folder named <i>UNLOC</i> to the <i>Plugins</i> folder of Fiji (for example C:\Fiji.app\plugins\)</li>
      <li> Download the UNLOC_v2.2.jar file and copy/paste it to the <i>Plugins</i> folder</li>
      </ul>
      
![Fiji folder](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_Fiji.png)


## Running the tests

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



## Versioning
v2.2

## Authors
Sébastien Mailfert, Jérôme Touvier, Lamia Benyoussef, Roxane Fabre, Asma Rabaoui, Marie-Claire Blache, Yannick Hamon, Sophie Brustlein, Serge Monneret, Didier Marguet, Nicolas Bertaux

N.B. and D.M. supervised the study and conceived the project. S. Mailfert, A.R., L.B., J.T., and N.B. developed the algorithms and performed the simulations. S.B., S. Mailfert, and S. Monneret designed the optical bench. R.F., M.-C.B., and Y.H. performed experimental observations. And all authors contributed to the interpretation of the data. N.B., S. Mailfert, and D.M. wrote the manuscript.

## Licence
Please read and agree the "SOFTWARE LICENSE FOR RESEARCH USE.docx" file


## Acknowledgments
We acknowledge Marc Allain, Sophie Brasselet, Hai-Tao He, Hervé Rigneault, and Muriel Roche for their critical reading of the manuscript and Emily Witty (AngloScribe) for language editing. We thank Christophe Leterrier for valuable discussions and Florian Levet for his advice on the SR-Tesseler analysis.

This work was supported by institutional funding from the CNRS, Inserm, Aix-Marseille University and Centrale Marseille and program grants from the Research National Agency (ANR-10-BLAN-1214 to N.B. and D.M.), the French “Investissements d’Avenir” (ANR-11-IDEX-0001-02 A∗MIDEX to N.B. and D.M., ANR-10-INBS-04 France BioImaging, ANR-11-LABX-0054 Labex INFORM, and ANR-14-CE09-0008-02 to D.M.), the Fondation pour la Recherche Médicale (FRM-DEQ-20090515412 to D.M.), and the Institut National du Cancer (C15005AS to D.M.).