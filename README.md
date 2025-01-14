# Agon light™
![AgonLight Tiny](https://user-images.githubusercontent.com/69539226/174462809-74da7287-020a-45ee-8996-a5056379a8d4.png)


Agon light™ is a unique combination of instant-on microcomputer and standalone microcontroller, which allows you to control your projects from the convenience and immediacy of a BASIC prompt, without the need for a host PC or sketch compilation. To find out more about what makes Agon light™ unique, useful and attractive, please visit the official website at: https://www.thebyteattic.com/p/agon.html.<p>
The <a href="https://github.com/TheByteAttic/AgonLight/blob/main/Agon%20light%20R1.0%20Manual.pdf">Hardware Manual</a> and the <a href="https://github.com/TheByteAttic/AgonLight/blob/main/Agon%20light%20Quick%20Start%20Guide.pdf">Quick Start Guide</a> (the latter assumes that the files in the <a href="https://github.com/TheByteAttic/AgonLight/tree/main/uSD%20card%20files">/uSD card files</a> directory are present in the uSD card inserted in the Agon light™ unit) should also contain everything you need to know.<p>
The three modules of Agon light™'s official firmware, called Quark™, can be found here:
<UL>
  <LI><a href="https://github.com/breakintoprogram/agon-bbc-basic/releases">Quark™ BBC BASIC</a><br>
  <LI><a href="https://github.com/breakintoprogram/agon-mos/releases">Quark™ MOS</a><br>
  <LI><a href="https://github.com/breakintoprogram/agon-vdp/releases">Quark™ VDP</a><br>
</UL>
Quark™ MOS, running on the Zilog eZ80 CPU, can now be upgraded <i>without</i> the dedicated Zilog USB Smart Cable, by using <a href="https://github.com/envenomator/agon-flash">this utility written by Jeroen Venema</a>. The utility is clearly documented and has been tested.<p><br>
If you are installing Quark™ yourself, the <a href="https://github.com/TheByteAttic/AgonLight/blob/main/Agon%20light%E2%84%A2%20Firmware%20Installation%20Guide.pdf">Firmware Installation Guide</a> has step-by-step instructions on how to do it.<p>
Agon light™ has an <a href="https://www.printables.com/model/235402-agonlight-case">official, customized, 3D-printed case</a>, designed by Jeroen Venema. I recommend this case for protection and extra mechanical stability.
<p><br>
  
![AgonLight Case Montage](https://user-images.githubusercontent.com/69539226/177433409-fe3092d2-4595-4a67-b965-d64440dbf8c5.png)
  
<p><br>
The directory structure above contains the following information:
<UL>
  <LI><a href="https://github.com/TheByteAttic/AgonLight/tree/main/3D%20model">/3D Model</a> contains a, well, 3D model of Agon light™'s board and a 2D image specifying the PCB's key dimensions. These are meant for those interested in designing and building custom (3D-printed) cases for Agon light™.
  <LI><a href="https://github.com/TheByteAttic/AgonLight/tree/main/Design">/Design</a> contains all design files, like schematics, EasyEDA source files and PCB layout.
  <LI><a href="https://github.com/TheByteAttic/AgonLight/tree/main/Manufacturing">/Manufacturing</a> contains the files necessary to have an Agon light™ board manufactured, such as the Gerber file, Bill of Materials and Pick and Place file.
  <LI><a href="https://github.com/TheByteAttic/AgonLight/tree/main/Photos">/Photos</a> contains photos of a properly assembled Agon light™ unit, so to provide detailed references for those attempting to build one themselves. These photos can also be used by the media (feel free to do so if you are a journalist or tech writer).
  <LI><a href="https://github.com/TheByteAttic/AgonLight/tree/main/Third%20party%20documentation">/Third party documentation</a> contains what the name suggests: useful datasheets, user manuals, guides and application/technical notes of parts and software used in/with Agon light™.
  <LI><a href="https://github.com/TheByteAttic/AgonLight/tree/main/uSD%20card%20files">/uSD card files</a> contains the files and directories that should be present in the micro SD card inserted in the Agon light™ unit when you follow the instructions in the <a href="https://github.com/TheByteAttic/AgonLight/blob/main/Agon%20light%20Quick%20Start%20Guide.pdf">Quick Start Guide</a>.
</UL>
   
![AgonLight top small](https://user-images.githubusercontent.com/69539226/177007640-d767e277-f808-4206-9fc4-2d244c61b045.png)

<p><br>
All files in this repository, except for the third-party documentation,<br>
Copyright &copy; 2022 by Bernardo Kastrup.<br>
All rights are reserved.
<p>
<hr>
<b>CHANGE HISTORY:</b>
<p>
<UL>
  <LI><b>17 December 2022</b>: Link to the Quark™ MOS cable-free upgrade utility added to this README file.
  <LI><b>16 December 2022</b>: Small update to the Firmware Installation Guide. Namely, the description of steps 45 and 47 was improved for clarity.
  <LI><b>02 December 2022</b>: Update to the Hardware Manual and schematics to correct an error: the positions of the control port pins ESPI36 to ESPI39 were documented in reverse order, but are now corrected. This update does <i>not</i> change the manufacturing files (Gerber, pick & place and bill of materials files).
  <LI><b>23 November 2022</b>: Update to the uSD card files and the firmware installation guide to reflect release 1.02 of Quark MOS™, Quark VDP™, and Quark BBC BASIC™.
  <LI><b>24 October 2022</b>: Quick Start Guide and Firmware Installation Guide updated to reflect the fact that Agon light™ requires a class-10, Fat32-formatted uSD-card with a partition of no more than 32GB.
  <LI><b>21 October 2022</b>: Quick Start Guide, Firmware Installation Guide, and bbcbasic.bin (in the folder /uSD card files) updated.
  <LI><b>17 October 2022</b>: All documentation updated to reflect the fact that the Zilog USB Smart Cable with product number ZUSBESC0200ZACG will <i>NOT</i> work with Agon light™. The only <i>CORRECT</i> cable has product number ZUSBSC00100ZACG.
  <LI><b>16 October 2022</b>: Step-by-step firmware installation guide added to the repository.
  <LI><b>15 October 2022</b>: Improvements to the Bill of Materials spreadsheets for more clarity regarding which components to source.
  <LI><b>11 October 2022</b>: Update of the Quick Start Guide; The "/uSD card files" directory has been added.
  <LI><b>5 October 2022</b>: Quick Start Guide uploaded.
  <LI><b>4 August 2022</b>: Update of the Manual. The theory of operation (page 6) and the system diagram (page 7) now contain information about the two interrupt lines from the ESP32 available to the eZ80F92. A description of the control port signals (page 10) has also been added.
  <LI><b>26 July 2022</b>: Various bits and pieces of previously missing information added to the manual. System diagram (page 7) updated.
  <LI><b>06 July 2022</b>: Added power considerations to the manual (page 19). More photos (of the official case) added to the /Photos directory.
  <LI><b>30 June 2022</b>: All files of Rev. 1.0 uploaded.
</UL>
