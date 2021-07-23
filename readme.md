Translations extracted and based on the dated but excelent work (ESP translation tool) of Gilles_k

found at https://www.mwmythicmods.com/toolsgen.htm
under "Translation:" called the "Sauerkrabbler" (English -> German) [https://ressources.wiwiland.net/IMG/7z/DEU3.03a.7z]

DEU3.03a

DER-FIX-WIE-NIX-ESP-ÜBERSETZER
ERSTELLT VON GILLES_K


I've extracted the cell translation from cells.dat with painful regex and then corrected some for some reason missing entries in the table
and threw together a python script to walk through the whole server directory and translate (case insensitive) all cell names.

Only Cell identifiers are translated, because (at least i think so) these are the only meaningfull (code breaking if wrong) differences between the english and german files


If you have Python installed, just place the py script in your tes3mp server directory and execute it with python.
Any scripts relying on cell identifiers should be up and running from now on.

You should be able to relaunch the sript at any time you add other script or update server files.

with best regard, Armin :)

Have Fun Sauerkrauting
