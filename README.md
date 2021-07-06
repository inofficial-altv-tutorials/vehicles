# en_EN
#### Example documentation of how to use add-on vehicles on the GTA V mp plattform alt:V.

### How to Setup
1. Copy the "vehicle" folder into your "resources" folder ('.../altv-server/resources/'). 
2. Rename it to anything you want (ex.: manufacturer_modelname or lspd_pack).
3. Just replace every file which exists in the modded vehicle you want to include.
4. Every file which was not included in your vehicle has to be removed manually by yourself.
5. Remove every mentioned file (meta and audio files) on the 'stream.cfg' which was not included in this add-on vehicle.
6. Rename the audio files in the 'stream.cfg'.
7. Add the folder name to the 'server.cfg' as a resource.

Now the vehicle should just work all fine for you.

### Infos
- Capital letters in this repository are most likely to be changed.
- The 'dlctext.meta' is never mentioned in the 'stream.cfg'.
- The meta files are mentioned as them.
- The audio sfx files are mentioned as their folder.
- The other audio files are mentioned grouped as '.dat' for every different type of them. They are most likely named like you can see in 'examplefiles/stream/audio' with '_amp', '_game' & '_sounds'.
- The folder structure and the file names are just examples and could be different.

### Use it as a template...
A good advice might be to have a template folder. Therefore just do step 1, but then name it something like '.vehicles', '!exampleveh', '#veh' or '_vehicletemp'. (The signs will list this template folder in top of your resources.) Now do steps 3 to 6. Your template folder is done. From now on you just have to copy your tempkate name it as you want and do steps 7 to 12.



# de_DE 
#### Es handelt sich bei diesem Repository um eine beispielhafte Vorlage zu Vehicle Add-On Resourcen auf der GTA V Multiplayer Plattform alt:V.

### Wie nutze ich es (Setup)
1. Kopiere den "vehicle"(de: Fahrzeug) Ordner in deinen "resources" Ordner ('.../altv-server/resources/'). 
2. Bennene den Ordner, wie du willst (Bsp.: hersteller_modellname oder polizei_pack).
3. Ersetze jeder der Dateien, durch die, die im dem Fahrzeug, das du hinzufügen möchtest enthalten sind.
4. Übergeblieben Dateien, die nicht dabei waren, müssen gelöscht werden.
5. Entferne jede Zeile, die eine Datei erwähnen, die in deinem Fahrzeug nicht dabei war, aus der 'stream.cfg'.
6. Korrigiere die Namen der Audio-Dateien in der 'stream.cfg'.
7. Füge den Ordnernamen zu der 'server.cfg' als Resource hinzu.

Das Fahrzeug sollte jetzt auf deinem Server spawnbar sein.

### Infos
- Großbuchstaben in diesem Repository sind in den meisten Fällen ersetzt durch Labels der Fahrzeuge (oder ihrer Modifikationen).
- Die Datei 'dlctext.meta' wird in der 'stream.cfg' nie erwähnt, da sie immer dabei ist.
- Jede '.meta' Datei wird in der 'stream.cfg' einzeln erwähnt.
- Die Audio Dateien, die im Ordner 'stream/audio/sfx' gelandet sind, werden nicht einzeln, sondern als Ordner in der 'stream.cfg' erwähnt.
- Die anderen Audio Dateien, werden gruppiert als '.dat' für jede verschiedene Zahl hinter diesem '.dat' erwähnt. Sie heißen auch meistens in der Endung alle entweder '_amp' oder '_game oder '_sound'.
- Die Ordnerstruktur und Namen sind nur beispielhaft und könnten natürlich mit etwas Aufwand umbenannt werden.

### Nutzung als Vorlage
Ich empfehle euch, dass ihr euch einen Vorlageordner für Fahrzeugresourcen macht. So könnt ihr schneller neue Fahrzeuge hinzufügen. Dafür solltet ihr einfach Schritt 1 machen (Ordner kopieren) und den Ordner dann sowas wie '.vehicles', '!exampleveh', '#veh' oder '_vehicletemp' nennen. (Die Sonderzeichen vor dem Namen sollen den Ordner ganz oben listen.) Wenn ihr jetzt die Schritte 3 bis 6 macht, habt ihr eine fertige Vorlage. Ab sofort müsst ihr den Ordner nur noch kopieren, umbennen wie ihr wollt und könnt mit den Schritten 7 bis 12 ein neues Fahrzeug hinzufügen.


# Credits
- Rockstar Games (Grand Theft Auto V) -> https://www.rockstargames.com
- multiplayer plattform alt:V -> https://altv.mp/#/

=> btw, here is alt:V's official tutorial for this -> https://wiki.altv.mp/wiki/Tutorial:Stream_Vehicles
