# Guide Late-Game (50h+)

!!! success "Bienvenue dans l'End-Game"
    Vous avez survécu aux premières heures, maîtrisé les bases des mods majeurs, et construit une infrastructure solide. Il est temps de viser l'infini et au-delà !

---

## Objectifs End-Game

| Objectif | Difficulté | Temps estimé | Prérequis |
|----------|------------|--------------|-----------|
| Armure Draconic complète | :material-star: :material-star: :material-star: :material-star: | 10-20h | Chaos Guardian tué |
| MekaSuit maxé | :material-star: :material-star: :material-star: | 5-10h | Fusion nucléaire |
| EMC infini | :material-star: :material-star: | 3-5h | Transmutation Table |
| Réacteur Draconic stable | :material-star: :material-star: :material-star: :material-star: :material-star: | 15-30h | Awakened Draconium |
| Items créatifs | :material-star: :material-star: :material-star: :material-star: :material-star: | 50h+ | Tout le reste |

---

## Armures & Armes Ultimes

### Comparatif des Armures End-Game

| Armure | Protection | Mobilité | Capacités spéciales | Coût |
|--------|------------|----------|---------------------|------|
| **Draconic Evolution** | ∞ | Vol créatif | Bouclier, effets, stockage RF | Très élevé |
| **MekaSuit** | Très haute | Jetpack intégré | Modules modulaires, vision | Élevé |
| **Supremium** | Haute | Normale | Essence farming boost | Moyen |
| **Terrasteel (Botania)** | Haute | Normale | Régénération mana | Moyen |

---

### Draconic Evolution Armor

!!! warning "Attention"
    L'armure Draconic nécessite de tuer le **Chaos Guardian** pour obtenir les Chaos Shards, l'un des boss les plus difficiles du modpack.

=== "Craft de base"

    ```
    Prérequis:
    ├── Wyvern Armor (set complet)
    ├── Awakened Draconium Blocks (x16 minimum)
    ├── Draconic Cores (x4)
    └── Chaos Shards (x4) - Drop du Chaos Guardian
    ```

=== "Upgrades recommandés"

    | Upgrade | Effet | Priorité |
    |---------|-------|----------|
    | Shield Capacity | Bouclier absorbant les dégâts | :material-star: :material-star: :material-star: |
    | Shield Recovery | Régénération du bouclier | :material-star: :material-star: :material-star: |
    | RF Capacity | Stockage d'énergie interne | :material-star: :material-star: |
    | Speed | Vitesse de déplacement | :material-star: :material-star: |
    | Jump Boost | Hauteur de saut | :material-star: |
    | Flight Speed | Vitesse de vol | :material-star: :material-star: :material-star: |

=== "Configuration optimale"

    ```yaml
    Casque:
      - Night Vision: ON
      - Shield: MAX

    Plastron:
      - Flight: Creative Mode
      - Shield: MAX
      - RF Capacity: MAX

    Jambières:
      - Speed: 300%
      - Jump: 3 blocks

    Bottes:
      - Fall Damage: Disabled
      - Step Assist: ON
    ```

---

### MekaSuit

!!! tip "Alternative modulaire"
    Le MekaSuit est plus accessible que l'armure Draconic et offre une grande flexibilité grâce à son système de modules.

=== "Modules essentiels"

    | Module | Pièce | Fonction |
    |--------|-------|----------|
    | Jetpack | Plastron | Vol (hydrogène) |
    | Gravitational Modulator | Plastron | Vol créatif |
    | Vision Enhancement | Casque | Night vision + zoom |
    | Nutritional Injection | Casque | Auto-alimentation |
    | Hydrostatic Repulsor | Bottes | Marche sur l'eau |
    | Magnetic Attraction | Plastron | Ramassage à distance |

=== "Craft du MekaSuit"

    ```
    Ressources nécessaires par pièce:
    ├── HDPE Sheets (x12)
    ├── Ultimate Control Circuits (x4)
    ├── Polonium Pellets (x2)
    ├── Refined Obsidian (x8)
    └── Basic/Advanced/Elite Modules selon pièce
    ```

=== "Alimentation"

    Le MekaSuit consomme de l'énergie RF/FE.

    **Options d'alimentation:**

    - Générateur solaire portable (Mekanism)
    - QIO Charging (recommandé)
    - Induction Matrix wireless charger

---

### Supremium Armor (Mystical Agriculture)

!!! info "Pour les farmers"
    L'armure Supremium booste significativement la croissance des essences et le drop des mobs.

| Set Bonus | Effet |
|-----------|-------|
| 2 pièces | +10% vitesse de croissance des crops |
| 3 pièces | +25% vitesse de croissance |
| 4 pièces | +50% vitesse + Flight |

**Craft:**
```
Supremium Ingots: 24 au total
├── Casque: 5 ingots
├── Plastron: 8 ingots
├── Jambières: 7 ingots
└── Bottes: 4 ingots
```

---

### Enchantements Optimaux

=== "Armure"

    | Enchantement | Niveau max | Effet |
    |--------------|------------|-------|
    | Protection | IV | Réduction dégâts globale |
    | Unbreaking | III | Durabilité x4 |
    | Mending | I | Réparation via XP |
    | Soul Speed | III | Vitesse sur Soul Sand |
    | Depth Strider | III | Vitesse aquatique |
    | Feather Falling | IV | Réduction dégâts de chute |

=== "Épée"

    | Enchantement | Niveau max | Priorité |
    |--------------|------------|----------|
    | Sharpness | V | :material-star: :material-star: :material-star: |
    | Looting | III | :material-star: :material-star: :material-star: |
    | Sweeping Edge | III | :material-star: :material-star: |
    | Unbreaking | III | :material-star: :material-star: |
    | Mending | I | :material-star: :material-star: :material-star: |
    | Fire Aspect | II | :material-star: |

=== "Arc/Arbalète"

    | Enchantement | Niveau max | Notes |
    |--------------|------------|-------|
    | Power | V | Dégâts +150% |
    | Infinity | I | Flèches infinies |
    | Punch | II | Knockback |
    | Flame | I | Dégâts de feu |

!!! warning "Incompatibilités"
    - **Infinity** et **Mending** sont incompatibles sur un arc
    - Choisir **Infinity** pour le combat, **Mending** pour le farm

---

## Ressources Infinies

### Système EMC (ProjectE)

!!! success "Le Saint Graal"
    ProjectE permet de convertir n'importe quel item en EMC (énergie) puis de la reconvertir en n'importe quel autre item.

=== "Setup de base"

    ```
    Configuration EMC infinie:

    1. Transmutation Table
       └── Apprendre les recettes (clic droit avec l'item)

    2. Energy Condenser MK2
       └── Place un item "target" = production infinie

    3. Collectors (Klein Stars)
       └── Génèrent de l'EMC passivement (solaire)

    4. Relays
       └── Transfèrent l'EMC vers les Condensers
    ```

=== "Farm EMC optimisé"

    | Source | EMC/tick | Difficulté setup |
    |--------|----------|------------------|
    | Collector MK1 | 4 | Facile |
    | Collector MK2 | 12 | Moyen |
    | Collector MK3 | 40 | Difficile |
    | Blaze farm + Condenser | ~1000+ | Moyen |
    | Wither farm + Condenser | ~5000+ | Difficile |

=== "Items haute valeur EMC"

    | Item | Valeur EMC | Source recommandée |
    |------|------------|-------------------|
    | Nether Star | 139,264 | Wither farm |
    | Dragon Egg | 139,264 | Ender Dragon |
    | Beacon | 147,456 | Craft avec Nether Stars |
    | Awakened Draconium | ~500,000+ | Draconic Evolution |

---

### Mystical Agriculture Automation

!!! tip "Ressources organiques infinies"
    Avec Mystical Agriculture, vous pouvez farmer littéralement n'importe quelle ressource.

=== "Tiers des essences"

    | Tier | Couleur | Exemples | Temps croissance |
    |------|---------|----------|------------------|
    | 1 | Blanc | Inferium, Stone | Rapide |
    | 2 | Jaune | Iron, Coal | Moyen |
    | 3 | Orange | Gold, Redstone | Moyen |
    | 4 | Violet | Diamond, Emerald | Lent |
    | 5 | Rouge | Nether Star, Dragon Egg | Très lent |

=== "Setup automatisé"

    ```mermaid
    flowchart TB
        subgraph farm["Farm Setup"]
            GA["Growth Accelerators<br/>(jusqu'à 64 sous chaque plante)"]
            SS["Supremium Soil"]
            H["Harvester (Industrial Foregoing)<br/>ou<br/>Mechanical User + Hoe (Cyclic)"]
        end

        GA --> SS
        SS --> H
        H --> ST["Storage System<br/>(ME/RS/Drawer)"]
    ```

=== "Boosters de croissance"

    | Item | Bonus | Stackable |
    |------|-------|-----------|
    | Growth Accelerator | +20% par bloc | Oui (x64) |
    | Supremium Soil | +25% base | Non |
    | Greenhouse Glass | +30% | Oui |
    | Lily of the Valley (Botania) | Variable | Non |
    | Watering Can (automatisé) | +200% | Non |

---

### Void Mining

!!! info "Minage sans miner"
    Les Void Miners génèrent des ressources à partir de rien, parfait pour les serveurs où le minage intensif lag.

=== "Mekanism Digital Miner"

    Bien que pas vraiment "void", le Digital Miner avec Silk Touch:

    - Inverse Mining: mine tout dans une zone
    - Filtres précis par ore
    - Auto-replacement avec Cobblestone

    **Combo avec Laser Drill (Industrial Foregoing):**

    | Lens couleur | Ressources | Rareté |
    |--------------|------------|--------|
    | Rouge | Redstone | Commun |
    | Bleu | Lapis, Diamond | Rare |
    | Vert | Emerald | Très rare |
    | Blanc | Quartz, Certus | Commun |
    | Noir | Coal, Obsidian | Commun |

=== "Environmental Tech Void Miners"

    | Tier | RF/tick | Output |
    |------|---------|--------|
    | 1 | 2,000 | Faible |
    | 2 | 8,000 | Moyen |
    | 3 | 32,000 | Bon |
    | 4 | 128,000 | Très bon |
    | 5 | 512,000 | Excellent |
    | 6 | 2,000,000 | Insane |

=== "RFTools Builder"

    ```
    Configuration Quarry alternative:

    1. Builder Block
    2. Shape Card (Quarry)
    3. Définir zone avec 2 positions
    4. Fortune/Silk Touch via modules
    5. Void mode = pas de trou visible
    ```

---

## Énergie Maximale

### Draconic Reactor

!!! danger "ATTENTION: Explosion potentielle"
    Le réacteur Draconic peut exploser et détruire TOUT dans un rayon de ~500 blocks si mal géré. **TOUJOURS construire dans une dimension de test d'abord!**

=== "Composants requis"

    | Composant | Quantité | Fonction |
    |-----------|----------|----------|
    | Reactor Core | 1 | Centre du réacteur |
    | Reactor Stabilizer | 4 | Contrôle containment |
    | Energy Injector | 1+ | Démarre le réacteur |
    | Flux Gate | 2+ | Contrôle flux entrant/sortant |
    | Awakened Draconium Blocks | 4+ | Fuel |

=== "Paramètres sûrs"

    ```yaml
    Configuration stable:
      Containment Field: > 50% TOUJOURS
      Saturation: > 50%
      Temperature: < 8000°C (idéal: 7000-7500°C)
      Output Rate: Ajuster selon consommation

    Règles d'or:
      1. JAMAIS laisser Containment < 15%
      2. Toujours surveiller température
      3. Avoir un Failsafe (Emergency shutdown)
      4. Backup dimension recommandé
    ```

=== "Output énergétique"

    | Configuration | RF/tick | Durée fuel |
    |---------------|---------|------------|
    | Safe mode | 500,000 | Plusieurs heures réelles |
    | Optimal | 2,000,000+ | ~1-2 heures |
    | Maximum | 5,000,000+ | ~30 minutes |

    !!! tip "Conseil"
        Utilisez ComputerCraft/OpenComputers pour automatiser la surveillance!

---

### Mekanism Fusion Reactor

!!! success "Alternative plus sûre"
    Le réacteur à fusion Mekanism ne peut pas exploser et offre une excellente production d'énergie.

=== "Structure"

    ```
    Composants:
    ├── Fusion Reactor Controller
    ├── Fusion Reactor Frames (x64)
    ├── Fusion Reactor Ports (x4)
    ├── Fusion Reactor Logic Adapters (x2)
    └── Laser Amplifier (pour démarrage)

    Fuel:
    ├── D-T Fuel (Deuterium + Tritium)
    └── Produit via Heavy Water + Électrolyse
    ```

=== "Production optimale"

    | Configuration | RF/tick | Injection Rate |
    |---------------|---------|----------------|
    | Minimum viable | 100,000 | 2 mB/t |
    | Standard | 500,000 | 10 mB/t |
    | Optimisé | 2,000,000 | 98 mB/t |
    | Maximum | 5,000,000+ | 98 mB/t + Hohlraum |

=== "Chaîne de production fuel"

    ```mermaid
    flowchart TB
        W["Water"] --> EP["Electric Pump"]
        EP --> ES1["Electrolytic Separator"]
        ES1 --> H["Hydrogen"]
        ES1 --> O1["Oxygen"]
        H --> TEP["Thermal Evaporation Plant"]
        TEP --> HW["Heavy Water"]
        HW --> ES2["Electrolytic Separator"]
        ES2 --> D["Deuterium"]
        ES2 --> O2["Oxygen"]
        D --> SNA["Solar Neutron Activator"]
        SNA --> T["Tritium"]
        D --> CI["Chemical Infuser"]
        T --> CI
        CI --> DTF["D-T Fuel"]
        DTF --> FR["Fusion Reactor"]
    ```

---

### Solutions de Stockage RF

| Solution | Capacité | Avantages | Inconvénients |
|----------|----------|-----------|---------------|
| **Draconic Energy Core** | 9.2 quintillions RF (Tier 8) | Capacité insane | Très cher |
| **Induction Matrix** | ~400 milliards RF (max) | Modulaire | Moins que Draconic |
| **Flux Networks** | Transfert wireless | Pratique | Nécessite autre stockage |
| **EnderIO Capacitor Banks** | Modéré | Facile à craft | Limité |

=== "Draconic Energy Core"

    | Tier | Capacité | Blocks requis |
    |------|----------|---------------|
    | 1 | 45.5M RF | 4 Draconium |
    | 2 | 273M RF | 28 Draconium |
    | 3 | 1.64B RF | 52 Drac + 32 Redstone |
    | 4 | 9.8B RF | 76 Drac + 92 Redstone |
    | 5 | 59B RF | 100 Drac + 176 Redstone |
    | 6 | 355B RF | 124 Drac + 284 Redstone |
    | 7 | 2.14T RF | 148 Drac + 416 Redstone |
    | 8 | 9.2E RF | 172 Awakened + 572 Drac |

=== "Induction Matrix"

    ```
    Configuration recommandée:

    Structure: 7x7x7 (intérieur 5x5x5)

    Cells:
    ├── Ultimate Induction Cells (stockage)
    └── Ultimate Induction Providers (transfer)

    Ratio optimal: 80% Cells, 20% Providers
    ```

---

## Progression vers les Items Créatifs

!!! abstract "Le but ultime"
    Certains modpacks permettent de crafter des items créatifs (ou quasi-créatifs) après énormément de progression.

### Items "Créatifs" par Mod

| Mod | Item | Effet | Difficulté |
|-----|------|-------|------------|
| **Draconic Evolution** | Creative Flux Capacitor | Énergie infinie | Extrême |
| **Mekanism** | Creative Energy Cube | Énergie infinie | Extrême |
| **ProjectE** | Red Matter Furnace/Tools | Production quasi-infinie | Haute |
| **Avaritia** | Infinity Armor/Tools | Invincibilité totale | Insane |
| **Extra Utilities 2** | Creative Drum | Fluides infinis | Très haute |

=== "Avaritia (si présent)"

    ```
    Progression Avaritia:

    1. Crystal Matrix Ingots
       └── Diamonds + Extreme Crafting Table

    2. Neutronium Ingots
       └── Neutron Collector (très lent)

    3. Infinity Ingots
       └── Neutronium + EMC astronomical

    4. Infinity Armor
       └── Invincible, one-hit kill, flight
    ```

=== "Draconic Creative Items"

    Généralement non-craftables en survie, mais certains packs permettent:

    - **Creative Flux Capacitor**: Énergie infinie
    - **Creative Builder's Wand**: Construction instantanée
    - **Creative RF Source**: Pour tests

---

## Préparation aux Boss Fights

### Chaos Guardian

!!! danger "Le boss le plus difficile"
    Le Chaos Guardian est souvent considéré comme le boss le plus difficile des modpacks. Une préparation minutieuse est OBLIGATOIRE.

=== "Équipement minimum"

    | Slot | Item recommandé | Pourquoi |
    |------|-----------------|----------|
    | Armure | Wyvern full set minimum | Bouclier + vol |
    | Arme | Draconic Staff of Power | Dégâts + range |
    | Baubles | Flight ring + Regen | Mobilité + survie |
    | Potions | Strength II, Regen II | Boost combat |

=== "Stratégie de combat"

    ```
    Phase 1: Destruction des cristaux
    ├── 7 Chaos Crystals autour de l'arène
    ├── Chacun doit être détruit
    └── Attention aux explosions

    Phase 2: Combat direct
    ├── Attaques de charge
    ├── Projectiles
    ├── Zone damage
    └── BEAUCOUP de HP

    Tips:
    • Toujours bouger (vol créatif requis)
    • Avoir un point de respawn proche
    • Backup de tout l'équipement
    • Potentiellement plusieurs tentatives
    ```

=== "Rewards"

    | Drop | Quantité | Utilité |
    |------|----------|---------|
    | Chaos Shard | 1-4 | Craft armure Draconic |
    | Dragon Heart | 1 | Craft Resurrection Stone |
    | Massive XP | ~100 niveaux | Enchantements |

---

### Ender Dragon (farm)

=== "Respawn"

    ```
    Matériaux pour respawn:
    ├── End Crystals (x4)
    │   ├── Glass (x7)
    │   ├── Eye of Ender (x1)
    │   └── Ghast Tear (x1)
    └── Placer sur le portail de sortie
    ```

=== "Farm setup"

    Avec certains mods (Draconic Evolution), possibilité de farm automatiquement:

    1. **Mob Grinder** positionné au spawn
    2. **Redstone Clock** pour respawn automatique
    3. **Collection system** pour XP et drops

---

### Wither Farming

!!! tip "Source de Nether Stars"
    Les Nether Stars sont essentiels pour les Beacons et ont une haute valeur EMC.

=== "Farm manuelle"

    ```
    Setup rapide:
    1. Aller dans le Nether roof (Y=128+)
    2. Suffocate Wither sous bedrock
    3. Attaquer à distance
    4. ~30 secondes par kill
    ```

=== "Farm automatique"

    | Mod | Méthode | Output/heure |
    |-----|---------|--------------|
    | Industrial Foregoing | Wither Builder + Mob Crusher | 60+ |
    | Draconic Evolution | Mob Grinder | 120+ |
    | RFTools | Builder + Shield | 100+ |

=== "Ressources nécessaires"

    ```
    Par Wither:
    ├── Soul Sand (x4)
    └── Wither Skulls (x3)

    Farm de Skulls:
    ├── Wither Skeletons dans Nether Fortress
    ├── Looting III épée obligatoire
    └── Ou Mystical Agriculture Wither Skeleton seeds
    ```

---

## Tips Server-Friendly

!!! warning "Respectez les autres joueurs"
    En late-game, vos builds peuvent facilement laguer le serveur entier. Voici comment minimiser l'impact.

### Règles d'or

| Pratique | Impact | Alternative |
|----------|--------|-------------|
| Chunk loading excessif | Très mauvais | Limiter à 9-25 chunks |
| Machines non-utilisées ON | Mauvais | Redstone control |
| Pipes/cables exposés | Moyen | Utiliser facades |
| Entités en masse | Très mauvais | Kill switches |
| Draconic Reactor | Potentiel désastre | Dimension séparée |

### Optimisations recommandées

=== "Stockage"

    ```
    GOOD:
    ✓ ME System avec 1 controller
    ✓ Drawers compactés
    ✓ Storage Disks haute capacité

    BAD:
    ✗ Multiple ME Systems
    ✗ Milliers de coffres
    ✗ Items au sol
    ```

=== "Énergie"

    ```
    GOOD:
    ✓ Flux Networks (wireless, pas de lag)
    ✓ Energy Core centralisé
    ✓ Machines OFF quand non utilisées

    BAD:
    ✗ Milliers de câbles
    ✗ Générateurs multiples petits
    ✗ Pas de stockage (génération constante)
    ```

=== "Farms"

    ```
    GOOD:
    ✓ Farms désactivables par redstone
    ✓ Void excess items
    ✓ Limiteurs d'entités

    BAD:
    ✗ Farms 24/7 sans overflow protection
    ✗ Spawners multiples actifs
    ✗ Pas de kill timer sur mobs
    ```

---

## "J'ai tout fait" - Et maintenant?

!!! question "Vous avez vraiment tout fait?"
    Vérifiez cette checklist avant de dire que vous avez "fini" :

### Checklist End-Game

- [ ] Toutes les armures tier max obtenues
- [ ] EMC > 1 milliard
- [ ] Chaos Guardian tué (solo)
- [ ] Draconic Reactor stable 24h+
- [ ] Toutes les quêtes complétées (si modpack avec quêtes)
- [ ] Base 100% automatisée
- [ ] Chaque mod majeur maîtrisé

### Nouveaux défis

=== "Challenges personnels"

    | Défi | Description |
    |------|-------------|
    | **Speedrun** | Refaire le pack en moins de temps |
    | **Hardcore** | Tout refaire en Hardcore mode |
    | **Minimalist** | Atteindre end-game avec base compacte |
    | **One Block** | Tout faire dans un chunk |
    | **Pacifist** | Éviter de tuer (autant que possible) |

=== "Contributions communautaires"

    - **Créer un tutoriel** pour les débutants
    - **Aider sur Discord/Forum** les autres joueurs
    - **Builder** des structures pour le spawn serveur
    - **Organiser** des events (boss fights, races)

=== "Nouveaux horizons"

    ```
    Options:
    ├── Essayer un nouveau modpack
    │   ├── Expert packs (plus difficiles)
    │   ├── Tech-only ou Magic-only
    │   └── Skyblock variants
    │
    ├── Créer son propre modpack
    │   └── Combiner vos mods préférés
    │
    └── Contribuer aux mods
        ├── Bug reports
        ├── Traductions
        └── Suggestions features
    ```

---

## Résumé

!!! success "Félicitations!"
    Si vous avez atteint ce stade, vous maîtrisez les aspects les plus avancés de Minecraft moddé. Voici un récap des priorités end-game:

| Priorité | Objectif | Pourquoi |
|----------|----------|----------|
| 1 | Énergie stable infinie | Base de tout |
| 2 | Armure Draconic/MekaSuit | Survie garantie |
| 3 | EMC system | Ressources infinies |
| 4 | Automation complète | Temps libre |
| 5 | Boss kills | Achievements + drops |
| 6 | Items créatifs | Flexibilité totale |

!!! tip "Dernier conseil"
    Le vrai end-game de Minecraft, c'est de s'amuser. Si vous ne vous amusez plus, c'est peut-être le moment de faire une pause ou d'essayer quelque chose de nouveau. Le jeu sera toujours là quand vous reviendrez!

---

## Voir aussi

- [:octicons-arrow-right-24: Mid-Game Guide](mid-game.md) - Revenir aux fondations de l'automatisation
- [:octicons-arrow-right-24: Préparation Boss](boss-prep.md) - Stratégies détaillées pour les boss fights
- [:octicons-arrow-right-24: Progression Équipement](gear-progression.md) - Guide complet des armures et outils
- [:octicons-arrow-right-24: Dimensions](dimensions.md) - Explorer les dimensions alternatives
