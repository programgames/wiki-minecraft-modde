# Mods QOL (Quality of Life)

<div class="grid cards" markdown>

-   :sparkles: **JEI (Just Enough Items)**

    ---

    Recherche de recettes et items. Indispensable pour naviguer dans les mods.

    [:octicons-arrow-right-24: Découvrir](#jei-just-enough-items)

-   :mag: **JourneyMap**

    ---

    Minimap et carte en temps réel. Waypoints et exploration facilitée.

    [:octicons-arrow-right-24: Découvrir](#journeymap)

-   :wrench: **FTB Ultimine**

    ---

    Mine des groupes de blocs en un seul coup. Excavation rapide et efficace.

    [:octicons-arrow-right-24: Découvrir](#ftb-ultimine)

-   :keyboard: **Controlling**

    ---

    Gestion avancée des touches et raccourcis. Recherche de conflits de keybinds.

    [:octicons-arrow-right-24: Découvrir](#controlling)

</div>

!!! info "Mods Secondaires"
    **Jade/WTHIT** (info blocks) | **Xaero's Minimap** (alternative map) | **Mouse Tweaks** (inventaire) | **Quark** (vanilla+) | **Supplementaries** (vanilla+) | **AppleSkin** (saturation) | **Inventory Tweaks Refoxed** (tri) | **Crafting Tweaks** (recettes) | **BetterF3** (debug) | **Just Zoom** (zoom) | **Extreme Sound Muffler** (sons)

    [:octicons-arrow-down-24: Voir les mods secondaires](#mods-secondaires)

## Comparaison Rapide

| Mod | Type | Recommandé pour |
|-----|------|-----------------|
| JEI | Interface | Recherche de recettes (indispensable) |
| JourneyMap | Navigation | Carte et waypoints |
| FTB Ultimine | Mining | Miner des veines entières |
| Controlling | Config | Gérer les conflits de touches |
| AppleSkin | Interface | Voir la saturation et faim |
| Inventory Tweaks | Inventaire | Tri automatique |
| BetterF3 | Debug | Infos techniques améliorées |
| Extreme Sound Muffler | Audio | Réduire les bruits de machines |

## Progression Recommandée

!!! tip "Early Game"
    - :zap: **[RUSH]** Configurer les touches JEI (R pour recettes, U pour usages)
    - :zap: **[RUSH]** Créer tes premiers waypoints JourneyMap (spawn, base)
    - :zap: **[RUSH]** Configurer FTB Ultimine (touche par défaut: grave/tilde)
    - Installer AppleSkin pour voir ta saturation et faim cachée

!!! note "Mid Game"
    - Configurer les **filtres JEI** pour cacher les items indésirables
    - Utiliser les **addons JEI** (JER, JEP) pour plus d'informations
    - Configurer **Extreme Sound Muffler** pour réduire le bruit des machines
    - Activer les **overlays de spawn** avec More Overlays Updated

!!! success "Late Game"
    - Maîtriser les **bookmarks JEI** pour les recettes fréquentes
    - Configurer les **profiles JourneyMap** pour différentes dimensions
    - Utiliser **Spark** pour diagnostiquer les problèmes de performance
    - Configurer les touches pour tous les mods avec **Controlling**

## Synergies entre Mods

!!! abstract "Combinaisons Puissantes"

    **JEI + Just Enough Resources**
    :   Voir les drop rates des mobs et les spawns des minerais par niveau

    **JourneyMap + JourneyMap Integration**
    :   Intégration avec les autres mods (waypoints automatiques)

    **Inventory Tweaks + Crafting Tweaks**
    :   Tri automatique dans tous les inventaires et crafting optimisé

    **BetterF3 + Spark**
    :   Debug complet pour identifier les sources de lag

    **FTB Ultimine + Harvest with Ease**
    :   Récolte massive de cultures et minage groupé

---

## JEI (Just Enough Items)

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/jei) | [Wiki](https://github.com/mezz/JustEnoughItems/wiki)

!!! success "Quick Start"
    1. Ouvre ton inventaire - la liste JEI apparaît à droite
    2. Appuie sur **R** sur un item pour voir sa recette
    3. Appuie sur **U** sur un item pour voir ses usages
    4. Utilise la **barre de recherche** en bas pour filtrer
    5. **Clic molette** sur un item pour l'ajouter aux bookmarks

=== "Tips"

    !!! tip "Recherche Avancée"
        - Préfixe `@` pour chercher par **mod** : `@mekanism` affiche tous les items Mekanism
        - Préfixe `#` pour chercher par **tag** : `#forge:ingots` affiche tous les lingots
        - Préfixe `$` pour chercher par **tooltip** : `$upgrade` affiche les items mentionnant upgrade
        - Combine les préfixes : `@thermal #forge:dusts`

    !!! tip "Navigation"
        - **Clic droit** sur un item dans une recette = voir sa recette
        - **Shift + clic** pour voir toutes les recettes d'un type
        - **Backspace** pour revenir en arrière dans l'historique
        - **Clic molette** en mode créatif = obtenir l'item

    !!! warning "Performance"
        - Désactive l'**indexation des recettes** si tu as beaucoup de mods
        - Utilise les **filtres** pour cacher les items que tu n'utilises pas
        - Le **mode cheat** peut être désactivé dans les options

    !!! example "Bookmarks Utiles"
        - Ajoute les **recettes fréquentes** aux bookmarks (clic molette)
        - Organise par **catégorie** en utilisant des séparateurs
        - Exporte/importe tes bookmarks entre modpacks

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Barre de recherche | :zap: RUSH | Filtre les items par nom, mod, tag |
    | Touche R | :zap: RUSH | Affiche la recette d'un item |
    | Touche U | :zap: RUSH | Affiche les usages d'un item |
    | Bookmarks | - | Sauvegarde tes recettes favorites |
    | Filtres | - | Cache les items non pertinents |
    | Mode Cheat | | Donne les items en créatif |

=== "Guides"

    - [JEI Keybindings](https://github.com/mezz/JustEnoughItems/wiki/Key-Bindings)
    - [JEI Search Syntax](https://github.com/mezz/JustEnoughItems/wiki/Search-Recipes)

### Addons JEI

- [Just Enough Resources](https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer) : Drops des mobs et spawn des minerais
- [Just Enough Professions](https://www.curseforge.com/minecraft/mc-mods/just-enough-professions-jep) : Trades des villageois
- [Just Enough Archaeology](https://www.curseforge.com/minecraft/mc-mods/just-enough-archaeology) : Items archéologiques
- [Just Enough Mekanism Multiblocks](https://www.curseforge.com/minecraft/mc-mods/just-enough-mekanism-multiblocks) : Visualisation des multiblocks
- [JourneyMap Integration](https://www.curseforge.com/minecraft/mc-mods/journeymap-integration) : Lien avec JourneyMap

---

## JourneyMap

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/journeymap) | [Wiki](https://journeymap.info/Home)

!!! success "Quick Start"
    1. Appuie sur **J** pour ouvrir la carte en plein écran
    2. **Double-clic** sur la carte pour créer un waypoint
    3. Utilise la **minimap** en haut à droite pour naviguer
    4. Appuie sur **B** pour lister tous tes waypoints
    5. Configure les **options** avec le bouton engrenage

=== "Tips"

    !!! tip "Waypoints"
        - **Double-clic** sur la carte = nouveau waypoint
        - Les waypoints sont **visibles dans le monde** avec un faisceau
        - **Shift + clic** sur un waypoint pour le désactiver temporairement
        - Organise par **couleur** et **nom** pour retrouver facilement

    !!! tip "Navigation"
        - **Clic droit** sur la carte pour déplacer la vue
        - **Molette** pour zoomer/dézoomer
        - Utilise les **boutons en bas** pour changer de couche (surface, grottes)
        - **Cave mode** automatique quand tu es sous terre

    !!! warning "Performance"
        - Réduis la **fréquence de scan** si tu as du lag
        - Désactive le **radar de mobs** si non nécessaire
        - Les grandes maps peuvent utiliser beaucoup de **RAM**

    !!! example "Configurations Utiles"
        - Active le **death waypoint** pour ne jamais perdre ton stuff
        - Configure des **couleurs différentes** par dimension
        - Utilise le **mode web** pour voir ta carte sur un navigateur

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Touche J | :zap: RUSH | Ouvre la carte en plein écran |
    | Touche B | - | Ouvre la liste des waypoints |
    | Minimap | :zap: RUSH | Carte en temps réel dans le coin |
    | Waypoints | - | Marque des positions importantes |
    | Cave Mode | - | Affiche les grottes automatiquement |
    | Radar Mobs | | Affiche les mobs sur la carte |

=== "Guides"

    - [JourneyMap Options](https://journeymap.info/Options_Manager)
    - [Waypoint Beacons](https://journeymap.info/Waypoint_Beacons)

---

## FTB Ultimine

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/ftb-ultimine-forge) | [Wiki](https://docs.feed-the-beast.com/v0.1/docs/ftb-ultimine/)

!!! success "Quick Start"
    1. Configure ta **touche Ultimine** (défaut: grave ` ou tilde ~)
    2. Maintiens la touche **en minant** un bloc
    3. Les blocs **identiques adjacents** seront minés ensemble
    4. Fonctionne aussi pour la **récolte** des cultures
    5. Configure les **limites** dans les options du mod

=== "Tips"

    !!! tip "Utilisation"
        - Maintiens la touche **avant** de commencer à miner
        - Le **shape mode** permet de choisir la forme (tunnel, veine, etc.)
        - Fonctionne avec **tous les outils** (pioche, hache, pelle)
        - La **durabilité** de l'outil est consommée pour chaque bloc

    !!! tip "Shapes"
        - **Shapeless** : mine tous les blocs connectés du même type
        - **Small Tunnel** : creuse un tunnel 3x3
        - **Large Tunnel** : creuse un tunnel 5x5
        - **Mining Tunnel** : tunnel 1x2 à hauteur de joueur

    !!! warning "Limitations"
        - Respecte le **niveau de l'outil** (pioche en pierre ne mine pas le diamant)
        - La **limite de blocs** est configurable (défaut souvent 64)
        - Consomme de l'**énergie/faim** selon la config du serveur

    !!! example "Usages Pratiques"
        - Mine des **veines entières** de minerai
        - Récolte des **champs entiers** de cultures
        - Abats des **arbres complets** d'un coup
        - Creuse des **tunnels** rapidement

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Touche Ultimine | :zap: RUSH | Active le minage groupé |
    | Shape Selector | - | Change la forme de minage (tunnel, veine) |
    | Config Limite | - | Ajuste le nombre max de blocs |
    | Harvest Mode | - | Récolte les cultures automatiquement |

=== "Guides"

    - [FTB Ultimine Documentation](https://docs.feed-the-beast.com/v0.1/docs/ftb-ultimine/)

---

## Controlling

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/controlling) | [Wiki](https://github.com/jaredlll08/Controlling/wiki)

!!! success "Quick Start"
    1. Ouvre le menu des **Options > Controls**
    2. Utilise la **barre de recherche** en haut pour filtrer
    3. Clique sur **Show Conflicts** pour voir les conflits de touches
    4. **Clic gauche** sur une touche pour la modifier
    5. Utilise **Reset** pour revenir aux valeurs par défaut

=== "Tips"

    !!! tip "Recherche"
        - Tape le **nom d'un mod** pour voir toutes ses touches
        - Tape une **touche** (ex: "R") pour voir tous les bindings
        - Le bouton **conflits** montre les touches utilisées plusieurs fois

    !!! tip "Organisation"
        - Trie par **catégorie** (Gameplay, Inventory, Movement, etc.)
        - Les touches **non assignées** sont visibles séparément
        - Exporte tes configs pour les **partager** ou **sauvegarder**

    !!! warning "Conflits Courants"
        - JEI utilise **R** et **U** - conflit possible avec d'autres mods
        - Les mods de **zoom** utilisent souvent C ou Z
        - Curios/Baubles utilisent souvent **G** pour l'inventaire

    !!! example "Touches Recommandées"
        - **Grave/Tilde** pour FTB Ultimine
        - **G** pour inventaire Curios/Baubles
        - **M** pour map JourneyMap (alternative à J)
        - **V** pour jetpack/vol

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Barre de recherche | :zap: RUSH | Filtre les keybindings par nom |
    | Show Conflicts | :zap: RUSH | Affiche les touches en conflit |
    | Catégories | - | Filtre par type de contrôle |
    | Reset All | | Remet toutes les touches par défaut |

=== "Guides"

    - [Controlling GitHub Wiki](https://github.com/jaredlll08/Controlling/wiki)

---

## Mods Secondaires

??? note "Jade / WTHIT"

    [Jade CurseForge](https://www.curseforge.com/minecraft/mc-mods/jade) | [WTHIT CurseForge](https://www.curseforge.com/minecraft/mc-mods/wthit)

    !!! success "Quick Start"
        1. Installe le mod - **actif automatiquement**
        2. Regarde n'importe quel bloc ou entité
        3. Un **tooltip** apparaît avec les informations
        4. Configure les options dans le menu du mod
        5. Affiche le contenu des machines, le fuel restant, etc.

    === "Tips"

        !!! tip "Informations Affichées"
            - **Nom du bloc** et mod source
            - **Contenu** des coffres et machines
            - **Progression** des crafts et furnaces
            - **État** des redstone, crops, etc.
            - **Stats** des mobs (HP, effets)

        !!! tip "Jade vs WTHIT"
            - **Jade** : Plus populaire, plus de fonctionnalités
            - **WTHIT** : Plus léger, successeur de HWYLA
            - Choisis l'un ou l'autre, **pas les deux**
            - Les deux héritent de l'ancien **Waila**

        !!! warning "Essentiel"
            - Un des mods **les plus importants** pour comprendre les mods tech
            - Montre ce que les blocs moddés font sans ouvrir JEI
            - **Indispensable** dans tout modpack

    === "Objets Importants"

        | Fonctionnalité | Description |
        |----------------|-------------|
        | Block Tooltip | :zap: RUSH - Infos sur tous les blocs |
        | Entity Tooltip | Infos sur les mobs |
        | Harvest Level | Montre l'outil requis |
        | Crop Progress | Pourcentage de croissance |
        | Fluid Info | Type et quantité de fluide |

??? note "Xaero's Minimap"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) | [World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)

    !!! success "Quick Start"
        1. Installe Xaero's **Minimap** + **World Map** (deux mods)
        2. La minimap apparaît dans un coin de l'écran
        3. Appuie sur **U** pour la world map
        4. **B** pour créer des waypoints
        5. Configure la position et taille dans les options

    === "Tips"

        !!! tip "Alternative à JourneyMap"
            - Plus **léger** en performances
            - Interface différente, préférences personnelles
            - **Waypoints** illimités avec icônes
            - Compatible avec les serveurs sans mods client

        !!! tip "Fonctionnalités"
            - **Minimap** rotative ou fixe
            - **World Map** avec zoom
            - **Cave Mode** automatique
            - **Mob Radar** configurable
            - **Death Points** automatiques

        !!! warning "Deux Mods"
            - Installe **les deux** : Minimap + World Map
            - Le World Map ajoute la carte plein écran
            - Peuvent fonctionner indépendamment

    === "Objets Importants"

        | Fonctionnalité | Description |
        |----------------|-------------|
        | Minimap | :zap: RUSH - Carte en coin |
        | World Map (U) | Carte plein écran |
        | Waypoints (B) | Marques de navigation |
        | Cave Mode | Affichage automatique sous terre |

??? note "Mouse Tweaks"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks)

    !!! success "Quick Start"
        1. Installe le mod - **actif automatiquement**
        2. **LMB drag** avec un stack = distribue les items
        3. **RMB drag** = place un item par slot
        4. **Shift + Scroll** pour transférer rapidement
        5. Configure les options dans le menu

    === "Tips"

        !!! tip "Contrôles Inventaire"
            - **LMB drag** : Distribue également les items
            - **RMB drag** : Place un item par slot
            - **Shift + Scroll up/down** : Transfert rapide
            - **Scroll sur stack** : Envoie un item à la fois

        !!! tip "Pourquoi l'Utiliser"
            - Rend la gestion d'inventaire **beaucoup plus rapide**
            - Indispensable pour les **crafts en masse**
            - Fonctionne dans tous les inventaires moddés

    === "Objets Importants"

        | Fonctionnalité | Description |
        |----------------|-------------|
        | LMB Drag | :zap: RUSH - Distribution égale |
        | RMB Drag | Un item par slot |
        | Scroll Transfer | Transfert rapide avec molette |

??? note "Quark"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/quark) | [Documentation](https://quarkmod.net/)

    !!! success "Quick Start"
        1. Installe Quark - des **dizaines de features** activées
        2. Configure dans les options du mod (menu Q)
        3. Explore les nouvelles **fonctionnalités vanilla+**
        4. Les changements sont subtils mais nombreux
        5. Désactive ce qui ne te plaît pas

    === "Tips"

        !!! tip "Features Notables"
            - **Inventory Sorting** (touche configurable)
            - **Item Pipes** simples en bois
            - **Nouveaux blocs** décoratifs
            - **Totem of Holding** (récupère ton stuff)
            - **Enchantments améliorés**
            - **Amélioration des mobs** vanilla

        !!! tip "Modules"
            - **Automation** : Pipes, dispensers améliorés
            - **Building** : Nouveaux blocs et textures
            - **Management** : Tri inventaire, bags
            - **Tweaks** : QOL divers
            - **World** : Génération améliorée

        !!! warning "Configuration"
            - Beaucoup de features = **conflits possibles**
            - Configure pour désactiver ce qui overlap avec d'autres mods
            - Le menu de config est **très complet**

    === "Objets Importants"

        | Objet/Feature | Description |
        |---------------|-------------|
        | Inventory Sort | :zap: RUSH - Tri automatique |
        | Item Pipes | Pipes basiques en bois |
        | Totem of Holding | Récupère ton inventaire à la mort |
        | Crates | Stockage compact |
        | Rope | Corde escaladable |

??? note "Supplementaries"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/supplementaries) | [Wiki](https://github.com/MehVahdJukworthy/Supplementaries/wiki)

    !!! success "Quick Start"
        1. Installe le mod - de nombreux **blocs vanilla-style**
        2. Explore les recettes dans JEI (@supplementaries)
        3. Craft un **Safe** pour stocker tes valuables
        4. Place des **Signs** et **Flags** pour décorer
        5. Utilise les **Jars** pour stocker et afficher items

    === "Tips"

        !!! tip "Blocs Utilitaires"
            - **Safe** : Coffre privé (code ou clé)
            - **Sack** : Bag transportable
            - **Jar** : Stocke et affiche des items/fluides
            - **Cage** : Capture et transporte des mobs
            - **Rope** : Corde escaladable

        !!! tip "Décoration"
            - **Flags** : Bannières améliorées
            - **Signs** : Panneaux colorés
            - **Candles** : Bougies variées
            - **Planters** : Pots décoratifs
            - Style **vanilla-friendly**

        !!! warning "Vanilla++"
            - Tous les items ont un style **vanilla**
            - S'intègre parfaitement au jeu de base
            - Parfait pour les serveurs vanilla+

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Safe | - | Coffre privé sécurisé |
        | Sack | - | Bag portable |
        | Jar | - | Stockage décoratif |
        | Cage | - | Capture et transport de mobs |
        | Rope | - | Corde fonctionnelle |
        | Flags | | Bannières décoratives |

??? note "AppleSkin"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/appleskin)

    !!! success "Quick Start"
        1. Installe le mod - pas de configuration nécessaire
        2. Regarde ta **barre de faim** - la saturation est maintenant visible
        3. Survole un **aliment** dans ton inventaire pour voir ses stats
        4. Les **coeurs dorés** indiquent la régénération

    === "Tips"

        !!! tip "Informations Visuelles"
            - La **saturation** apparaît comme overlay sur la barre de faim
            - La **régénération de vie** est prédite avec des coeurs dorés
            - En survolant un aliment : **faim restaurée** + **saturation gagnée**

        !!! tip "Compréhension"
            - Une **saturation élevée** = régénération de vie plus rapide
            - Les aliments avec **haute saturation** sont meilleurs (steak, golden carrot)
            - Tu ne peux manger que si ta **faim n'est pas pleine**

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Overlay Saturation | :zap: RUSH | Montre la saturation sur la barre de faim |
        | Food Tooltip | - | Affiche les stats des aliments au survol |
        | Health Regen Preview | - | Prédit la régénération de vie |

??? note "Inventory Tweaks Refoxed"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/inventory-tweaks-refoxed)

    !!! success "Quick Start"
        1. Ouvre ton inventaire - les boutons de tri apparaissent
        2. Clique sur le **bouton de tri** (ou touche R par défaut)
        3. **Clic molette** sur un slot pour le verrouiller
        4. Configure les **règles de tri** dans les options
        5. Le tri fonctionne aussi dans les **coffres**

    === "Tips"

        !!! tip "Tri Automatique"
            - **Clic droit** sur le bouton de tri = options
            - Configure le **tri automatique** à l'ouverture des coffres
            - Les **slots verrouillés** ne sont jamais déplacés

        !!! tip "Raccourcis"
            - **Shift + clic** sur un item le déplace instantanément
            - **Double-clic** rassemble tous les items identiques
            - **Clic molette** verrouille/déverrouille un slot

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Bouton de tri | :zap: RUSH | Trie l'inventaire automatiquement |
        | Slots verrouillés | - | Empêche les items de bouger |
        | Tri automatique | - | Trie à l'ouverture des coffres |

??? note "Crafting Tweaks"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/crafting-tweaks)

    !!! success "Quick Start"
        1. Ouvre une **table de craft** - les boutons apparaissent
        2. Utilise **Rotate** pour tourner la grille de craft
        3. Utilise **Balance** pour équilibrer les items
        4. Utilise **Clear** pour vider la grille vers l'inventaire
        5. **Shift + clic** sur un item le transfert en masse

    === "Tips"

        !!! tip "Boutons de Craft"
            - **Rotate** : Tourne le pattern de 90 degrés
            - **Balance** : Répartit également les items
            - **Clear** : Renvoie tout dans l'inventaire

        !!! tip "Raccourcis"
            - **Clic molette** sur un slot = compresse/décompresse
            - Maintiens **Shift** pour des transferts en masse
            - Fonctionne dans toutes les grilles de craft (incluant autres mods)

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Bouton Rotate | - | Tourne le pattern de craft |
        | Bouton Balance | - | Équilibre les quantités |
        | Bouton Clear | - | Vide la grille de craft |

??? note "BetterF3"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/betterf3)

    !!! success "Quick Start"
        1. Appuie sur **F3** pour ouvrir le debug screen
        2. L'écran est maintenant **coloré et organisé**
        3. Configure les **modules** à afficher dans les options
        4. Utilise **F3 + Q** pour voir toutes les commandes F3
        5. Désactive les **infos inutiles** pour plus de clarté

    === "Tips"

        !!! tip "Modules"
            - **Coordonnées** : Ta position exacte XYZ
            - **FPS** : Performance du jeu
            - **Biome** : Le biome actuel
            - **Light Level** : Niveau de lumière (spawn de mobs)

        !!! warning "Performance"
            - L'écran F3 peut causer du **lag** si trop d'infos
            - Désactive les modules non utilisés
            - Utilise **Spark** pour un profiling plus précis

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Touche F3 | :zap: RUSH | Affiche le debug screen amélioré |
        | Config Modules | - | Personnalise les infos affichées |
        | F3 + Q | - | Liste toutes les commandes F3 |

??? note "Extreme Sound Muffler"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/extreme-sound-muffler)

    !!! success "Quick Start"
        1. Ouvre le menu avec la touche configurée (défaut: M?)
        2. Joue un **son** dans le jeu pour le voir apparaître
        3. Clique sur un son pour le **muter ou réduire**
        4. Utilise les **anchors** pour muter dans une zone spécifique
        5. Crée des **profils** pour différentes situations

    === "Tips"

        !!! tip "Sons Courants à Muter"
            - **Machines** de mods tech (bruit constant)
            - **Portails** du Nether (très bruyant)
            - **Villageois** (sons répétitifs)
            - **Wither/Dragon** (boss sounds)

        !!! tip "Anchors"
            - Les **anchors** mutent les sons dans une zone
            - Place un anchor près de tes machines
            - Le son revient en dehors de la zone

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Menu Principal | :zap: RUSH | Interface pour muter les sons |
        | Sound Anchor | - | Mute les sons dans une zone |
        | Profiles | - | Sauvegarde différentes configs |

??? note "Just Zoom"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/just-zoom)

    !!! success "Quick Start"
        1. Maintiens la touche **C** (ou configurée)
        2. Le zoom s'active tant que tu maintiens
        3. Utilise la **molette** pour ajuster le niveau de zoom
        4. Relâche pour revenir à la vue normale

    === "Tips"

        !!! tip "Configuration"
            - Le niveau de **zoom max** est configurable
            - Le **smooth zoom** rend la transition plus douce
            - Compatible avec les **shaders** (la plupart)

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Touche Zoom | :zap: RUSH | Active le zoom |
        | Molette | - | Ajuste le niveau de zoom |

??? note "More Overlays Updated"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/more-overlays-updated)

    !!! success "Quick Start"
        1. Appuie sur **F7** pour afficher les overlays de spawn
        2. Les **croix jaunes** = mobs spawneront la nuit
        3. Les **croix rouges** = mobs peuvent spawner maintenant
        4. Utilise pour **light-proof** ta base

    === "Tips"

        !!! tip "Light Level"
            - Les mobs spawn si **light level < 1** (1.18+)
            - Place des torches sur toutes les croix rouges
            - Vérifie après avoir placé les lumières

        !!! warning "Performance"
            - L'overlay peut causer du **lag** dans les grandes zones
            - Désactive après avoir éclairé la zone

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Touche F7 | :zap: RUSH | Affiche les zones de spawn |
        | Croix Jaunes | - | Spawn possible la nuit |
        | Croix Rouges | - | Spawn possible maintenant |

??? note "Clumps"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/clumps)

    !!! success "Quick Start"
        1. Installe le mod - **aucune configuration nécessaire**
        2. Les orbes d'XP se **regroupent automatiquement**
        3. Réduit le **lag** des mob farms
        4. L'XP totale reste identique

    === "Tips"

        !!! tip "Performance"
            - Essentiel pour les **mob farms**
            - Réduit drastiquement les **entités**
            - Invisible mais très efficace

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | XP Orbs Groupés | :zap: RUSH | Automatique, réduit le lag |

??? note "Fast Leaf Decay"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fast-leaf-decay)

    !!! success "Quick Start"
        1. Installe le mod - **automatique**
        2. Coupe un arbre
        3. Les feuilles **disparaissent rapidement**
        4. Les **drops** (saplings, apples) apparaissent vite

    === "Tips"

        !!! tip "Configuration"
            - La **vitesse** de decay est configurable
            - Fonctionne avec les **arbres moddés**
            - Ne casse pas les feuilles placées par joueur

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Leaf Decay | :zap: RUSH | Les feuilles disparaissent vite |

??? note "FindMe"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/findme)

    !!! success "Quick Start"
        1. Survole un item dans JEI ou ton inventaire
        2. Appuie sur la touche **Y** (ou configurée)
        3. Les coffres contenant cet item **brillent**
        4. Utile pour retrouver des items perdus

    === "Tips"

        !!! tip "Utilisation"
            - Fonctionne à travers les **murs**
            - La **portée** est configurable
            - Compatible avec la plupart des **containers moddés**

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Touche FindMe | - | Illumine les coffres avec l'item |

??? note "Harvest with Ease"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/harvest-with-ease)

    !!! success "Quick Start"
        1. Installe le mod
        2. **Clic droit** sur une culture mature
        3. La culture est **récoltée et replantée** automatiquement
        4. Fonctionne avec la plupart des **crops moddées**

    === "Tips"

        !!! tip "Combine avec FTB Ultimine"
            - Maintiens **Ultimine + clic droit** = récolte massive
            - Parfait pour les grands champs

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Clic Droit Harvest | :zap: RUSH | Récolte et replante en un clic |

---

## Mods Techniques (Background)

??? note "Mods de Stabilité"

    | Mod | Description |
    |-----|-------------|
    | [Attribute Fix](https://www.curseforge.com/minecraft/mc-mods/attributefix) | Corrige les limites d'attributs vanilla |
    | [Login Protection](https://www.curseforge.com/minecraft/mc-mods/login-protection) | Protège les joueurs pendant le chargement |
    | [Packet Fixer](https://www.curseforge.com/minecraft/mc-mods/packet-fixer) | Corrige les problèmes de paquets réseau |
    | [Connectivity](https://www.curseforge.com/minecraft/mc-mods/connectivity) | Améliore la connexion client/serveur |

??? note "Mods de Performance"

    | Mod | Description |
    |-----|-------------|
    | [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fastfurnace) | Optimise les fours |
    | [FastSuite](https://www.curseforge.com/minecraft/mc-mods/fastsuite) | Optimise les recettes |
    | [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements) | Optimise l'IA des mobs |
    | [Get It Together, Drops!](https://www.curseforge.com/minecraft/mc-mods/get-it-together-drops) | Regroupe les drops |
    | [Spark](https://www.curseforge.com/minecraft/mc-mods/spark) | Profiler de performance |
    | [Observable](https://www.curseforge.com/minecraft/mc-mods/observable) | Trouve les sources de lag |

??? note "Mods de Debug"

    | Mod | Description |
    |-----|-------------|
    | [Crash Assistant](https://www.curseforge.com/minecraft/mc-mods/crash-assistant) | Aide à comprendre les crashes |
    | [Crash Utilities](https://www.curseforge.com/minecraft/mc-mods/crash-utilities) | Outils pour débugger |
    | [Better Compatibility Checker](https://www.curseforge.com/minecraft/mc-mods/better-compatibility-checker) | Vérifie la compatibilité des mods |

??? note "Mods de Compatibilité"

    | Mod | Description |
    |-----|-------------|
    | [Almost Unified](https://www.curseforge.com/minecraft/mc-mods/almost-unified) | Unifie les items dupliqués (copper, etc.) |
    | [Common Capabilities](https://www.curseforge.com/minecraft/mc-mods/common-capabilities) | API commune entre mods |

---

## Sources de Mods QOL

Les meilleurs modpacks pour découvrir des mods QOL :

- **All The Mods (ATM)** - Collection exhaustive de QOL
- **Ragnamod** - Sélection curated de QOL
- **FTB packs** - QOL bien intégrés

Ces packs incluent de nombreux petits mods QOL à explorer et adapter à ton gameplay.
