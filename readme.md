Dieses Tool dient der Übersetzung von Zellenidentifikationen für tes3mp aus dem englischen ins deutsche.

Somit sollte es ohne großen Aufwand möglich sein, alle Scripte dritter, sowie die beiliegenden Scripte von tes3mp, auf die deutsche Version des Spiels anzuwenden.
Führt das hier enthaltene Script einfach jederzeit in eurem tes3mp Serververzeichnis aus und es übersetzt alle Zellreferenzen in sämtlichen scripten auf die deutsche Version.

Da dieses Programm in Python geschrieben wurde, wird für die Ausführung wird Python3 benötigt.



Solltet ihr nicht die notwendige Version von Python besitzen, bzw. sucht einen einfachen Weg euren Server in deutscher Sprache nutzen zu können,
findet ihr eine übersetzte Zusammenfassung hier (https://github.com/ArminSeiko/tes3mp-server_incl_scripts-de).
Den dort beinhaltenden Ordner "server" vereint ihr dann einfach, mit eurer frischen Kopie tes3mp (gegenwärtig 0.7) und es ist sofort Spielbereit.

Diese Zusammenfassung beinhaltet eine Kuration von Learwolf (https://github.com/Learwolf/)
mit verschiedenen Fehlerbehebungen (https://github.com/ArminSeiko/tes3mp-Scripts)
inklusive der bei tes3mp beiligenden Scripte mit übersetzten Zellenidentifikationen.


-----------------------

Translations extracted and based on the dated but excelent work (ESP translation tool) of Gilles_k

found at https://www.mwmythicmods.com/toolsgen.htm
under "Translation:" called the "Sauerkrabbler" (English -> German) [https://ressources.wiwiland.net/IMG/7z/DEU3.03a.7z]

DEU3.03a

DER-FIX-WIE-NIX-ESP-ÜBERSETZER
ERSTELLT VON GILLES_K

----------

I've extracted the cell translation from cells.dat with painful regex and then corrected some for some reason missing entries in the table
and threw together a python script to walk through the whole server directory and translate (case insensitive) all cell names.

Only Cell identifiers are translated, because (at least i think so) these are the only meaningfull (code breaking if wrong) differences between the english and german files


If you have Python3 installed, just place the py script in your tes3mp server directory and execute it with python.
Any scripts relying on cell identifiers should be up and running from now on.

If you do not have Python and want a fast and easy solution, look here:
https://github.com/ArminSeiko/tes3mp-server_incl_scripts-de

You should be able to relaunch the sript at any time you add other script or update server files.

with best regard, Armin :)

Have Fun Sauerkrauting
