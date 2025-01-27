# Single Molecule Localization Microscopy (SMLM) at High Density / UNLOC:  UNsupervised Particle LOCalization

[ImageJ] Single Molecule Localization Microscopy (SMLM) Plugin: UNLOC

[Mailfert et al. Biophys.J, 2018](https://www.cell.com/biophysj/fulltext/S0006-3495(18)30761-6): A Theoretical High-Density Nanoscopy Study Leads to the Design of UNLOC, a Parameter-Free Algorithm

[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_7.png)](https://youtu.be/hlHCQPL3Em8)

---

## Aim
As an open-source and user-friendly Fiji plugin, UNLOC is designed for processing SMLM data. UNLOC generates a list of single-molecule localizations with their respective precisions, enabling the reconstruction of super-resolution images. UNLOC is robust when processing data with a high density of particles per frame, significant variations in SNR, and spatio-temporal background fluctuations. 

UNLOC is an efficient unsupervised algorithm requiring only the point spread function (PSF) size of the optical setup used for data acquisition or synthetic data generation.

---

## Versioning

- **v1.1 (2018):** Published version
- **v2.2 (2020):** Updated version of the Java plugin code; functionality identical to the published version
- **v2.3 (2020):** RAW data from PCO cameras can now be processed
- **v2.4 (2024-03):** Private version
- **v2.5 (2024-04):** Updated version of the Java plugin code
- **v2.51 (2024-04):** RAW data from PCO cameras can once again be processed
- **v2.52 (2024-08):** Updated version of the Java plugin code, simplified graphical user interface, and fixed an issue with ND2 files (if your ND2 files are not being processed, please convert them to TIFF)

---

## Prerequisites
UNLOC only requires two free software tools (see the installation procedure below):

- Fiji
- A MATLAB Compiler Runtime (MCR)

---

## Installing: Just 3 Steps!!!
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_0.png)](https://youtu.be/5JKW7ERvdkI)

### 1. Fiji
Download the latest version from its official website [here](https://imagej.net/Fiji/Downloads) ([Schneider et al., Nat. Meth., 2012]).

### 2. MATLAB Compiler Runtime
Download MCR 2024a (version 24.1) for your operating system [here](https://www.mathworks.com/products/compiler/mcr.html?s_tid=srchtitle). Follow the MATLAB installation instructions.

### 3. UNLOC

1. Go to the *UNLOC_plugin folder*.
2. Download the *UNLOC.zip* file and unzip its contents.
3. Copy the entire folder named *UNLOC* into Fiji's *Plugins* directory (e.g., `C:\Fiji.app\plugins\`).
4. Download the *UNLOC_v2.52.jar* file and place it in the *Plugins* directory.

![Fiji folder](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_Fiji.png)

---

## Running the Tests

### #1 | Getting Started with UNLOC
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_2.png)](https://youtu.be/a0wCX3nqlxM)

### #2 | Determining PSF Size with UNLOC
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_2.png)](https://www.youtube.com/watch?v=eUesmBXYbqA)

### #3 | A Simple Example Using Simulated Data
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_3.png)](https://www.youtube.com/watch?v=AfKZNcJovx0)

### #4 | Analyzing a DNA-PAINT Dataset
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_4.png)](https://www.youtube.com/watch?v=SEu8VFmdj5Q)

### #5 | Using Batch Mode for Automated Analysis
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_5.png)](https://www.youtube.com/watch?v=3EJgBsAiJYk)

### #6 | Using the Debug Mode in UNLOC
[![Watch the video](https://github.com/MAILFERT-Sebastien/UNLOC/blob/main/Images/UNLOC_6.png)](https://www.youtube.com/watch?v=AQrCPhSbxLE)

---

## Authors
### Initial Publication
- Sébastien Mailfert
- Jérôme Touvier
- Lamia Benyoussef
- Roxane Fabre
- Asma Rabaoui
- Marie-Claire Blache
- Yannick Hamon
- Sophie Brustlein
- Serge Monneret
- Didier Marguet
- Nicolas Bertaux

### Updates and Current Developments
- Sébastien Mailfert
- Nicolas Bertaux
  - With the kind and valuable help of Jérôme Touvier

---

## License
Please read and agree to the terms in the *"SOFTWARE LICENSE FOR RESEARCH USE.docx"* file.

---

## Acknowledgments
This work was supported by institutional funding from the CNRS, Inserm, Aix-Marseille University, and Centrale Marseille, as well as program grants from:

- The French National Research Agency (ANR-10-BLAN-1214 to N.B. and D.M.)
- The French “Investissements d’Avenir” programs (ANR-11-IDEX-0001-02 A∗MIDEX to N.B. and D.M., ANR-10-INBS-04 France BioImaging, ANR-11-LABX-0054 Labex INFORM, and ANR-14-CE09-0008-02 to D.M.)
- Fondation pour la Recherche Médicale (FRM-DEQ-20090515412 to D.M.)
- Institut National du Cancer (C15005AS to D.M.)
