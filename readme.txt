steps:
1. 2GB SD Karte
2. start-Menü erzeugen:
# Start Dialog for Navgear MX 350
# to install:
# 1. take an empty SD card, create a folder named MobileNavigator
# 2. download mortscript 4.2 from http://www.sto-helit.de/index.php?module=download&action=list&category=2
# 3. unpack the zip archive an copy the content of the folder bin\PNA to the SD card into the MobileNavigator directory
# 4. rename Autorun.exe into mobilenavigator.exe
# 5. copy this script with the name mobilenavigator.mscr to the same directory
# if you would like to add more programs to start, just edit below

3. Totalcommander installieren
# download von http://www.ghisler.com/wince2x.htm "beta cabs" - direkt:
# windows CE ARM auswählen http://tcce.s3.amazonaws.com/b3/ce2/cecmd.arm.cab
# msceinf zum Entpacken der cab Datei: http://msceinf.software.gmx.de/pocketpc
# Starten, cecmd.arm.cab öffnen, enpacken in ein Verzeichnis
# von dort alle Files aus dem Ordner Program Files\Total Commander auf die Speicherkarte (Ordern \Totalcommander) kopieren

4. Ozi Explorer installieren
# von http://www.oziexplorer3.com/ozice/oziexplorerce1.html 
wince_core_runtime_arm.zip (http://www.oziexplorer3.com/ozice/downloads/v2a/wince_core_runtime_arm.zip) runterladen
# enpacke in einen Ordner \Oziexplorer auf Speicherkarte
#
5. Starten, im Menü MobileNavigator auswählen
# Startmenü mit Auswahl Explorer, Commander, OZI sollte erscheinen
# OZI auswählen
# GPS Com7, 4800

6. ActiveSync Verbindung über USB
#control panel 
#USB client switch -> serial class (original: mass storage class)
\HKLM\Drivers\USB\FunctionDrivers
	defaultClientDriver=Mass_Storage_Class <-> Serial_Class

