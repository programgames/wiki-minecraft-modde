# Setups Détaillés

Configurations optimales pour les systèmes les plus importants.

## Setup AE2 Optimal

### Architecture Recommandée

```
                    ┌─────────────────┐
                    │  ME Controller  │
                    └────────┬────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
   ┌────┴────┐         ┌────┴────┐         ┌────┴────┐
   │ Drives  │         │ Crafting │        │ Machines │
   │ (Storage)│        │   CPUs   │        │ (Export) │
   └─────────┘         └─────────┘         └─────────┘
```

### Pattern Provider Layout

!!! success "Configuration Optimale"
    ```
    [MA][MA][MA]     MA = Molecular Assembler
    [MA][PP][MA]     PP = Pattern Provider
    [MA][MA][MA]
    ```

    - **6 Molecular Assemblers** autour de chaque Pattern Provider
    - Ajouter **Acceleration Cards** dans les Assemblers
    - Utiliser **Dense Smart Cables** pour les channels

### Channels Management

| Composant | Channels Utilisés |
|-----------|-------------------|
| ME Drive | 1 |
| Terminal | 1 |
| Pattern Provider | 1 |
| Molecular Assembler | 0 (transfère 8) |
| Import/Export Bus | 1 |

!!! tip "Économiser les Channels"
    - **Subnetworks** pour les machines gourmandes
    - **Storage Bus** sur un chest = 1 channel pour tout le chest
    - **P2P Tunnels** : 32 channels dans 1 channel

### Setup Crafting CPU

```
Pour gros crafts :
┌───┬───┬───┐
│64k│64k│64k│   64k = Crafting Storage
├───┼───┼───┤
│64k│ U │64k│   U = Crafting Unit
├───┼───┼───┤
│64k│Co │64k│   Co = Co-Processing Unit (parallélisme)
└───┴───┴───┘
```

### Intégration Machines Externes

```
[Pattern Provider] → [ME Interface] → [Machine] → [ME Interface] → [Retour au réseau]

Configuration Pattern Provider :
- Blocking Mode : ON (si machine = 1 craft à la fois)
- Blocking Mode : OFF (si machine peut queue)
```

---

## Setup Mob Farm Universel

### Mob Farm Simple (Early Game)

!!! tip "Matériaux Basiques"

```
Niveau +24 (spawning):
┌─────────────────────────┐
│    Eau → Centre         │
│  ┌───────────────────┐  │
│  │   Platform 9x9    │  │
│  │     (sombre)      │  │
│  └───────────────────┘  │
└─────────────────────────┘
         ↓ (chute)
┌─────────────────────────┐
│  Eau pousse vers kill  │
│         zone           │
└─────────────────────────┘
         ↓
┌─────────────────────────┐
│   Spikes / Magma        │
│   + Hopper → Chest      │
└─────────────────────────┘
```

**Composants** :
- Plateforme de spawn 9x9 minimum
- Trapdoors pour que les mobs tombent
- 24+ blocs de chute pour les tuer
- Hopper sous la kill zone

### Mob Farm Avancée (Mid-Late Game)

!!! danger "High Efficiency"

```
┌─────────────────────────────────────┐
│         Cursed Earth / Fan          │
│    (ou Mob Duplicator en boucle)    │
└──────────────┬──────────────────────┘
               ↓
┌──────────────┴──────────────────────┐
│         Conveyor Belts              │
│    (Industrial Foregoing / Create)  │
└──────────────┬──────────────────────┘
               ↓
┌──────────────┴──────────────────────┐
│          MOB MASHER                 │
│   + Looting Enchant                 │
│   + Beheading Enchant               │
└──────────────┬──────────────────────┘
               ↓
┌──────────────┴──────────────────────┐
│     Absorption Hopper               │
│   (collecte items + XP)             │
└──────────────┬──────────────────────┘
               ↓
┌──────────────┴──────────────────────┐
│        Vers AE2 / Storage           │
└─────────────────────────────────────┘
```

**Composants Avancés** :

| Composant | Mod | Fonction |
|-----------|-----|----------|
| Cursed Earth | Extra Utilities | Spawn x10 |
| Fan | Mob Grinding Utils | Pousse les mobs |
| Mob Masher | Mob Grinding Utils | Kill + drops |
| Absorption Hopper | Mob Grinding Utils | Items + XP |
| XP Tap | Mob Grinding Utils | Extrait l'XP |
| Vector Plate | Dark Utilities | Transport mobs |

### Spawner-Based Farm

```
┌─────────────────────────────────────┐
│   Apotheosis Spawner (boosté)       │
│   + Sugar x16 (speed)               │
│   + Clock x16 (speed)               │
│   + Fermented Spider Eye x8 (count) │
└──────────────┬──────────────────────┘
               ↓
┌──────────────┴──────────────────────┐
│   9x9 kill zone sous le spawner    │
│   Spikes Diamond / Mob Masher       │
└─────────────────────────────────────┘
```

---

## Setup Productive Bees Optimal

### Ruche Optimale

```
┌─────────────────────┐
│  Advanced Beehive   │
│  ┌───────────────┐  │
│  │ Bee (max gene)│  │
│  │ + Upgrades :  │  │
│  │ - Productivity│  │
│  │ - Speed       │  │
│  │ - Filtering   │  │
│  │ - Simulation  │  │
│  └───────────────┘  │
└─────────┬───────────┘
          ↓
┌─────────┴───────────┐
│  Powered Centrifuge │
└─────────┬───────────┘
          ↓
┌─────────┴───────────┐
│   Vers stockage     │
└─────────────────────┘
```

### Genes Optimaux

!!! success "Target ces genes"
    | Gene | Niveau Optimal | Effet |
    |------|----------------|-------|
    | Productivity | Very High | +200% combs |
    | Endurance | Very High | Vie x3 |
    | Temper | Passive | Pas de piqûre |
    | Behavior | Metaturnal | Jour + Nuit |
    | Weather Tolerance | Any | Pluie OK |

### Processus de Breeding

```
1. Capturer abeilles sauvages
          ↓
2. Breeding Chamber (genes de gauche = prioritaires)
          ↓
3. Gene Sampler sur les bébés
          ↓
4. Combiner genes + Honey Treat
          ↓
5. Appliquer sur l'abeille (clic droit)
          ↓
6. Répéter jusqu'à genes parfaits
```

### Layout de Production

```
[Hive 1] [Hive 2] [Hive 3] [Hive 4]
    \       \       /       /
     \       \     /       /
      \       \   /       /
       └───────┴─┴───────┘
               │
        [Chest Buffer]
               │
     [Powered Centrifuge]
               │
        [AE2 Interface]
```

---

## Setup Mystical Agriculture Max

### Configuration Maximale

```
         [Plant]
            │
   ┌────────┼────────┐
   │   64x Growth    │
   │   Accelerators  │
   │   (en colonne   │
   │    sous le sol) │
   └────────┬────────┘
            │
   [Supremium Farmland]
            +
   [Lily Pad of Fertility]
```

### Détails

!!! danger "Setup OP"
    | Composant | Quantité | Effet |
    |-----------|----------|-------|
    | Growth Accelerator | 64 (max) | +6400% vitesse |
    | Supremium Farmland | 1 par plant | +50% drops |
    | Lily Pad of Fertility | 1 nearby | +bonus croissance |
    | Harvester (IF) | 1 | Auto-récolte |

### Automation

```
[Mystical Crops]
       ↓
[Plant Gatherer (IF)]
       ↓
[Modular Router avec filtres]
       ├── Inferium → Crafter (4→1 tier up)
       ├── Prudentium → Crafter
       ├── ... (chaque tier)
       └── Supremium → Stockage final
```

### Calcul de Production

```
Sans accélérateurs : ~2-3 min par récolte
Avec 64 accélérateurs : ~2-3 sec par récolte
= 20-30x plus de production
```

---

## Setup Botania Mana Infini

### Entropinnyum Automation

!!! success "Mana par TNT"

```
┌─────────────────────────────────────┐
│   Dispenser avec TNT                │
│          ↓                          │
│   [Piston pousse TNT]               │
│          ↓                          │
│   Zone d'explosion (2 blocs min)    │
│          ↓                          │
│   [Entropinnyum]                    │
│          ↓                          │
│   [Mana Spreader]                   │
│          ↓                          │
│   [Mana Pool]                       │
└─────────────────────────────────────┘
```

**Automation** :
1. Redstone timer (2-3 sec interval)
2. Dispenser drop TNT
3. Piston pousse TNT vers Entropinnyum
4. Explosion génère du mana

!!! warning "Attention"
    - L'Entropinnyum doit voir l'explosion
    - Pas trop rapide (cooldown de la fleur)
    - Protéger la zone avec Obsidian

### Kekimurus (Cake Farm)

```
[Create Mechanical Arm]
       ↓
[Place Cake devant Kekimurus]
       ↓
[Kekimurus mange le cake]
       ↓
[Mana généré]
```

**Production de Cakes** :
- Farmer's Delight automation
- Create mechanical crafting
- AE2 autocrafting

### Gourmaryllis (Food)

```
[AE2 ou Hopper avec nourriture variée]
       ↓
[Open Crate]
       ↓
[Gourmaryllis]
       ↓
[Mana Pool]
```

!!! tip "Variété = Plus de Mana"
    Alterner différents types de nourriture pour bonus de mana.

### Rosa Arcana (XP)

```
[Mob Farm avec XP]
       ↓
[XP stocké en fluide]
       ↓
[Relâcher XP près de Rosa Arcana]
       ↓
[Mana massif]
```

### Pool Management

```
[Mana Pool] ─── [Mana Spreader] ─── [Mana Pool 2]
     │                                    │
     └──── [Sparks pour transfert] ──────┘
```

**Tips Mana** :
- **Mana Tablet** pour transport manuel
- **Sparks** pour transfert automatique entre pools
- **Mana Detector** pour redstone quand pool plein

---

## Voir aussi

- [:octicons-arrow-right-24: Synergies](synergies.md) - Combinaisons de mods
- [:octicons-arrow-right-24: Automation](automation.md) - Techniques générales
- [:octicons-arrow-right-24: Technologie](../technologie/index.md) - AE2 et autres
- [:octicons-arrow-right-24: Farming](../farming/index.md) - Mystical Agriculture
- [:octicons-arrow-right-24: Magie](../magie/index.md) - Botania
