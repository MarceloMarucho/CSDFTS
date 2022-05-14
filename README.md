# CSDFTS
﻿Classical Solvation Density Functional Theory Solver (CSDFTS): A Java Application to Characterize Biomolecules and Nanomaterials in Electrolyte Aqueous Solutions

The source can be downloaded from https://data.mendeley.com/datasets/4t8ybf93d5/1 

-Software installation and execution

The software is distributed as a single zip file containing the self-installer application. The user does not need “Root” or “Admin” permissions to install the software on the user’s home directory. The user may unzip the file on the desktop directory, open the resulting folder, then double-click the self-installer application to run the wizard setup and follow a number of module steps. 
As a unique feature, the software comes with a graphical user interface (GUI) that allows users to take advantage of the visually guided setup of the required input data to properly characterize the system and configure the solver. The installer creates the folder “CSDFTS” in the chosen directory to save the software source files, including the GUI executable “CSDFTS- software”. If selected, the installer also creates an icon on the desktop for easy access to run the GUI. The software was successfully installed and tested on a variety of operating systems (Windows 7 and 10, Sierra, Centos 7, Ubuntu 14, Fedora 24, Debian 8) and provides an uninstaller application for easy removal. 
Further information on the software, including examples, can be found in the well documented user guide provided in the folder “CSDFTS”. A brief description of the files and external sources used to make up the package is provided below.

-Files saved in folder CSDFTS

CSDFTS-Software  (double chick it to run the CSDFTS GUI application)
Csdfts_User_Guide.pdf (user guide)
HydratedIonLibrary.txt (Hydrated ion sizes and valences data file used by the CSDFTS to define the electrolyte)
ShannonCrystalIonLibrary.txt (Crystal ion sizes and valences data file used by the CSDFTS to define the electrolyte)
ShannonEffectiveIonlibrary.txt (Effective ion sizes and valences data file used by the CSDFTS to define the electrolyte)
License.txt (GNU General Public License Version 2)
Readme.txt
Uninstaller_CSDFTS (double click it to uninstall the CSDFTS GUI application and remove source files)
atmtypenumbers (input atomic radius data file used by 3v application to calculate protein volume)
bondi.rad (input atomic radius data file used by provol application to calculate protein volume)
united.rad (input atomic radius data file used by provol application to calculate protein volume)

-Subfolders saved in folder CSDFT

3v  (It contains the libraries, Fortran and Python source files downloaded from the repository “svn checkout svn://svn.code.sf.net/p/vossvolvox/code/ vossvolvox/”, as well as, compiled Fortran and Python applications required to run the 3v program, version 1.2. This application is available for Mac and Linux users only).
jmol  (It contains the jmol.jar java application, version 13, downloaded from the sourceforge website  “http://sourceforge.net/projects/jmol/files/latest/download?source=files” for protein visualization)
jre  (It contains the JRE java package, version 1.8, downloaded from Oracle website “http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html”. These files were packed and linked to the CSDFTS installer by using the free application install4j. This Jre java package is used  to run all the java applications included in CSDFTS folder)
pdb2pqr (It contains the libraries and source files downloaded from the sourceforce website “https://sourceforge.net/projects/pdb2pqr/files/latest/download”, as well as, compiled Fortran and Python applications required to run pdb2pqr and propka applications)
pdbfiles  (It contains two uncharged molecular structures for illustration purposes. 1dna.pdb and 1J6Z.pdb represent a cylindrical biomolecule and a globular protein example, respectively. This folder can be used by the user to save any other molecular structure)
provol  (It contains the Trove collections library and the ProteinVolume.jar java application downloaded from the website “http://gmlab.bio.rpi.edu/download.php”.  ProteinVolume.jar is required to run the provol program, version 1.3).
Linux (It contains statically compiled and portable Fortran applications required to run the CSDFTS and perform some GUI operations).
dist (It contains the compiled CSDFTS.jar file and the corresponding java libraries required to run the GUI).
build (It contains figure and image files required by the GUI to illustrate different methods and options).

-Contact information

Lead Developer: Dr. Marcelo Marucho
Email: csdfts.comphys@gmail.com
