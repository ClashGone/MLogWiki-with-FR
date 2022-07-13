[<< retourner à la page principale](../README_FR.md)
# Tableur des schématiques avec logique

Notifier SByte#7574 sur discord en case de problèmes avec ce tableur ou pour envoyer un Pull Request.

<!-- TODO: Automate this with actions and json -->
<!-- previously on https://docs.google.com/spreadsheets/d/1LQXT5KLEAX0OmkofKDUdt6xcSattJKX6_A9beSJ1A7w/edit#gid=0 -->

| Nom | Description | Auteur | Lien de la schématique | Code source | Version | Date de la dernière mise à jour |
| :--- | --- | :---: | :---: | :---: | :--- | ---: |
| CCAD Recon. Control |	payEnter |	Cirrocco | [Discord principal](https://discord.com/channels/391020510269669376/640604827344306207/961263533859962912) | | v3a28 | 4/6/2022
| CCER GP Reactor Controller | **Contrôleur de réacteur** <br> Contrôleur universel de réacteur <br><br>- Démarre les réacteurs à thorium. <br>- Calcule le moment optimal pour démarrer un réacteur à impact en fonction de l'énergie circulant, de l'énergie stockée sur batterie, et des effets accélérants alentour. <br>- Si assez d'énergie est disponible, l'accélération sera activée. <br>- Plusieurs contrôleurs peuvent gérer différents réacteurs, tant qu'ils sont reliés à la même cellule de mémoire. | Cirrocco | [Discord principal](https://discord.com/channels/391020510269669376/422855426242248725/934609395063595030) | | v5.28 | |
| CCMR Mining Brane | | Cirrocco | [Discord principal](https://discord.com/channels/391020510269669376/640604827344306207/944295882470326425) | | v4.17 | 2/19/2022  |
| Factory Performance | **Mesureur de la productivité d'une fabrique** <br><br>Connecter à une fabrique ou un reconstructeur, ou à chaque fabrique d'une schématique pour obtenir la production moyenne.<br>- Mesure dès que la fabrique démarre.<br>- Note depuis quand il mesure, et le pourcentage de temps dans lequel des unités ont été produites.<br>- Remarque si quelque chose manque de ressources. | Cirrocco | [Discord principal](https://discord.com/channels/391020510269669376/422855426242248725/923309808336125985) | | v2.1 | 12/23/2021 |
| Ratios | **Calculateur de ratios** | Bidun | [Main Discord](https://discord.com/channels/391020510269669376/422855426242248725/970050118835396620) | | v1.6 | 5/1/2022 |
| Supply Crew | **Livraison d'item**<br>Conçu pour le début/milieu de partie. Pour un meilleur débit, il vaut mieux choisir d'autres logiques.<br><br>- Peut contrôler jusqu'à 9 unités en même temps.<br>- Contient un sauvegardeur de ressources (configurable) | SBytes | [Discord principal](https://discord.com/channels/391020510269669376/878022862915653723/974570618668318763) | | v2.6.3 | 05/13/2022 |
| uBindFew | Lie plusieurs unités pour ajouter votre propre code | Nester | | [Discord principal](https://discord.com/channels/391020510269669376/742769933926269069/902996482599297125) | v2.02 | |
| Ultimate Dome Loader | Contrôle des unités pour apporter du tissu phasé et du silicium à un dôme accélérant | Highfire1 | [Main Discord](https://discord.com/channels/391020510269669376/878022862915653723/925648746870620182) | | v6 |12/29/2021 |
| UMiner Group | **Logique minière pour 5 types d'unités**<br>- Agit comme l'IA d'un mono, haute efficacité.<br>- Peut miner plus de ressources, comme le sable, le charbon et la ferraille.<br>- Mine en priorité les ressources importantes, en suivant la liste du message<br>- Change automatiquement la ressource choisie si elle n'est as présente.<br>- Hautement configurable | Username | [Discord principal](https://discord.com/channels/391020510269669376/640604827344306207/942284761827778622) | | v5.2 | 1/31/2022 |
| Smart POD | **Projecteur + tissu phasé intelligent**<br>Envoie du tissu phasé dans un accélérant s'il y a plus de 100 tissus phasés dans le noyau et pas de dôme accélérant dans son rayon.<br>- Lier à un projecteur/dôme accélérant.<br>- | Gewi | | [Github](https://github.com/Gewi413/mindustry-logic/blob/main/overdrive/normal.mlog) | | 3/13/2022 |
<!-- | | | | | | | | -->
