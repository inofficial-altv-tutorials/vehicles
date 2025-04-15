<p align="center">
  <a href="https://github.com/altv-templates">
  <picture>
    <source srcset="https://avatars.githubusercontent.com/u/87015511?s=200&v=4">
    <img alt="alt:V Templates Logo" src="https://avatars.githubusercontent.com/u/87015511?s=200&v=4">
    </picture>
  </a>
</p>
<h1 align="center">
  Stream Vehicles
</h1>

<p align="center">
  Beispielhafte Vorlage zum Streamen von Fahrzeugen auf alt:V.
</p>
<p align="center">
  <a href="https://github.com/altv-templates/stream-vehicles/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-9911cc.svg" alt="Released under the MIT license." />
  </a>
    <a href="https://github.com/altv-templates/stream-vehicles/wiki">
        <img src="https://img.shields.io/badge/wiki-GitHub-008736.svg" alt="See our wiki." />
  </a>
</p>

<p align="center">
    <a href="README.md" style="margin: 0 0.2em">
        <img height="20" src="https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.2/svg/1f1ec-1f1e7.svg">
        <img src="https://img.shields.io/badge/English-444.svg" alt="English" />
    </a>
    <a href="README.de.md" style="margin: 0 0.2em">
    <img height="20" src="https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.2/svg/1f1e9-1f1ea.svg">
        <img src="https://img.shields.io/badge/Deutsch-444.svg" alt="Deutsch" />
    </a>
    <a href="README.fr.md" style="margin: 0 0.2em">
    <img height="20" src="https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.2/svg/1f1eb-1f1f7.svg">
        <img src="https://img.shields.io/badge/Français*-444.svg" alt="Français*" />
    </a>
</p>

## Hinweis
alt:V hat mit der v15 einen "einfachen Weg" zum Streamen von Fahrzeugen eingeführt, falls man das Fahrzeug als ``dlc.rpf`` hat. Falls dem so ist, kann man nun diese Datei einfach in einen eignen Ordner in dem Resourcen-Ordner packen, ihn bennen und in der ``server.toml`` als Ressource erwähnen.

Wir sind uns unsicher, ob dies alle Dateien, welche in dieser Vorlage vorhanden sind, korrekt streamt oder ob es nur die Dateien abdeckt, die in der offiziellen Dokumentation auch auf dem "langen Weg" behandelt werden.
Zusätzlich zu den offiziell dokumentieren Dateitypen, enthält diese Vorlage die zwei Metadateien ``caraddoncontentunlocks.meta`` und ``vehiclelayouts_NAME.meta``.


## Anleitung
1. Kopiere den ``vehicle``-Ordner in den ``resources``-Ordner (also ``.../altv-server/resources/vehicle``). 
2. Man bennene den Ordner, wie man will (z.B. ``hersteller_modell`` oder ``gruppe_paket``).
3. Ersetzen jeder der Dateien, durch die, die im dem Fahrzeug, das man hinzufügen möchtest enthalten sind.
4. Übergeblieben Dateien, die nicht dabei waren, müssen gelöscht werden.
5. Entfernen jeder Zeile, die eine Datei erwähnt, die in dem Fahrzeug nicht dabei war, aus der ``stream.toml``.
6. Korrigiere die Namen der Audio-Dateien in der ``stream.toml``.
7. Füge den Ordnernamen zu der ``server.toml`` als Resource hinzu.

###
    Das Fahrzeug sollte jetzt auf deinem Server spawnbar sein.

## Zusätzliche Hinweise
- Jedes ``NAME``, ``VARIANT`` und ``MOD`` in den Dateinamen muss entsprechend ersetzt werden.
- Die ``dlctext.meta``-Datei wird niemals in der ``stream.toml`` erwähnt.
- Die meta-Dateien müssen als diese genannt werden.
- Die Audio-sfx-Dateien müssen als ihr Ordner genannt werden.
- Andere Audio-Dateien werden gruppiert als ``.dat`` für jeden verschiedenen Typ genannt. Diese sind meistens als ``_amp``, ``_game`` & ``_sounds`` benannt.
- Die Ordnerstruktur und die Dateinamen sind lediglich Beispiele und können daher auch anders sein, allerdings halten wir uns an eine sehr ähnliche Struktur, wie sie in der [offiziellen Dokumentation](https://docs.altv.mp/gta/articles/tutorials/stream_vehicles) auch genutzt wird.
- Diese Vorlage enthält zusätzlich Dateien, welche nicht offiziell dokumentiert sind, in der Vergangenheit allerdings funktioniert zu haben scheinen (welche das sind, findet sich im Abschnitt "Disclaimer").


## Nutzung als Vorlage
Wir empfehlen, einen Vorlageordner für Fahrzeugresourcen anzulegen. Dafür führt man einfach Schritt 1 durch (Ordner kopieren) und nennt Ordner dann sowas wie ``_fahrzeug``. Gegebenfalls könnte man die vorhanden Dateien unter``/stream`` aus diesem Löschen und nur die ``.toml``-Dateien jedes Mal anpassen. Durch den Unterstrich sollte dieser Ordner oben gelistet werden.


## Beiträge

[PRs](https://github.com/altv-templates/stream-vehicles/pulls) sind herzlich willkommen. Für spezifische Änderungen, öffnet bitte zunächst ein [Issue](https://github.com/altv-templates/stream-vehicles/issues). Da es sich um eine Vorlage handelt, versuchen wir alles so einfach und sauber wie möglich zu halten.


## Anerkennungen
- [Rockstar Games (Grand Theft Auto V)](https://www.rockstargames.com)
- [Mehrspielerplattform alt:V](https://altv.mp/#/)
- Extra: [alt:V's offizielles Tutorial zum Streamen von Fahrzeugen](https://docs.altv.mp/gta/articles/tutorials/stream_vehicles.html?q=vehicle%20mod)
