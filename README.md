# SimCom-SIM7000-Basics
Getting started with the Simcom's SIM7000 module


Flashing new firmware to SIM modules

The process of lashing a new firmware consists of 3 steps.
1-Backup the QCN file 
2-Flash the new firmware(binaries)
3-Restore the QCN file you backed up on step 1


Let's Start!!!

-Download & install the QPST flashing tool here https://androidmtk.com/download-qpst-flash-tool (Google 'QPST' & download the latest version)
-Open the QPST configuration application
-Click 'Start Clients' on the menu tab & select 'Software  Download' in the menu tab, now you will be able to see a seperate window named 'QPST Software Download'.
-Connect your SIM7000 module & select 'Backup' in the menutab.You will see your SIMCOM modem next to the 'Port'
-Now select browse nest to the 'xQCN file' and select a location & name for your QCN file which will be backed up.
-Click start & wait until the back up process gets completed.

-Click 'Browse' near your Port name and right click your modem port. Then select 'Sahara Configuration'
-Now select 'SB 3.0' tab on the menu tab click 'Browse' near the 'XML' field and select the XML file in your firmware folder(Ex: SIM7000C or SIM7000E)
-Click start, your sim module will automatically resets & switches to 'Download mode' and downloads the firmware files. It will roughly take around 1 to 2 minutes.
-Once the status shows



