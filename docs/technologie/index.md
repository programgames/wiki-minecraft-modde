# Technologie

<div class="grid cards" markdown>

-   :gear: **Applied Energistics 2**

    ---

    Stockage digital et autocrafting massif. Le cerveau de ta base end-game.

    [:octicons-arrow-right-24: Découvrir](#applied-energistics-2)

-   :factory: **Create**

    ---

    Mécanique et automatisation visuelle. Rotation, trains et contraptions.

    [:octicons-arrow-right-24: Découvrir](#create)

-   :zap: **Mekanism**

    ---

    Technologie avancée, ore processing 5x et armure MekaSuit ultime.

    [:octicons-arrow-right-24: Découvrir](#mekanism)

-   :fire: **Thermal Series**

    ---

    Processing modulaire et énergie. Augments et dynamos configurables.

    [:octicons-arrow-right-24: Découvrir](#thermal-series)

</div>

!!! info "Mods Secondaires"
    **Immersive Engineering** (rétro-industriel) | **Industrial Foregoing** (mob farms) | **Ender IO** (conduits) | **PneumaticCraft** (pression) | **RFTools** (builder/quarry) | **Flux Networks** (énergie sans fil) | **Draconic Evolution** (end-game) | **Ad Astra** (exploration spatiale)

    [:octicons-arrow-down-24: Voir les mods secondaires](#mods-secondaires)

## Comparaison Rapide

| Mod | Difficulté | Phase | Recommandé pour |
|-----|:----------:|:-----:|-----------------|
| Applied Energistics 2 | 3/5 | Mid → Late | Stockage digital, autocrafting |
| Create | 2/5 | Early → Late | Automation visuelle, trains |
| Mekanism | 3/5 | Early → Late | Ore 5x, MekaSuit end-game |
| Thermal Series | 2/5 | Early → Mid | Ore 2x rapide, augments |
| Industrial Foregoing | 2/5 | Mid → Late | Mob farms, Laser Drill |
| Ender IO | 2/5 | Mid → Late | Conduits tout-en-un |
| PneumaticCraft | 4/5 | Mid → Late | Drones programmables |
| RFTools | 2/5 | Early → Late | Mini-AE2, Builder quarry |
| Flux Networks | 1/5 | Mid → Late | Énergie sans fil cross-dim |
| Draconic Evolution | 4/5 | Late | Outils/armures ultimes |

## Progression Recommandée

!!! tip "Early Game"
    - :zap: **[RUSH]** Create pour le processing basique (Mechanical Saw, Hand Crank)
    - :zap: **[RUSH]** Thermal Pulverizer pour le doublage de minerais
    - :zap: **[RUSH]** RFTools Storage Scanner + Tablet = mini système de stockage
    - Simple Storage Network comme premier système de stockage centralisé

!!! note "Mid Game"
    - Développer **Mekanism** pour ore processing 3x/4x
    - **AE2** pour stockage digital et autocrafting
    - **Industrial Foregoing** pour les mob farms automatisées
    - **Flux Networks** pour la distribution d'énergie sans fil

!!! success "Late Game"
    - AE2 avec tous les addons pour autocrafting massif
    - Mekanism Fission/Fusion pour énergie infinie
    - **Draconic Evolution** pour les outils et armures ultimes
    - **MekaSuit** modulaire avec tous les upgrades

## Synergies entre Mods

!!! abstract "Combinaisons Puissantes"

    **AE2 + Mekanism** (via Applied Mekanistics)
    :   Stockage des gaz et slurries dans le système AE2

    **Create + Thermal** (via Create Crafts & Additions)
    :   Conversion énergie RF ↔ Rotation pour alimenter les deux systèmes

    **AE2 + Botania** (via Applied Botanics)
    :   Stockage et gestion du mana dans le réseau AE2

    **Mekanism + Industrial Foregoing**
    :   Digital Miner + Laser Drill = ressources infinies

    **Flux Networks + Tout**
    :   Distribution d'énergie cross-dimension vers toutes les machines

---

## Applied Energistics 2

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2) | [Guide Officiel](https://guide.appliedenergistics.org/) | [All The Guides](https://allthemods.github.io/alltheguides/mods/ae2/)

!!! success "Quick Start"
    1. Mine du **Certus Quartz** et des **Meteorites** pour les presses
    2. Craft un **Charger** et charge du Certus Quartz
    3. Crée des **Fluix Crystals** en jetant Charged Certus + Redstone + Nether Quartz dans l'eau
    4. Construit un **Inscriber** pour fabriquer les processeurs
    5. Place un **ME Controller** + **ME Drive** + **Terminal** pour ton premier réseau

### Addons

- [Advanced AE](https://www.curseforge.com/minecraft/mc-mods/advancedae) : Export bus amélioré, disques, tour à craft, pattern provider amélioré, wireless, inscriber amélioré
- [AE Additions](https://www.curseforge.com/minecraft/mc-mods/ae-additions-extra-cells-2-fork) : Wireless et super dense energy cells
- [Wireless Terminal](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2-wireless-terminals) / [AE Infinity Booster](https://www.curseforge.com/minecraft/mc-mods/aeinfinitybooster) : Accès sans fil illimité
- [Mega Cells](https://www.curseforge.com/minecraft/mc-mods/mega-cells) : Gros disques, advanced inscriber
- [Applied Mekanistics](https://www.curseforge.com/minecraft/mc-mods/applied-mekanistics) : Intégration Mekanism (gaz, slurry)
- [Applied Flux](https://www.curseforge.com/minecraft/mc-mods/applied-flux) : Intégration énergie
- [Applied Botanics](https://www.curseforge.com/minecraft/mc-mods/applied-botanics-addon) : Intégration Botania (mana)
- [Ars Énergistique](https://www.curseforge.com/minecraft/mc-mods/ars-energistique) : Intégration Ars Nouveau
- [ME Requester](https://www.curseforge.com/minecraft/mc-mods/merequester) : Requêtes automatiques de stock

=== "Tips"

    !!! tip "Channels & Networking"
        - **Dense Smart Cable** = 32 channels (vs 8 pour câble normal)
        - **P2P Tunnels** pour transporter 32 channels dans un seul câble
        - **Quartz Fiber** transfère l'énergie sans connecter les channels
        - Les **Molecular Assemblers ne consomment pas de channel** mais en transfèrent 8

    !!! tip "Autocrafting Setup"
        - **Pattern Provider entouré de 6 Molecular Assemblers** = setup optimal
        - Utiliser des **Acceleration Cards** dans les Assemblers pour plus de vitesse
        - **Blocking Mode** sur Pattern Provider pour machines qui ne prennent qu'un batch à la fois
        - Séparer les **crafting steps** pour paralléliser les jobs
        - Pour les **crafts répétitifs**, utiliser la modification des quantités pour crafter par batch (ça change tout!)

    !!! tip "Planification Réseau"
        - Commencer et prévoir son réseau AE2 **propre et extensible dès le début**
        - Choisir entre **channels vs wireless** selon votre style de jeu
        - Utiliser **tous les types de cells** avec les addons : Infinity, Mega, FE Storage, Chemical, Source, Mana, Fluid...

    !!! tip "Subnetworks & Optimisation"
        - Créer un **sous-réseau dédié** aux machines lourdes (ex: Mekanism)
        - Relier au réseau principal via **Storage Bus** pour éviter les conflits de channels
        - **ME Chest avec priorité élevée** = buffer pour items importants
        - **Level Emitter + Crafting Card** = autocraft quand le stock descend sous un seuil

    !!! warning "Attention"
        - **Middle click** dans le terminal pour ajuster les quantités des crafts
        - On peut changer l'incrément du nombre d'objets par batch dans la **config AE2**
        - Utiliser des **nuggets pour réparer outils Tinkers** = économie de ressources

    !!! example "Setups Utiles"
        - **Crystal Growth Accelerators** autour des cristaux dans l'eau = growth x17 plus rapide
        - **Storage Bus sur un chest** comme buffer temporaire pour les crafts
        - **Formation Plane** peut placer des blocs dans le monde automatiquement
        - **Level Emitter** émet redstone quand un item atteint un seuil
        - **Mechanical Arm (Create)** peut importer vers ME Interface = intégration Create dans l'autocrafting

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | ME Controller | :zap: RUSH | Cerveau du réseau (obligatoire pour >8 channels) |
    | ME Drive | - | Contient les disques de stockage |
    | Inscriber | :zap: RUSH | Fabrique les processeurs (crucial early) |
    | Charger | - | Charge les outils et certum quartz |
    | Fluix Crystal | - | Matériau de base (craft dans l'eau) |
    | Crafting CPU | - | Gère les jobs d'autocrafting |
    | Pattern Provider | - | Envoie les items aux machines externes |
    | Molecular Assembler | - | Craft les recettes internes |
    | ME Terminal | - | Interface utilisateur |
    | Import/Export Bus | | Transfert automatique avec le monde |
    | Storage Bus | | Connecte des inventaires externes au réseau |

=== "Guides"

    - [Autocrafting Guide](https://guide.appliedenergistics.org/1.20.1/ae2-mechanics/autocrafting)
    - [Tips Reddit ATM](https://www.reddit.com/r/allthemods/comments/1jzyulf/ae2_tips_and_tricks/)
    - [Recursive Crafting Setup](https://guide.appliedenergistics.org/1.20.4/example-setups/recursive-crafting-setup)

---

## Create

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/create) | [Wiki](https://create.fandom.com/wiki/) | [CreateMod Wiki](https://createmod.wiki/)

!!! success "Quick Start"
    1. Craft un **Hand Crank** et une **Millstone** pour le processing basique
    2. Place un **Water Wheel** dans de l'eau courante pour génération passive
    3. Connecte les machines avec des **Shafts** et **Cogwheels**
    4. Utilise un **Mechanical Press** pour faire des sheets et compacter
    5. Upgrade vers les **Brass components** pour plus de fonctionnalités

### Addons

- [Create Crafts & Additions](https://www.curseforge.com/minecraft/mc-mods/createaddition) : Énergie RF ↔ Rotation
- [Create Jetpack](https://www.curseforge.com/minecraft/mc-mods/create-jetpack)
- [Create Ore Excavation](https://www.curseforge.com/minecraft/mc-mods/create-ore-excavation) : Mining automatique
- [Create Slice & Dice](https://www.curseforge.com/minecraft/mc-mods/slice-and-dice) : Cuisine automatisée
- [Create: Enchantment Industry](https://www.curseforge.com/minecraft/mc-mods/create-enchantment-industry)
- [Create: New Age](https://www.curseforge.com/minecraft/mc-mods/create-new-age) : Énergie solaire et nucléaire
- [Create: Steam 'n' Rails](https://www.curseforge.com/minecraft/mc-mods/create-steam-n-rails) : Trains

=== "Tips"

    !!! tip "Rotational Force Basics"
        - **Rotational Force** a 3 caractéristiques : direction, vitesse (RPM), et Stress (SU)
        - Utiliser un **Speedometer** pour voir les RPM
        - **Cogwheel** inverse la rotation et double/divise la vitesse
        - Le **Stress** est partagé sur tout le réseau connecté

    !!! tip "Processing & Automation"
        - :zap: **[RUSH]** **Mechanical Saw + Hand Crank** = bois facile en early game
        - **Encased Fan** avec lave/eau/feu = processing automatique (smelting, washing, haunting)
        - **Deployer** peut simuler un joueur (right-click, crafting, enchanting)
        - **Mechanical Crafter** pour les recettes en forme (shaped crafting auto)

    !!! warning "Performance"
        - Les **Contraptions** trop grandes peuvent causer du lag
        - **Clipboard** pour copier des configs entre machines

    !!! example "Setups Avancés"
        - **Steam Engine** + Boiler = meilleure génération mid-game
        - **Contraptions** avec Portable Storage Interface = systèmes mobiles
        - Les **Trains** sont le meilleur transport long-distance
        - **Mechanical Harvester sur Bearing** = farm rotative automatique, ajouter un Deployer pour replanter
        - **Schematicannon + chest AE2** = constructions automatiques à grande échelle depuis un fichier .nbt

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Hand Crank | :zap: RUSH | Génère de la rotation manuellement (early) |
    | Water Wheel | - | Génère rotation avec eau courante |
    | Windmill | - | Génère rotation avec le vent |
    | Steam Engine | - | Génération puissante avec vapeur |
    | Mechanical Press | - | Compresse les items, fait des sheets |
    | Mechanical Saw | :zap: RUSH | Coupe bois, tue mobs |
    | Millstone | - | Broie les items (early) |
    | Crushing Wheels | | Version améliorée du Millstone |
    | Mixer | - | Mélange les recettes |
    | Deployer | - | Utilise des items comme un joueur |
    | Mechanical Arm | | Transporte items entre inventaires |
    | Schematicannon | | Place des structures automatiquement |

=== "Guides"

    - [Rotational Force Wiki](https://create.fandom.com/wiki/Rotational_Force)
    - [Generate and Convey GitHub](https://github.com/Creators-of-Create/Create/wiki/Generate-and-Convey)

---

## Mekanism

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/mekanism) | [Wiki Officiel](https://wiki.aidancbrady.com/wiki/)

!!! success "Quick Start"
    1. Mine de l'**Osmium** et craft un **Metallurgic Infuser**
    2. Infuse du fer avec du charbon pour créer de l'**Enriched Iron**
    3. Craft une **Enrichment Chamber** pour le ore doubling (2x)
    4. Utilise le **Configurator** pour configurer les faces des machines
    5. Upgrade vers les **Factories** pour le processing multi-slot

### Addons

- [Mekanism Generators](https://www.curseforge.com/minecraft/mc-mods/mekanism-generators) : Fission, Fusion, Turbines
- [Mekanism Tools](https://www.curseforge.com/minecraft/mc-mods/mekanism-tools) : Outils en Refined materials
- [Gravitational Modulating Additional Unit](https://www.curseforge.com/minecraft/mc-mods/gravitational-modulating-additional-unit) : Modules de gravité

=== "Tips"

    !!! tip "Ore Processing Tiers"
        - **Tier 1 (2x)** : Enrichment Chamber → 2 dusts par ore → smelt = 2 ingots
        - **Tier 2 (3x)** : Purification Chamber avec Oxygen
        - **Tier 3 (4x)** : Chemical Injection Chamber + Hydrogen Chloride
        - **Tier 4 (5x)** : Chemical Dissolution Chamber + Sulfuric Acid → Slurry → Crystallizer

    !!! tip "Machine Setup"
        - Placer les machines **côte à côte** pour transfert direct (économise des pipes)
        - Utiliser le **Configurator** pour configurer push/pull sur les faces
        - **Speed Upgrades** (8 max) accélèrent toutes les machines
        - **Factories** sont des versions multi-slot des machines

    !!! warning "Power & Efficiency"
        - **Energy Upgrades** réduisent la consommation d'énergie
        - **Anchor Upgrades** chunk-load les machines

    !!! example "Items Utiles"
        - **Digital Miner** peut filter par mod, nom, ou tag
        - **Cardboard Box** peut déplacer n'importe quel bloc avec son contenu
        - **Gauge Dropper** pour vider les machines de leurs fluides/gaz
        - **Robit** est un compagnon portable avec crafting table, chest, et furnace
        - **Diversion Transporter** : transfère seulement avec un signal redstone

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Metallurgic Infuser | :zap: RUSH | Infuse des matériaux (crucial pour crafts) |
    | Enrichment Chamber | :zap: RUSH | Ore doubling (2x) |
    | Purification Chamber | - | Ore tripling (3x) avec Oxygen |
    | Chemical Injection Chamber | - | Ore quadrupling (4x) |
    | Chemical Dissolution Chamber | | Ore quintupling (5x) |
    | Digital Miner | - | Mine automatiquement selon des filtres |
    | Teleporter | - | Téléportation entre bases |
    | Jetpack | - | Vol early-mid game |
    | Atomic Disassembler | - | Multi-tool puissant |
    | MekaSuit | - | Armure modulaire end-game |
    | Fission Reactor | | Génération d'énergie massive |
    | Fusion Reactor | | Énergie quasi-infinie (end-game) |
    | QIO Drive Array | | Stockage end-game (comme AE2) |

=== "Guides"

    - [Getting Started Tutorial](https://wiki.aidancbrady.com/wiki/Tutorials/Getting_Started)
    - [Ore Processing Guide](https://wiki.aidancbrady.com/wiki/Ore_Processing)
    - [Ore Processing ATM Guide](https://jangro.com/2024/12/22/mastering-mekanism-ore-processing-from-2x-3x-4x-to-5x)
    - [Schémas Énergie (Google Drive)](https://drive.google.com/drive/folders/1-qBYHOeW_2hcmvpxyCtwaYuf6TTEZLNU)
    - [Réacteur Fission Max (Reddit)](https://www.reddit.com/r/feedthebeast/comments/m109gs/making_the_largest_fission_reactor_from_mekanism/)

---

## Thermal Series

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/thermal-expansion) | [Docs Officiels](https://teamcofh.com/docs/)

!!! success "Quick Start"
    1. Craft un **Pulverizer** pour doubler tes minerais
    2. Craft une **Redstone Furnace** pour la cuisson rapide
    3. Place un **Dynamo** (Stirling ou Steam) pour l'énergie
    4. Utilise un **Fluxduct** pour connecter l'énergie
    5. Ajoute des **Augments** pour améliorer les machines

### Addons

- Thermal Foundation - Basics and Resources
- Thermal Cultivation - Farming and Foods
- Thermal Dynamics - Logistics and Transport
- Thermal Innovation - Advanced Power Tools and Gadgets
- Thermal Integration - Modded Compatibility
- [Thermal Extra](https://www.curseforge.com/minecraft/mc-mods/thermal-extra)

=== "Tips"

    !!! tip "Augments System"
        - Les **Augments** modifient les machines (4 slots par machine)
        - Les augments de **tier supérieur nécessitent les inférieurs**
        - **Compression Dynamo + Spark Plugs + 3 Transmission Coils** = 760 RF/t

    !!! tip "Farming & Resources"
        - **Phyto-Gro** accélère la croissance des crops massivement
        - **Aqueous Accumulator** = source d'eau infinie
        - **Phyto Soil** fait pousser les crops plus vite

    !!! warning "Énergie"
        - Les **Dynamos peuvent être tiered up** pour plus d'efficacité
        - Commencer avec **Stirling Dynamo** (charbon) ou **Steam Dynamo**

    !!! example "Machines Utiles"
        - **Pulverizer** pour ore doubling + byproducts
        - **Induction Smelter** pour créer les alliages
        - **Fluid Transposer** pour ajouter/retirer fluides des items
        - **Phytogenic Insolator** pour farming automatique - [Guide d'automatisation](https://imgur.com/a/auto-phytogenic-insolator-upgrading-configurating-wt6uTT6)

    !!! success "Augments Cachés"
        Les machines Thermal acceptent des **Augments** qui changent fondamentalement leur comportement :

        - **Pulverizer + Reagent Recovery** : conserve les réactifs
        - **Fluid Encapsulator + Trivection Chamber** : cuit les items dans le fluide
        - Explorez JEI systématiquement — beaucoup sont sous-documentés !

    !!! tip "Satchel Auto-Tri"
        Le **Satchel filtrable** aspire automatiquement certains types d'items (ores, drops) de votre inventaire vers le sac, ou bloque certains items. Indispensable en mining pour garder l'inventaire propre sans gestion manuelle.

=== "Objets Importants"

    | Objet | Priorité | Description |
    |-------|:--------:|-------------|
    | Pulverizer | :zap: RUSH | Ore doubling + chance de byproducts |
    | Redstone Furnace | - | Furnace rapide avec augments |
    | Induction Smelter | - | Combine minerais pour alliages |
    | Fluid Transposer | | Ajoute/retire fluides des items |
    | Dynamos | - | Génération d'énergie (Steam, Magmatic, etc.) |
    | Energy Cell | - | Stockage d'énergie |
    | Aqueous Accumulator | - | Source d'eau infinie |
    | Phyto Soil | | Sol qui accélère les crops |
    | Watering Can | | Accélère crops manuellement |
    | Insightful Crystal | - | Stocke jusqu'à 63 niveaux d'XP |
    | Fluxduct | - | Câbles d'énergie |
    | Itemduct / Servos | | Transport d'items |
    | Satchel | | Inventaire portable |

=== "Guides"

    - [Team CoFH Documentation](https://teamcofh.com/docs/)
    - [Thermal Series Guide](https://ftb.fandom.com/wiki/Thermal_Expansion_5)

---

## Mods Secondaires

??? note "Immersive Engineering"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/immersive-engineering) | [Wiki](https://ftb.fandom.com/wiki/Immersive_Engineering)

    !!! success "Quick Start"
        1. Craft un **Engineer's Manual** (livre + levier)
        2. Construit un **Coke Oven** (multiblock) pour créer du Coke et Creosote
        3. Construit un **Blast Furnace** pour faire de l'acier
        4. Craft des **Wires** et **Connectors** pour transporter l'énergie
        5. Place un **Water Wheel** ou **Windmill** pour générer du IF (énergie)

    === "Tips"

        !!! tip "Multiblocks Importants"
            - **Coke Oven** : Crée du Coke (charbon amélioré) et Creosote Oil
            - **Blast Furnace** : Fer + Coke = Steel (acier)
            - **Crusher** : Ore doubling avec animations visuelles
            - **Excavator** : Mine automatiquement des veines de minerais
            - **Garden Cloche** : Farming automatique compact

        !!! tip "Énergie & Câbles"
            - Les **câbles suspendus** donnent un look industriel unique
            - Les **Connectors** ont différentes capacités (LV, MV, HV)
            - **Wire Coils** pour connecter sur de longues distances
            - Compatible avec RF/FE des autres mods

        !!! warning "Esthétique"
            - L'un des mods tech les plus **visuellement impressionnants**
            - Les machines ont des animations détaillées
            - Parfait pour les bases industrielles réalistes

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Engineer's Manual | :zap: RUSH | Guide in-game essentiel |
        | Coke Oven | :zap: RUSH | Premier multiblock, crée Coke + Creosote |
        | Blast Furnace | - | Crée l'acier (Steel) |
        | Crusher | - | Ore doubling avec style |
        | Garden Cloche | - | Farming automatique compact |
        | Excavator | - | Mining automatique de zone |
        | Water Wheel | - | Génération passive d'énergie |
        | Windmill | | Génération avec le vent |
        | Wire Connectors | - | Transfert d'énergie avec câbles |
        | Revolver | | Arme à feu customisable |
        | Railgun | | Arme end-game puissante |
        | Turrets | | Défense automatique |
        | Charging Station | | Recharge outils électriques |
        | Silo | | Stockage de masse |

    **Addon:** [Immersive Petroleum](https://www.curseforge.com/minecraft/mc-mods/immersive-petroleum) - Pétrole, raffinage, bateaux améliorés

    === "Immersive Petroleum"

        | Objet | Description |
        |-------|-------------|
        | Seismic Survey Tool | Trouver des fluides souterrains |
        | Motorboat | Bateau amélioré plus rapide |
        | Pumpjack | Extrait le pétrole |
        | Distillation Tower | Raffine le pétrole |
        | Asphalt Concrete | Bloc de route qui donne Speed |

??? note "Ad Astra"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ad-astra)

    !!! success "Quick Start"
        1. Construis un **NASA Workbench** pour les crafts spatiaux
        2. Craft une **Rocket** et du **Fuel**
        3. Lance-toi vers la **Lune** puis **Mars** et au-delà
        4. Établis des bases avec des **Oxygen Generators**
        5. Explore les planètes pour des ressources uniques

    === "Tips"

        !!! tip "Exploration Spatiale"
            - Progression : **Lune → Mars → Venus → Mercury → Glacio**
            - Chaque planète a des **ressources uniques**
            - Nécessite de l'**oxygène** et de la protection
            - Les véhicules incluent **Rovers** et **Rockets**

        !!! warning "Survie Spatiale"
            - L'**oxygène** est critique hors de l'Overworld
            - La **température** varie selon les planètes
            - Les **combinaisons spatiales** sont obligatoires

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | NASA Workbench | :zap: RUSH | Crafting des items spatiaux |
        | Space Suit | - | Protection spatiale |
        | Rocket | - | Transport vers les planètes |
        | Oxygen Gear | - | Respiration hors atmosphère |
        | Oxygen Generator | - | Produit O2 pour les bases |
        | Rover | | Véhicule de surface |

    **Addon:** [Giselle Addon](https://www.curseforge.com/minecraft/mc-mods/ad-astra-giselle-addon) - QoL et features supplémentaires

??? note "Industrial Foregoing"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/industrial-foregoing) | [Guide SkyFactory](https://skyfactory-4.fandom.com/wiki/Industrial_Foregoing)

    !!! success "Quick Start"
        1. Craft un **Mob Crusher** pour tuer les mobs automatiquement
        2. Place un **Plant Sower** + **Plant Gatherer** pour le farming
        3. Alimente avec de l'énergie RF
        4. Upgrade vers le **Laser Drill** pour ressources infinies

    === "Tips"

        !!! tip "Mob Farming"
            - **Mob Crusher** fait 300 dégâts par opération, tue tout sauf Wither en un coup
            - Mob Crusher ne tue **pas les bébés animaux** (utile pour breeding farms)
            - Activer **Looting Mode** sur Mob Crusher désactive l'Essence mais donne du loot bonus

        !!! tip "Resources"
            - **Laser Drill** : 4 Laser Drills alimentent 1 Laser Base, doit voir la bedrock
            - Les **lenses** du Laser Drill modifient les drops possibles
            - **Mob Duplicator** + Safari Net = infinite mob spawning

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Mob Crusher | - | Tue les mobs et stocke l'Essence |
        | Mob Duplicator | - | Duplique les mobs capturés |
        | Plant Gatherer / Sower | - | Farming automatique |
        | Laser Drill / Laser Base | - | Génère des ressources depuis le void |
        | Black Hole Unit | - | Stockage massif d'un type d'item |
        | Black Hole Tank | | Stockage massif de fluides |
        | Hydroponic Bed | | Accélère les crops |
        | Meat Feeder | | Mange automatiquement |

    **Addon:** [Industrial Foregoing Souls](https://www.curseforge.com/minecraft/mc-mods/industrial-foregoing-souls)

??? note "Ender IO"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ender-io) | [Wiki](https://enderio.com/)

    !!! success "Quick Start"
        1. Craft un **SAG Mill** pour le ore processing
        2. Craft un **Alloy Smelter** pour créer les alliages
        3. Utilise des **Conduits** pour connecter items, fluides et énergie
        4. Upgrade vers les **Dark Steel Tools** pour le mining

    === "Tips"

        !!! tip "Conduits"
            - Mod tech **tout-en-un** : machines, conduits, outils, armures
            - Les **Conduits** transportent items, fluides, énergie, redstone dans le même bloc
            - Utilise les filtres pour diriger les items précisément

        !!! tip "Machines"
            - **Capacitor Banks** pour stocker l'énergie (tiers)
            - **Powered Spawner** = spawner alimenté en énergie
            - **Dimensional Transceiver** pour transfert cross-dimension

        !!! warning "Dark Steel"
            - Les **Dark Steel Tools** sont upgradables avec des enchants spéciaux
            - Nécessite de l'XP pour les empowered modes

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Conduits | :zap: RUSH | Transport tout-en-un (item, fluid, energy) |
        | SAG Mill | - | Ore doubling + byproducts |
        | Alloy Smelter | - | Crée les alliages (Dark Steel, etc.) |
        | Capacitor Bank | - | Stockage d'énergie |
        | Powered Spawner | - | Spawner alimenté en RF |
        | Dark Steel Tools | - | Outils upgradables (empowered) |
        | Dark Steel Armor | | Armure upgradable |
        | Travel Anchor | | Téléportation courte distance |
        | Soul Vial | | Capture l'âme des mobs |

    === "Conduits Reference"

        | Type | Fonction |
        |------|----------|
        | Energy Conduit | Transport d'énergie |
        | Item Conduit | Transport d'items |
        | Fluid Conduit | Transport de fluides |
        | Redstone Conduit | Signal redstone |
        | ME Conduit | Intégration AE2 |

    **Guides:** [Getting Started](https://ftb.fandom.com/wiki/Getting_Started_(Ender_IO)) | [Conduits Guide](https://ftb.fandom.com/wiki/Conduit_(Ender_IO))

??? note "PneumaticCraft: Repressurized"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/pneumaticcraft-repressurized) | [Guide Enigmatica](https://wiki.enigmatica.net/enigmatica6/gameplay/how-to.../pneumaticcraft-heating-and-cooling)

    !!! success "Quick Start"
        1. Craft un **Air Compressor** et alimente-le en combustible
        2. Connecte avec des **Pressure Tubes**
        3. Construit une **Pressure Chamber** pour les crafts
        4. Utilise un **Seismic Sensor** pour trouver le pétrole

    === "Tips"

        !!! tip "Pression System"
            - Le système de **pression** est unique : quantité d'air / volume = pression
            - Les machines chauffent à l'utilisation, deviennent moins efficaces
            - **Heat Sinks** sur les compresseurs dissipent la chaleur

        !!! warning "Efficiency"
            - **Advanced Compressor** à 100% efficacité en dessous de 50°C
            - Surveille la température pour éviter les explosions

        !!! tip "Drones"
            - Les **Drones** peuvent prendre jusqu'à 15 Armor Upgrades
            - Les Drones peuvent **Match by Block** pour matcher des blocs spécifiques

        !!! success "Drones Programmables"
            Les **Drones PneumaticCraft** sont programmables via un éditeur visuel. Ils peuvent miner, farmer, transporter, combattre et interagir avec des inventaires. Un Drone bien configuré remplace un réseau entier de machines pour des tâches complexes et conditionnelles.

        !!! success "Amadron Automation"
            Le système marchand **Amadron** échange des ressources automatiquement via des Tablets programmables. Couplé à une **Pressure Chamber automatisée** et un réseau AE2, convertit des items abondants en ressources rares en continu, sans intervention.

        !!! example "Pressure Chamber pour Enchantements"
            La **Pressure Chamber** (3x3x3 suffit, pression > 2.0 bar) peut appliquer des enchantements qui bypass les caps de l'enclume normale. Elle peut même combiner des enchantements normalement incompatibles (ex: Decrepitude + Sanctified).

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Air Compressor | - | Génère de l'air comprimé |
        | Pressure Chamber | - | Crafting avec pression + enchantements spéciaux |
        | Assembly System | | Crafting automatisé avancé |
        | Drone | - | Automatisation programmable complète |
        | Pneumatic Jackhammer | - | Outil de minage puissant |
        | Refinery | | Raffine le pétrole en fuel |
        | Seismic Sensor | - | Trouve le pétrole |
        | Heat Sink | - | Dissipe la chaleur |
        | Minigun | | Arme à distance puissante |
        | Liquid Hopper | | Hopper pour fluides |
        | Omni Hopper | | Hopper universel items+fluides |
        | Reinforced Chest | | Coffre améliorable |
        | Thermal Lagging | | Évite rejet de chaleur |
        | Gas Lift | | Pompe fluides + détection |
        | Air Grate Module | | Attire les mobs |
        | Logistic Modules | | Transport items/liquides |
        | Sentry Turret | | Défense automatique |
        | Kerosene Lamp | | Torch portable (30 blocs range) |
        | Air Cannon | | Transport d'items à distance |
        | Elevator | | Ascenseur pneumatique |
        | Collector Drone | | Ramasse items par terre |
        | Harvesting Drone | | Récolte automatique |
        | Memory Stick | | Gérer XP joueur |
        | Aerial Interface | | Connecte au joueur (auto-feeding, charge) |
        | Transfer Gadget | | Transfert item/fluid entre 2 blocs |
        | Crop Support | | Accélère croissance |
        | Vacuum Trap | | Capture mobs |

    **Guide:** [Guide Reddit ATM](https://www.reddit.com/r/allthemods/comments/1d05ovt/pneumaticcraft_repressurized_guide/)

??? note "RFTools"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/rftools-base) | [Wiki GitHub](https://github.com/McJtyMods/RFTools/wiki)

    !!! success "Quick Start"
        1. Craft un **Storage Scanner** (mini AE2!)
        2. Place des coffres autour et le Scanner les détecte
        3. Craft un **Tablet** pour accès distant
        4. Utilise le **Builder** comme quarry

    === "Tips"

        !!! tip "Storage System"
            - :zap: **[RUSH]** **Storage Scanner + Modular Storage + Tablet** = mini AE2 pour commencer
            - Le Storage Scanner détecte automatiquement les changements d'inventaire
            - Les **Screens** peuvent afficher le contenu des inventaires

        !!! tip "Builder"
            - **Builder** peut copier/coller des structures et faire office de quarry
            - Utilise des Shape Cards pour définir les zones

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Storage Scanner | :zap: RUSH | Recherche dans tous les inventaires |
        | Modular Storage | - | Stockage extensible |
        | Tablet | - | Accès distant au Storage Scanner |
        | Screen | | Affiche des informations |
        | Builder | - | Copie/colle structures, quarry |
        | Spawner | | Spawn des mobs avec énergie |
        | Environmental Controller | | Applique des effets dans une zone |
        | Powercell | | Transfert d'énergie sans fil |
        | Crafter | | Autocrafting simple |

    **Modules:** RFTools Base | RFTools Builder | RFTools Storage | RFTools Utility | RFTools Control | RFTools Dimensions

??? note "Flux Networks"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/flux-networks)

    !!! success "Quick Start"
        1. Craft de la **Flux Dust** en jetant de la Redstone dans du feu
        2. Craft un **Flux Controller** comme hub central
        3. Place des **Flux Plugs** sur les sources d'énergie (input)
        4. Place des **Flux Points** sur les machines (output)
        5. Lie tout au même réseau via l'interface

    === "Tips"

        !!! tip "Network Setup"
            - Distribution d'énergie **sans fil et cross-dimension**
            - **Flux Plugs** = input (injectent l'énergie dans le réseau)
            - **Flux Points** = output (extraient l'énergie du réseau)
            - **Priorités** configurables pour distribution intelligente

        !!! tip "Features"
            - **Chunk loading** intégré optionnel
            - Peut charger les items dans l'inventaire du joueur

        !!! success "Réseau Global Sans Fil"
            Tous vos générateurs alimentent un **Flux Point**, tous vos consommateurs reçoivent via **Flux Plugs**. Plus aucun câble, plus de goulot d'étranglement. Le **Flux Controller** gère les priorités d'alimentation par machine.

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Flux Dust | :zap: RUSH | Matériau de base (Redstone + feu) |
        | Flux Plug | - | Input d'énergie vers le réseau |
        | Flux Point | - | Output d'énergie depuis le réseau |
        | Flux Controller | - | Gestion centralisée du réseau |
        | Flux Storage | | Stockage d'énergie dans le réseau |

    **Guides:** [Automatiser la Flux Dust](https://wiki.enigmatica.net/enigmatica6/gameplay/how-to.../flux-networks-automating-flux-dust) | [Guide Reddit](https://www.reddit.com/r/feedthebeast/comments/9oc4j3/flux_networks_guide/)

??? note "ComputerCraft: Tweaked"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cc-tweaked) | [Wiki](https://tweaked.cc/)

    !!! success "Quick Start"
        1. Craft un **Computer** basique
        2. Tape `excavate 16` pour creuser un trou 16x16
        3. Craft un **Mining Turtle** avec pickaxe
        4. Utilise `pastebin get <code> <filename>` pour télécharger des scripts

    === "Tips"

        !!! tip "Turtles"
            - Les **Turtles** peuvent miner, placer des blocs, et craft automatiquement
            - `excavate 16` creuse un trou 16x16 jusqu'à la bedrock
            - `tunnel 100` creuse un tunnel de 100 blocs

        !!! tip "Networking"
            - Les **Wireless Modems** permettent la communication entre ordinateurs
            - **GPS** système pour localiser les turtles automatiquement

        !!! tip "Programming"
            - Les programmes sont en **Lua** - langage simple à apprendre
            - **Pastebin** intégré pour télécharger des programmes de la communauté
            - **N'hésitez pas à utiliser une IA** pour générer du code CC:Tweaked !

        !!! success "Programmes Utiles"
            - **Geo Scanner Pocket** + programme de recherche de blocs = trouver minerais rares (Allthemodium, etc.)
            - **Reactor Controllers** : [ReactorController](https://github.com/Kasra-G/ReactorController) | [Extreme Reactor Control](https://gitlab.com/seekerscomputercraft/extremereactorcontrol/)
            - Chercher sur Pastebin les programmes populaires de la communauté

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Computer | - | Ordinateur de base pour programmer |
        | Mining Turtle | - | Turtle avec pickaxe intégrée |
        | Wireless Modem | | Communication sans fil |
        | Monitor | | Écran externe configurable |
        | Disk Drive | | Partage de programmes |

    **Guides:** [Turtle API](https://www.computercraft.info/wiki/Turtle_(API)) | [Excavate Program](https://www.computercraft.info/wiki/Excavate)

??? note "XNet"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xnet) | [Guide](https://www.mcjty.eu/docs/mods/xnet)

    !!! success "Quick Start"
        1. Craft un **Controller** comme cerveau du réseau
        2. Place des **XNet Cables** pour connecter
        3. Utilise des **Connectors** sur les machines
        4. Configure les channels dans l'interface du Controller

    === "Tips"

        !!! tip "Universal Cables"
            - **Un seul type de câble** pour items, fluides, énergie ET logique
            - Les **Channels** permettent de séparer différents flux
            - **Routing** basé sur des conditions (redstone, quantité, etc.)

        !!! tip "Efficiency"
            - Peut remplacer plusieurs mods de transport
            - Très efficace pour les setups complexes multi-machines

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Controller | - | Cerveau du réseau, configure les transferts |
        | XNet Cable | - | Câble universel |
        | Connector | - | Connecte un bloc au réseau |
        | Advanced Connector | | Version avec plus de channels |
        | Router | | Étend la portée du réseau |
        | Wireless Router | | Connexion sans fil entre réseaux |

    **Addon:** [XNet Gases](https://www.curseforge.com/minecraft/mc-mods/xnet-gases) - Support des gaz Mekanism

    **Guide:** [Guide Officiel](https://www.mcjty.eu/docs/mods/xnet)

??? note "Refined Storage"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/refined-storage) | [Guide Officiel](https://refinedmods.com/refined-storage/getting-started.html)

    !!! success "Quick Start"
        1. Craft un **Controller** et alimente-le en énergie
        2. Craft un **Disk Drive** et des **Storage Disks**
        3. Craft un **Grid** pour accéder au stockage
        4. Utilise **Importers/Exporters** pour l'automatisation

    === "Tips"

        !!! tip "Alternative à AE2"
            - Plus simple que AE2 (pas de channels)
            - Système de stockage digital complet
            - Compatible avec beaucoup de mods

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Controller | - | Cerveau du réseau |
        | Disk Drive | - | Contient les disques |
        | Grid | - | Interface utilisateur |
        | Crafter | | Autocrafting |
        | Importer/Exporter | | Automatisation |

    **Addons:** [Cable Tiers](https://www.curseforge.com/minecraft/mc-mods/cable-tiers) | [Extra Storage](https://www.curseforge.com/minecraft/mc-mods/extrastorage) | [Extra Disks](https://www.curseforge.com/minecraft/mc-mods/extra-disks) | [RS Requestify](https://www.curseforge.com/minecraft/mc-mods/rs-requestify)

??? note "NuclearCraft"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/nuclearcraft-mod)

    === "Tips"

        !!! warning "Configuration"
            - Vérifier si la **config a été modifiée** sur le modpack
            - Utiliser le **Discord du mod** pour aide
            - Les générateurs en ligne aident à optimiser les réacteurs

    === "Guides & Outils"

        - [LEU-235 Reactor Planner](https://leu-235.com/) - Générateur de réacteurs en ligne
        - [NC Reactor Planner GitHub](https://github.com/hellrage/NC-Reactor-Planner)
        - [Guide FTB](https://ftb.fandom.com/wiki/Getting_Started_(NuclearCraft))
        - [Tutoriel Build Réacteur (Vidéo)](https://www.youtube.com/watch?v=xMahsOUl24c)

??? note "Extreme Reactors"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/extreme-reactors)

    === "Tips"

        !!! tip "Réacteurs Efficaces"
            - Utiliser des **moderators** pour améliorer l'efficacité
            - Le design du réacteur impacte beaucoup les performances
            - Les turbines sont plus efficaces que les réacteurs directs

    === "Guides"

        - [Guide ATM - Moderators](https://allthemods.github.io/alltheguides/atm9/extremereactors/#moderators)
        - [Meilleur Réacteur Reddit](https://www.reddit.com/r/allthemods/comments/1cd85tw/atm9_in_my_opinion_the_best_extreme_reactors/)

??? note "Deep Resonance"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/deep-resonance) | [Guide Wiki](https://github.com/McJtyMods/DeepResonance/wiki)

    === "Tips"

        !!! tip "Génération d'Énergie"
            - Système de cristaux pour génération d'énergie
            - Les cristaux peuvent être purifiés pour plus d'efficacité
            - Alternative intéressante aux autres systèmes d'énergie

??? note "FTB Industrial Contraptions"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ftb-industrial-contraptions-forge)

    === "Tips"

        !!! tip "Équipement"
            - **Armure électrique** modulaire
            - Machines industrielles variées

??? note "GregTech CE Unofficial"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/gregtech-ce-unofficial)

    !!! warning "Mod Expert"
        GregTech est un mod **très complexe** et **long** à progresser. Réservé aux joueurs expérimentés!

    === "Guides"

        - [Automatiser Assembly Line avec OpenComputers](https://github.com/botn365/assembling-line-automation-OC/tree/parrallel_processing)
        - [Automatisation Assembly Line (Vidéo)](https://www.youtube.com/watch?v=N_0ay7YLcdI)
        - [Optimiser les Crafts (Vidéo)](https://www.youtube.com/watch?v=EcjxtFIuZlU)

??? note "Super Factory Manager (SFM)"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/super-factory-manager)

    === "Tips"

        !!! tip "Automatisation Avancée"
            - Système de programmation visuel pour automation complexe
            - Peut gérer des setups multi-machines
            - Alternative puissante à Integrated Dynamics

    === "Scripts & Exemples"

        - [Automated Bees + HNN + Mekanism Mob Farm + Seed Farm](https://www.reddit.com/r/allthemods/comments/1llv4nt/automated_bees_hnn_mekanism_mob_farm_seed_farm/) - Script complet d'automation

---

## Voir aussi

- [:octicons-arrow-right-24: Automation](../astuces/automation.md) - Techniques avancées d'automatisation
- [:octicons-arrow-right-24: Énergie](../astuces/energie.md) - Production et distribution d'énergie
- [:octicons-arrow-right-24: Stockage](../stockage/index.md) - Systèmes de stockage centralisé

---

??? note "Integrated Dynamics"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/integrated-dynamics) | [Wiki](https://integrateddynamics.rubensworks.net/)

    !!! success "Quick Start"
        1. Craft un **Logic Cable** pour le réseau
        2. Craft un **Logic Programmer** pour créer des variables
        3. Place des **Part Readers** pour lire les données des blocs
        4. Combine avec **Integrated Tunnels** pour le transport

    === "Tips"

        !!! tip "Logic System"
            - Système de **logique programmable** très puissant
            - Les **Variables** stockent des valeurs (items, nombres, booleans)
            - Peut lire inventaires, tanks, energy storage, et plus
            - Bien plus puissant que la redstone pour des **automatisations complexes**

        !!! success "Filtres Avancés"
            Apprendre à utiliser les filtres sur **tags, regex et NBT** avec Integrated Dynamics est extrêmement puissant !

            - Lire l'état de n'importe quel bloc (niveau de fluide, inventaire, énergie)
            - Déclencher des actions conditionnelles complexes
            - Parfait pour automatiser ce que les autres mods ne peuvent pas faire

        !!! tip "Addons"
            - **Integrated Tunnels** addon pour transport automatique
            - **Integrated Terminals** addon pour interface type AE2
            - Utiliser pour automatiser ce que les autres mods ne peuvent pas faire

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Logic Cable | - | Connecte le réseau |
        | Logic Programmer | - | Crée des variables et conditions |
        | Variable Store | | Stocke les variables |
        | Part Reader | | Lit les données des blocs adjacents |
        | Part Writer | | Écrit des données vers les blocs |
        | Squeezer | | Processing unique |

    **Guides:** [Transfert de fluide infini](https://allthemods.github.io/alltheguides/mods/integrateddynamics/infinitefluidtransfer/) | [Getting Started](https://integrateddynamics.rubensworks.net/book/)

??? note "Draconic Evolution"

    [CurseForge](https://www.curseforge.com/minecraft/mc-mods/draconic-evolution) | [Wiki](https://draconic-evolution.fandom.com/)

    !!! success "Quick Start"
        1. Tue l'Ender Dragon pour obtenir un **Dragon Heart**
        2. Craft un **Fusion Crafting Core** pour les recettes avancées
        3. Crée des outils et armures **Wyvern** comme première tier
        4. Upgrade vers **Draconic** puis **Chaotic** pour end-game

    === "Tips"

        !!! danger "Draconic Reactor"
            - Le **Draconic Reactor** génère énormément d'énergie mais peut exploser!
            - **Surveiller le reactor** : si le field strength tombe à 0 = explosion massive
            - Commence avec les Energy Cores pour le stockage avant le reactor

        !!! tip "Equipment"
            - Les outils/armures ont des **modules upgradables**
            - **Staff of Power** = outil ultime (mine, combat, vol)
            - **Celestial Manipulator** pour changer météo et time

        !!! example "Automation Fusion Altar"
            Pour automatiser le **Draconic Fusion Crafting**, chercher "Draconic evolution fusion automation" sur Discord/Reddit - des solutions existent déjà !

    === "Objets Importants"

        | Objet | Priorité | Description |
        |-------|:--------:|-------------|
        | Fusion Crafting Core | - | Crafting avancé |
        | Wyvern Armor/Tools | - | Tier 1 end-game |
        | Draconic Armor/Tools | - | Tier 2 end-game |
        | Chaotic Armor/Tools | | Tier 3 ultime |
        | Staff of Power | - | Multi-tool ultime |
        | Energy Core | - | Stockage massif (tiers 1-8) |
        | Draconic Reactor | | Génération massive mais risquée |
        | Dislocator | | Téléportation sauvegardée |
        | Mob Grinder | | Tue et collecte automatiquement |

    **Guides:** [Reactor Guide](https://ftb.fandom.com/wiki/Draconic_Reactor) | [Safe Reactor Setup](https://www.youtube.com/watch?v=_9bvtB3VBQU)
