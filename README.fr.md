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
  Modèle explicatif pour les véhicules de flux sur alt:V.
</p>
<p align="center">
  <a href="https://github.com/altv-templates/stream-vehicles/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-%239911cc.svg" alt="Released under the MIT license." />
  </a>
    <a href="https://docs.altv.mp/gta/articles/tutorials/stream_vehicles">
    <img src="https://img.shields.io/badge/alt:V-Documentation-%23008736.svg" alt="Based on the alt:V Documentation and additional research." />
  </a>
</p>

<p align="center">
    <a href="README.md" style="margin: 0 0.5em">
        <img height="20" src="https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.2/svg/1f1ec-1f1e7.svg">
        <img src="https://img.shields.io/badge/English-444.svg" alt="English" />
    </a>
    <a href="README.de.md" style="margin: 0 0.5em">
    <img height="20" src="https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.2/svg/1f1e9-1f1ea.svg">
        <img src="https://img.shields.io/badge/Deutsch-444.svg" alt="Deutsch" />
    </a>
    <a href="README.fr.md" style="margin: 0 0.5em">
    <img height="20" src="https://cdnjs.cloudflare.com/ajax/libs/twemoji/14.0.2/svg/1f1eb-1f1f7.svg">
        <img src="https://img.shields.io/badge/Français*-444.svg" alt="Français*" />
    </a>
</p>

## Remarque

*Traduit avec DeepL.com, veuillez envisager de revoir ce texte.

alt:V a introduit une « manière simple » de streamer les véhicules avec la v15, si vous avez le véhicule en tant que ``dlc.rpf``. Si c'est le cas, vous pouvez simplement mettre ce fichier dans un dossier sous le dossier des ressources, nommer ce dossier et le mentionner dans le ``server.toml`` en tant que ressource.

Nous ne sommes pas sûrs que cela concerne tous les fichiers inclus dans ce modèle ou seulement les fichiers inclus dans le « long way » de la documentation officielle. En plus des fichiers officiellement documentés, ce modèle inclut les deux métafichiers ``caraddoncontentunlocks.meta`` et ``vehiclelayouts_NAME.meta``.


## Comment l'utiliser

1. Copiez le dossier ``vehicle`` dans votre dossier ``resources`` (par exemple ``.../altv-server/resources/vehicle``). 
2. Renommez-le comme vous le souhaitez (par exemple, ``manufacturer_modelname`` ou ``group_pack``).
3. Remplacez tous les fichiers qui existent dans le véhicule moddé que vous voulez inclure.
4. Chaque fichier qui n'a pas été inclus dans votre véhicule doit être supprimé manuellement par vous-même.
5. Supprimez tous les fichiers mentionnés (méta et audio) sur le ``stream.toml`` qui n'ont pas été inclus dans ce véhicule add-on.
6. Renommez les fichiers audio dans le ``stream.toml``.
7. Ajoutez le nom du dossier au ``server.toml`` en tant que ressource.

###
    Maintenant le véhicule devrait fonctionner sur votre serveur.


## Notes supplémentaires

- Tout ``NAME``, ``VARIANT`` et ``MOD`` à l'intérieur des noms de fichiers doit être remplacé respectivement.
- Le fichier ``dlctext.meta`` n'est jamais mentionné dans le fichier ``stream.toml``.
- Les fichiers méta sont mentionnés en tant que tels.
- Les fichiers audio sfx sont mentionnés dans leur dossier respectif.
- Les autres fichiers audio sont regroupés sous le nom de ``.dat`` pour chaque type de fichier. Ils sont probablement nommés avec ``_amp``, ``_game`` & ``_sounds``.
- La structure des dossiers et les noms de fichiers ne sont que des exemples et peuvent être différents, bien que ce soit presque la même structure que celle suggérée par la [docs officielle] (https://docs.altv.mp/gta/articles/tutorials/stream_vehicles).
- Ce modèle inclut certains fichiers qui ne sont pas officiellement documentés par alt:V, mais qui semblent avoir fonctionné dans le passé (pour savoir lesquels, voir « Remarque »).


## Utilisation comme modèle

Un bon conseil serait d'avoir un dossier modèle. Pour cela, il suffit de faire l'étape 1, mais de le nommer quelque chose comme ``_vehicle``. Si c'est utile, vous pouvez supprimer tous les fichiers du répertoire ``/stream`` et n'ajuster que les fichiers ``.toml``. Le trait de soulignement le placera en tête de votre dossier, ce qui vous permettra d'ajouter plus facilement d'autres véhicules.


## Contributions

Les [PRs] (https://github.com/altv-templates/stream-vehicles/pulls) sont les bienvenues. Pour des changements explicites, veuillez d'abord ouvrir un [issue](https://github.com/altv-templates/stream-vehicles/issues). Comme il s'agit d'un modèle, nous aimerions le garder aussi simple et soigné que possible.


## Crédits
- [Rockstar Games (Grand Theft Auto V)](https://www.rockstargames.com)
- [multiplayer plattform alt:V](https://altv.mp/#/)
- Extra: [alt:V's official tutorial for streaming vehicles](https://docs.altv.mp/gta/articles/tutorials/stream_vehicles.html?q=vehicle%20mod)
- [Translation by DeepL](https://www.deepl.com/)
