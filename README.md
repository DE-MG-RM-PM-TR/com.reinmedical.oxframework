# com.reinmedical.oxframework


Dies ist ein Oxygen-Framework zur Bereitstellung von RM-spezifischen DITA-Dokumenttypen in Dokumentvorlagen.
Dieser Ordner wird im Oxygen-Frameworks-Verzeichnis abgelegt.

Download via:
https://github.com/DE-MG-RM-PM-TR/com.reinmedical.oxframework
Details zur Installation weiter unten.


What´s New
- Templates für RM-DITA-Topics mit eigener Doctype Declaration
 - Concept
 - Task
 - Reference
 - Topic

Folgende Verbesserungen sind schon in der Pipeline:
- automatische Erkennung der neuen Datentypen


# Installation und Inbetriebnahme des Plugins „com.reinmedical.oxframework“

Oxygen und DITA-OT mit Java JRE-Installation ist erforderlich.
Das DITA-OT-Plugin com.reinmedical.doctypes muss installiert sein.
https://github.com/DE-MG-RM-PM-TR/com.reinmedical.doctypes


1.	Download des Plugins “com.reinmedical.oxframework” via
https://github.com/DE-MG-RM-PM-TR/com.reinmedical.oxframework
(siehe Download-Button unten rechts)

2.	Unzippen und Ordner unter „[Oxygen-Programmverzeichnis]/frameworks] ablegen.
3.	Ordner umbenennen in "com.reinmedical.oxframework"

4.	Oxygen starten. 

5.	Neue Dokumenttyperkennung für DITA und DITA VAL einrichten. (Frag SNo)

8.	Nun sollte über Datei->Neu Ordner für "Rein Medical" existieren. Diese Templates erzeugen Dita-Files vom Rein-Medical-Doctyp. Damit neue Filterattribute über den Filter-Wizzard bereit stehen, müssen entsprechende VAL-Filtes importiert sein. 
