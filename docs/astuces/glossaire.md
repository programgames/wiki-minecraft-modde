# Glossaire du Minecraft moddé

Ce glossaire regroupe les termes techniques et abréviations couramment utilisés dans l'univers du Minecraft moddé. Référence indispensable pour comprendre les guides et discussions de la communauté.

---

## Tableau de référence rapide

| Terme | Signification | Mod / Contexte |
|-------|---------------|----------------|
| RF | Redstone Flux | Thermal Series, standard énergétique |
| FE | Forge Energy | API Forge universelle |
| EU | Energy Units | IndustrialCraft 2 |
| J | Joules | Mekanism |
| ME | Matter Energy | Applied Energistics 2 |
| RS | Refined Storage | Refined Storage |
| DPS | Damage Per Second | Combat général |
| JEI | Just Enough Items | Mod de recettes |
| QOL | Quality of Life | Améliorations de confort |

---

=== "Énergie"

    ## Termes liés à l'énergie

    Les différents systèmes énergétiques peuvent sembler complexes, mais la plupart sont interconvertibles.

    RF (Redstone Flux)
    :   Unité d'énergie standard introduite par Thermal Expansion. Devenue le format universel adopté par la majorité des mods techniques. 1 RF = 1 FE.

    FE (Forge Energy)
    :   API énergétique native de Forge, compatible avec RF. Permet l'interopérabilité entre mods sans dépendances supplémentaires.

    EU (Energy Units)
    :   Système énergétique d'IndustrialCraft 2. Fonctionne avec des voltages (LV, MV, HV, EV) et peut exploser les machines si le voltage est trop élevé.

    J (Joules)
    :   Unité de Mekanism. Conversion : 1 J = 2.5 RF. Mekanism utilise aussi les câbles Universal pour la conversion automatique.

    Mana
    :   Énergie magique de Botania. Stockée dans des Mana Pools, transportée par Mana Spreaders. Ne se convertit pas en RF.

    Source
    :   Énergie magique d'Ars Nouveau. Générée par des Source Jars près de blocs spécifiques (fleurs, arbres). Utilisée pour les sorts et enchantements.

    LP (Life Points)
    :   Points de vie sacrifiés dans Blood Magic. Stockés dans un Soul Network personnel ou des Blood Altars.

    Aura
    :   Énergie ambiante de Nature's Aura. Présente naturellement dans le monde, peut être drainée ou régénérée selon les actions du joueur.

    Vis
    :   Énergie de Thaumcraft. Présente dans l'atmosphère sous forme d'aspects élémentaires.

    Starlight
    :   Énergie d'Astral Sorcery. Collectée la nuit via des structures de marbre, plus puissante selon les constellations.

    ### Tableau de conversion énergétique

    | Unité | Équivalent RF | Notes |
    |-------|---------------|-------|
    | 1 FE | 1 RF | Identique |
    | 1 EU | 4 RF | Variable selon les packs |
    | 1 J | 2.5 RF | Mekanism |
    | 1 IF | 1 RF | Industrial Foregoing |

=== "Stockage"

    ## Termes liés au stockage

    Les systèmes de stockage numérique révolutionnent la gestion des inventaires.

    ME (Matter Energy)
    :   Système de stockage d'Applied Energistics 2. Convertit les items en énergie pour les stocker sur des disques. Nécessite un réseau alimenté en énergie.

    RS (Refined Storage)
    :   Alternative plus simple à AE2. Pas de système de channels, configuration plus intuitive mais moins de fonctionnalités avancées.

    Channel
    :   Limite de connexions par câble dans AE2. Un câble normal supporte 8 channels, un câble dense en supporte 32. Chaque appareil utilise 1 channel.

    Crafting CPU
    :   Unité de calcul pour l'auto-crafting dans AE2/RS. Plus elle est grande, plus elle peut gérer de crafts complexes simultanément.

    Pattern
    :   Recette encodée pour l'auto-crafting. Peut être "processing" (machines externes) ou "crafting" (table de craft).

    Storage Cell
    :   Disque de stockage pour ME/RS. Capacité variable (1k, 4k, 16k, 64k, 256k). Les cells avec moins de types d'items stockent plus d'items au total.

    Disk Drive
    :   Bloc contenant les Storage Cells. Point d'accès au stockage du réseau.

    Controller
    :   Cerveau du réseau ME/RS. Fournit les channels (AE2) et gère les connexions. Un seul par réseau.

    Interface
    :   Point d'interaction entre le réseau ME et les machines externes. Peut fournir des items ou accepter des outputs.

    Import/Export Bus
    :   Bus d'importation/exportation. Déplace les items entre le réseau et des conteneurs externes.

    ### Comparaison AE2 vs Refined Storage

    | Fonctionnalité | AE2 | Refined Storage |
    |----------------|-----|-----------------|
    | Channels | Oui (limite 8/32) | Non |
    | Complexité | Élevée | Modérée |
    | Auto-crafting | Avancé | Simple |
    | Énergie requise | Oui | Oui |
    | Wireless | Oui | Oui |

=== "Automation"

    ## Termes liés à l'automatisation

    L'automatisation est le cœur du gameplay technique.

    Servo
    :   Composant de Thermal Series attaché aux conduits. Contrôle l'extraction des items/fluides avec filtrage et redstone.

    Filter
    :   Système de tri des items. Peut être whitelist (seuls les items listés passent) ou blacklist (tous sauf les items listés).

    Conduit
    :   Tuyau multifonction (Ender IO, Thermal). Peut transporter items, fluides, énergie et redstone dans un seul bloc.

    Augment
    :   Amélioration installable dans les machines Thermal. Modifie les performances : vitesse, efficacité, capacité.

    Upgrade
    :   Amélioration générique pour machines. Terme utilisé par de nombreux mods (Mekanism, Industrial Foregoing, etc.).

    Hopper
    :   Entonnoir vanilla. Base de l'automatisation simple. Les mods ajoutent souvent des versions améliorées.

    Pipe
    :   Tuyau de transport. BuildCraft a popularisé le concept, repris par Mekanism, Pipez, etc.

    Duct
    :   Terme Thermal pour les conduits spécialisés (Itemduct, Fluiduct, Fluxduct).

    Router
    :   Bloc intelligent de routage d'items. Modular Routers permet des configurations complexes dans un seul bloc.

    Retriever
    :   Composant qui "tire" les items depuis des inventaires distants vers un point central.

    ### Types de conduits Thermal

    | Type | Transporte | Servo requis |
    |------|------------|--------------|
    | Fluxduct | Énergie (RF) | Non |
    | Itemduct | Items | Oui (extraction) |
    | Fluiduct | Fluides | Oui (extraction) |
    | Signalum Fluxduct | RF + Redstone | Non |

=== "Combat"

    ## Termes liés au combat

    Le combat moddé introduit de nouvelles mécaniques et statistiques.

    DPS (Damage Per Second)
    :   Dégâts infligés par seconde. Calculé en combinant les dégâts de base, la vitesse d'attaque et les bonus.

    Armor Toughness
    :   Résistance aux dégâts élevés. Réduit la pénétration des attaques puissantes. L'armure vanilla en diamant a 2 de toughness.

    Enchanting Levels
    :   Niveaux d'enchantement. Apotheosis permet des niveaux bien supérieurs au vanilla (jusqu'à 100+).

    Modifier (Tinker's Construct)
    :   Amélioration appliquée aux outils Tinker's. Chaque outil a un nombre limité de slots de modifiers.

    Trait (Silent Gear)
    :   Caractéristique passive des matériaux. Chaque matériau apporte des traits uniques aux outils/armures.

    Affix (Apotheosis)
    :   Bonus aléatoire sur les items de loot. Comparable aux affixes de Diablo. Rareté : Common → Mythic.

    Curio
    :   Accessoire équipable dans des slots dédiés (Curios API). Anneaux, amulettes, ceintures, etc.

    Bauble
    :   Ancien terme (1.12.2) pour les accessoires équipables. Remplacé par Curios en 1.14+.

    Scaling
    :   Mise à l'échelle de la difficulté. Certains mods augmentent la force des mobs avec le temps ou la distance.

    Infusion
    :   Processus d'amélioration d'équipement. Utilisé par Ars Nouveau, Botania, et d'autres mods magiques.

    ### Slots Curios courants

    | Slot | Type d'accessoire | Exemples |
    |------|-------------------|----------|
    | Ring | Anneaux | Ring of Magnetization, Angel Ring |
    | Necklace | Colliers | Charm of Life |
    | Belt | Ceintures | Knapsack |
    | Head | Couvre-chefs | Goggles of Revealing |
    | Back | Dos | Elytra, Capes |

=== "Farming"

    ## Termes liés au farming

    L'agriculture moddée va bien au-delà du blé et des carottes.

    Inferium
    :   Essence de base de Mystical Agriculture. Se combine en tiers supérieurs : Prudentium → Tertium → Imperium → Supremium.

    Growth Accelerator
    :   Bloc de Mystical Agriculture placé sous le farmland. Accélère la croissance des plantes. Stack jusqu'à 64 sous un bloc.

    Bee Gene
    :   Caractéristique génétique des abeilles Productive Bees. Productivity, Endurance, Temper, Behavior, Weather Tolerance.

    Centrifuge
    :   Machine traitant les rayons de miel pour extraire les ressources. Version Powered = automatisable.

    Comb
    :   Rayon produit par les abeilles. Chaque type d'abeille produit des combs spécifiques contenant différentes ressources.

    Breeding Chamber
    :   Bloc pour croiser les abeilles et améliorer leurs gènes. Le parent de gauche transmet ses gènes en priorité.

    Soulium Dagger
    :   Dague de Mystical Agriculture. Tue les mobs avec une chance de drop des Mob Chunks pour crafter les seeds.

    Farmland Essence
    :   Type de farmland de Mystical Agriculture. Supremium Farmland = +50% de drops.

    Lily Pad of Fertility
    :   Objet de Cyclic. Accélère la croissance des plantes dans un rayon autour.

    Phytogenic Insolator
    :   Machine Thermal cultivant les plantes automatiquement avec de l'énergie et du Phyto-Gro.

    ### Tiers Mystical Agriculture

    | Tier | Essence | Couleur | Crafts débloqués |
    |------|---------|---------|------------------|
    | 1 | Inferium | Vert clair | Seeds basiques |
    | 2 | Prudentium | Vert | Seeds intermédiaires |
    | 3 | Tertium | Orange | Seeds avancées |
    | 4 | Imperium | Cyan | Seeds rares |
    | 5 | Supremium | Rouge | Seeds end-game |
    | 6 | Insanium | Violet | Seeds Insanium (addon) |

=== "Magie"

    ## Termes magiques

    Les systèmes magiques ont leur propre vocabulaire.

    Source (Ars Nouveau)
    :   Énergie magique d'Ars Nouveau. Générée passivement près de certains blocs naturels.

    Source Jar
    :   Conteneur de Source. Se remplit automatiquement près de sources naturelles (fleurs, arbres).

    Glyph
    :   Composant de sort Ars Nouveau. Combinés pour créer des effets personnalisés.

    Spell Book
    :   Livre contenant les sorts créés. Permet de lancer des combinaisons de glyphes.

    Starbuncle
    :   Familier Ars Nouveau collecteur d'items. Très utile pour l'automation early game.

    Drygmy
    :   Familier Ars Nouveau générant des drops de mobs passifs proches. Fonctionne sur les boss!

    Mana Pool
    :   Stockage de mana Botania. Base de tout système Botania.

    Mana Spreader
    :   Transporteur de mana Botania. Tire des bursts de mana vers les pools ou machines.

    Spark
    :   Entité Botania pour transfert de mana entre pools. Plus efficace que les spreaders pour grandes quantités.

    Generating Flora
    :   Fleurs Botania produisant du mana (Endoflame, Gourmaryllis, etc.).

    Functional Flora
    :   Fleurs Botania consommant du mana pour un effet (Hopperhock, Bellethorne, etc.).

    Terrasteel
    :   Matériau end-game Botania. Crafté sur une Terrestrial Agglomeration Plate avec beaucoup de mana.

    Blood Altar
    :   Structure centrale de Blood Magic. Upgrade en tiers pour débloquer plus de crafts.

    LP (Life Points)
    :   Énergie Blood Magic obtenue en sacrifiant sa vie. Stockée dans le Soul Network.

    Living Armor
    :   Armure Blood Magic évoluant avec l'usage. Gagne des upgrades passifs.

    Demon Will
    :   Ressource avancée Blood Magic obtenue des démons. Quatre types : Default, Corrosive, Vengeful, Steadfast.

    ### Comparaison systèmes magiques

    | Mod | Énergie | Stockage | Transport |
    |-----|---------|----------|-----------|
    | Botania | Mana | Mana Pool | Spreader/Spark |
    | Ars Nouveau | Source | Source Jar | Relay |
    | Blood Magic | LP | Soul Network | Rituel |
    | Astral Sorcery | Starlight | Collector | Liens |

=== "Général"

    ## Termes généraux

    Vocabulaire de base pour tout joueur de Minecraft moddé.

    Modpack
    :   Collection de mods assemblés et configurés pour fonctionner ensemble. Distribué via CurseForge, Modrinth, ou ATLauncher.

    Datapack
    :   Pack de données vanilla modifiant recettes, loot tables, et structures. Ne nécessite pas Forge/Fabric.

    Config
    :   Fichiers de configuration des mods. Permettent d'ajuster le gameplay sans modifier le code. Situés dans le dossier `/config/`.

    JEI (Just Enough Items)
    :   Mod indispensable affichant toutes les recettes du jeu. Raccourcis : R (recette), U (utilisations).

    REI (Roughly Enough Items)
    :   Alternative à JEI, souvent utilisée sur Fabric. Interface similaire avec quelques différences.

    EMI (Emi)
    :   Successeur moderne combinant les forces de JEI et REI. Support Forge et Fabric.

    Patchouli
    :   Système de guides in-game. Les mods créent des livres interactifs avec recettes et tutoriels.

    Curios
    :   API ajoutant des slots d'équipement supplémentaires. Standard pour les accessoires depuis 1.14.

    Baubles
    :   Prédécesseur de Curios pour Minecraft 1.12.2 et versions antérieures.

    Quest
    :   Système de quêtes (FTB Quests, Better Questing). Guide le joueur à travers le modpack avec des récompenses.

    Multiblock
    :   Structure composée de plusieurs blocs formant une machine unique. Ex: Immersive Engineering, Create.

    Tick
    :   Unité de temps Minecraft. 20 ticks = 1 seconde. Les machines traitent souvent "X items par tick".

    TPS (Ticks Per Second)
    :   Performance du serveur. 20 TPS = performance optimale. En dessous, le jeu ralentit.

    ### Mods utilitaires essentiels

    | Mod | Fonction | Versions |
    |-----|----------|----------|
    | JEI | Recettes | Forge 1.12+ |
    | REI | Recettes | Fabric/Forge |
    | EMI | Recettes | Fabric/Forge 1.18+ |
    | Jade/WAILA | Info blocs | Toutes |
    | Patchouli | Guides | Forge/Fabric |
    | Curios | Accessoires | Forge 1.14+ |

---

## Abréviations courantes

| Abréviation | Signification |
|-------------|---------------|
| AE2 | Applied Energistics 2 |
| IE | Immersive Engineering |
| TE | Thermal Expansion |
| TF | Thermal Foundation |
| TD | Thermal Dynamics |
| IF | Industrial Foregoing |
| IC2 | IndustrialCraft 2 |
| TC | Tinker's Construct |
| SG | Silent Gear |
| EIO | Ender IO |
| PNC | PneumaticCraft |
| CC | ComputerCraft / CC: Tweaked |
| OC | OpenComputers |
| RS | Refined Storage |
| MA | Mystical Agriculture |
| PB | Productive Bees |
| FD | Farmer's Delight |
| AN | Ars Nouveau |
| BM | Blood Magic |
| DE | Draconic Evolution |
| ER | Extreme Reactors |
| FN | Flux Networks |
| MR | Modular Routers |
| HNN | Hostile Neural Networks |
| MGU | Mob Grinding Utils |
| QOL | Quality of Life |
| OP | Overpowered |
| RNG | Random Number Generator |
| AOE | Area of Effect |
| NBT | Named Binary Tag (données d'items) |
| GUI | Graphical User Interface |
| API | Application Programming Interface |
| FPS | Frames Per Second |
| RTD | Right To Dial (Stargate) |
| SBU | Speed Bonus Unit |
| GC | Growth Crystal / Growth Accelerator |

---

## Termes de Modpacks

| Terme | Description |
|-------|-------------|
| Expert Mode | Mode de jeu avec recettes modifiées, plus difficiles |
| Gated Progression | Progression verrouillée par étapes (doit compléter X avant Y) |
| Kitchen Sink | Modpack sans thème précis, beaucoup de mods sans intégration |
| Skyblock | Type de map commençant sur une île flottante |
| Hardcore Questing | Système de quêtes avec vies limitées |
| Tech Tree | Arbre de technologies à débloquer progressivement |
| Worldgen | Génération du monde (biomes, structures, minerais) |
| Retrogen | Génération de nouveaux éléments dans des chunks existants |
| Ore Dictionary | Système unifiant les minerais entre mods (deprecated en 1.13+) |
| Tags | Système remplaçant Ore Dictionary depuis 1.13 |
| Loot Table | Tables définissant les drops des mobs/coffres |
| Recipe Viewer | Mod affichant les recettes (JEI, REI, EMI) |

## Termes Techniques Avancés

| Terme | Description |
|-------|-------------|
| Chunk Loading | Garder des chunks actifs même sans joueur présent |
| Lazy Chunk | Chunk chargé mais avec activité réduite |
| Tick Rate | Fréquence de mise à jour du jeu (20/sec normal) |
| Entity Culling | Optimisation n'affichant pas les entités non visibles |
| Mipmap | Niveaux de détail des textures à distance |
| VBO | Vertex Buffer Objects (rendu optimisé) |
| Shader | Programme graphique modifiant le rendu |
| Occlusion Culling | Ne pas rendre ce qui est caché |
| Garbage Collection | Nettoyage mémoire Java (source de lag spikes) |
| Memory Leak | Fuite mémoire causant des crashes |

---

## Voir aussi

- [:octicons-arrow-right-24: Mods QOL](../qol/index.md) - Mods améliorant le confort de jeu
- [:octicons-arrow-right-24: Énergie](../energie/index.md) - Guide complet sur les systèmes énergétiques
- [:octicons-arrow-right-24: Stockage](../stockage/index.md) - Systèmes de stockage détaillés
- [:octicons-arrow-right-24: Astuces Avancées](advanced-tips.md) - Techniques de pro
- [:octicons-arrow-right-24: Synergies](synergies.md) - Combinaisons de mods
