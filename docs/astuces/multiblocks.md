# Guide des Multiblocks

Les multiblocks sont des structures composées de plusieurs blocs qui fonctionnent ensemble. Ce guide liste les plus importants par mod.

## Multiblocks Essentiels (Early Game)

### Tinker's Construct - Smeltery
!!! success "Priorité RUSH"
    **Fonction** : Fondre les métaux, doubler les minerais, créer des alliages

    **Taille minimum** : 3x3x3 (intérieur 1x1x1)

    ```
    Couche 1 (Sol):        Couche 2-3 (Murs):     Couche 4 (Optionnel):
    [S][S][S]              [S][ ][S]              [S][S][S]
    [S][C][S]              [ ]   [ ]              [S][ ][S]
    [S][S][S]              [S][ ][S]              [S][S][S]

    S = Seared Bricks
    C = Smeltery Controller (n'importe quel mur)
    ```

    **Composants requis** :
    | Bloc | Quantité min | Fonction |
    |------|--------------|----------|
    | Seared Bricks | ~25 | Structure |
    | Smeltery Controller | 1 | Interface |
    | Seared Tank | 1+ | Stockage fuel |
    | Seared Drain | 1+ | Sortie métal |
    | Seared Faucet | 1+ | Verser métal |
    | Casting Table/Basin | 1+ | Moules |

### Immersive Engineering - Coke Oven
!!! tip "Premier Multiblock IE"
    **Fonction** : Créer du Cite (charbon amélioré) et Creosote Oil

    **Taille** : 3x3x3 solide

    ```
    27x Coke Bricks en cube 3x3x3
    Former avec Engineer's Hammer sur un coin
    ```

    **Output** : 1 Coal → 1 Coke + 500mb Creosote

### Immersive Engineering - Blast Furnace
!!! note "Acier (Steel)"
    **Fonction** : Créer de l'acier (Iron + Coke)

    **Taille** : 3x3x3 solide

    ```
    27x Blast Bricks en cube 3x3x3
    Former avec Engineer's Hammer
    Ajouter Blast Furnace Preheater pour x2 vitesse
    ```

### Blood Magic - Blood Altar
!!! warning "Tiers progressifs"
    **Fonction** : Crafting avec Life Points (LP)

    | Tier | Structure | LP Max |
    |------|-----------|--------|
    | 1 | Altar seul | 10,000 |
    | 2 | +8 Blood Runes | 25,000 |
    | 3 | +Pilliers + Runes | 100,000 |
    | 4 | +Grandes pilliers | 250,000 |
    | 5 | +Structure massive | 1,000,000 |

    [Schémas détaillés sur le Wiki](https://ftb.fandom.com/wiki/Blood_Altar)

## Multiblocks Mid Game

### Mekanism - Thermal Evaporation Plant
!!! example "Production de Brine/Lithium"
    **Fonction** : Évaporer l'eau en Brine, puis en Lithium

    **Taille** : 4x4 base, jusqu'à 18 blocs de haut

    ```
    Base 4x4:
    [C][C][C][C]
    [C][V][V][C]
    [C][V][V][C]
    [C][C][C][C]

    C = Thermal Evaporation Controller/Block/Valve
    V = Thermal Evaporation Valve (pour I/O)
    ```

    **Tips** :
    - Plus c'est haut, plus c'est rapide
    - Placer dans un **désert** ou **Nether** pour bonus chaleur
    - Ajouter **Solar Neutron Activator** au-dessus

### Mekanism - Industrial Turbine
!!! success "Énergie massive"
    **Fonction** : Générer de l'énergie avec Steam

    **Composants** :
    | Bloc | Fonction |
    |------|----------|
    | Turbine Casing | Structure extérieure |
    | Turbine Vent | Entrée steam (haut) |
    | Turbine Valve | I/O fluides |
    | Turbine Rotor | Centre (empilé) |
    | Turbine Blade | Sur le rotor |
    | Electromagnetic Coil | Génère l'énergie |
    | Rotational Complex | Connecte rotor aux coils |
    | Saturating Condenser | Récupère l'eau |

### PneumaticCraft - Pressure Chamber
!!! tip "Crafting sous pression"
    **Fonction** : Crafts spéciaux + enchantements

    **Taille minimum** : 3x3x3

    ```
    Murs: Pressure Chamber Wall
    Verre: Pressure Chamber Glass (optionnel, pour voir)
    Valve: Pressure Chamber Valve (entrée air)
    Interface: Pressure Chamber Interface (I/O items)
    ```

    **Pression requise** : > 2.0 bar minimum

### Immersive Engineering - Excavator
!!! danger "Mining Automatique"
    **Fonction** : Mine des veines de minerais infinies

    **Taille** : Grande structure

    **Prérequis** :
    1. Trouver une **Mineral Vein** avec le Core Sample Drill
    2. Construire l'Excavator au-dessus
    3. Alimenter en énergie (beaucoup!)

    **Output** : Minerais infinis de la veine

## Multiblocks Late Game

### Mekanism - Fission Reactor
!!! danger "Énergie Nucléaire"
    **Fonction** : Générer de la chaleur pour la Turbine

    **ATTENTION** : Peut exploser si mal géré!

    **Composants essentiels** :
    - Fission Reactor Casing
    - Fission Reactor Port
    - Fission Fuel Assembly
    - Control Rod Assembly
    - Reactor Logic Adapter

    **Tips Sécurité** :
    - Toujours avoir un **Boiler** pour évacuer la chaleur
    - Utiliser **Reactor Logic Adapter** pour auto-SCRAM
    - Ne jamais laisser sans surveillance sans automation

### Mekanism - Fusion Reactor
!!! success "Énergie Quasi-Infinie"
    **Fonction** : Fusion D-T pour énergie massive

    **Prérequis** :
    1. Laser Amplifier pour injection initiale
    2. Hohlraum avec D-T Fuel
    3. Structure du réacteur complète

    **Output** : 100M+ RF/t possible

### Draconic Evolution - Energy Core
!!! example "Stockage Massif"
    **Fonction** : Stocker des quantités absurdes d'énergie

    | Tier | Stockage |
    |------|----------|
    | 1 | 45.5M RF |
    | 2 | 273M RF |
    | 3 | 1.64B RF |
    | 4 | 9.88B RF |
    | 5 | 59.3B RF |
    | 6 | 356B RF |
    | 7 | 2.14T RF |
    | 8 | ∞ (Creative) |

### Extreme Reactors - Big Reactor
!!! tip "Configurable"
    **Fonction** : Génération d'énergie configurable

    **Structure** :
    - Reactor Casing (murs)
    - Reactor Controller (1)
    - Reactor Access Port (I/O fuel)
    - Reactor Power Tap (sortie énergie)
    - Reactor Fuel Rods (intérieur)
    - Reactor Coolant Ports (optionnel)

    **Moderators** (intérieur pour efficacité) :
    | Bloc | Efficacité |
    |------|------------|
    | Cryotheum | Excellent |
    | Gelid Cryotheum | Meilleur |
    | Diamond Block | Très bon |
    | Enderium Block | Excellent |

## Outils de Planification

### Liens Utiles
| Mod | Outil | Lien |
|-----|-------|------|
| Extreme Reactors | Reactor Planner | [br.sidoh.org](https://br.sidoh.org/) |
| Mekanism | Fission Calculator | [Wiki Mekanism](https://wiki.aidancbrady.com/) |
| NuclearCraft | Reactor Planner | [LEU-235](https://leu-235.com/) |
| Draconic Evolution | Energy Core Builder | In-game Fusion Crafting |

### Tips Généraux

!!! success "Conseils Multiblocks"
    1. **Toujours vérifier la formation** - Le controller indique si c'est valide
    2. **Utiliser le guide in-game** - Ponder (Create), Manual (IE), etc.
    3. **Prévoir l'espace** - Les multiblocks peuvent être TRÈS grands
    4. **Chunk loader** - Un multiblock qui se décharge peut causer des problèmes
    5. **Backup avant construction** - Surtout pour les réacteurs

---

## Voir aussi

- [:octicons-arrow-right-24: Technologie](../technologie/index.md) - Mods tech avec multiblocks
- [:octicons-arrow-right-24: Énergie](../energie/index.md) - Génération d'énergie
- [:octicons-arrow-right-24: Mob Farm](../mob-farm/index.md) - Structures de farming
