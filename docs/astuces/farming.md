# Guide des Techniques de Farming

Tout ce qu'il faut savoir pour optimiser la production de ressources via le farming en Minecraft modde.

---

## Acceleration de Croissance

### Comparaison des Methodes

| Methode | Mod | Difficulte | Efficacite | Stackable | Phase |
|---------|-----|:----------:|:----------:|:---------:|:-----:|
| Sprinkler | Cyclic | :star: | :star::star::star: | Non | :zap: RUSH |
| Growth Accelerator | Mystical Agriculture | :star::star: | :star::star::star::star::star: | Oui (64x) | Early -> Late |
| Lily Pad of Fertility | Reliquary | :star: | :star::star::star: | Non | Early |
| Phyto-Gro | Thermal | :star::star: | :star::star::star::star: | N/A (consomme) | Mid |
| Growth Crystal T3 | Tiny Progression | :star::star: | :star::star::star::star: | Non | Mid |
| Terra Preta | Cyclic | :star: | :star::star: | N/A (sol) | Early |
| Crop Support | PneumaticCraft | :star::star: | :star::star::star: | Non | Mid |
| SNAD | SNAD | :star: | :star::star::star: | N/A (sol) | Early |
| Garden Cloche | Immersive Engineering | :star::star: | :star::star::star::star: | Non | Mid |
| Hydroponic Bed | Industrial Foregoing | :star::star::star: | :star::star::star::star::star: | Non | Mid -> Late |

### Sprinkler (Cyclic)

!!! tip "RUSH - Early Game"
    Le **Sprinkler de Cyclic** est l'une des meilleures options early game pour accelerer les crops.

    - Craft simple, accessible tres tot
    - Couvre une zone autour de lui
    - Necessite de l'eau en dessous ou a proximite
    - Combinable avec d'autres accelerateurs

```
Recherche JEI : sprinkler @cyclic
```

### Growth Accelerators (Mystical Agriculture)

!!! success "Meilleure Option Mid-Late Game"
    Les **Growth Accelerators** de Mystical Agriculture sont extremement puissants grace a leur stackabilite.

    - Se placent **sous le farmland** (pas a cote!)
    - **Stackables jusqu'a 64** sous un seul bloc de terre
    - Effet cumulatif : 64 accelerators = croissance quasi-instantanee
    - Consomment de l'energie (FE/RF)

!!! example "Setup Optimal"
    ```
    [Crop]
    [Essence Farmland]
    [Growth Accelerator x64]
    ```

    Creuser 64 blocs sous le farmland et remplir de Growth Accelerators pour une vitesse maximale.

### Lily Pad of Fertility (Reliquary)

!!! note "Option Passive"
    La **Lily Pad of Fertility** accelere les crops dans une zone autour d'elle.

    - Se place sur l'eau
    - Zone d'effet autour du nenuphare
    - Pas d'energie requise
    - Combinable avec d'autres methodes

### Phyto-Gro (Thermal Series)

!!! info "Fertilisant Puissant"
    **Phyto-Gro** est un fertilisant de Thermal qui accelere considerablement la croissance.

    - **Phyto-Gro** : Version basique
    - **Rich Phyto-Gro** : Version amelioree, plus efficace
    - **Fluxed Phyto-Gro** : Version ultime, effet instantane

    Peut etre applique manuellement ou automatiquement via des machines Thermal.

```
Recherche JEI : phyto-gro @thermal
```

### Sols Magiques

| Sol | Mod | Effet |
|-----|-----|-------|
| Terra Preta | Cyclic | Acceleration de croissance |
| Rich Soil | Farmer's Delight | Auto-bone meal aux crops adjacents |
| Essence Farmland | Mystical Agriculture | +10% drops, requis pour certaines seeds |
| Hydroponic Bed | Industrial Foregoing | Croissance ultra-rapide |
| SNAD | SNAD | Sable accelere pour cactus/canne a sucre |

!!! tip "SNAD"
    **SNAD** est un mod simple mais efficace :

    - Remplace le sable sous les cactus et cannes a sucre
    - Accelere considerablement leur croissance
    - Parfait pour la production de bone meal via cactus -> green dye -> composter

---

## Farming Automatise par Mod

### Industrial Foregoing

!!! success "Solution Complete"
    Industrial Foregoing offre une solution de farming complete et puissante.

| Machine | Fonction | Priorite |
|---------|----------|:--------:|
| Plant Sower | Plante automatiquement les seeds | :star: |
| Plant Gatherer | Recolte automatiquement les crops | :star: |
| Plant Fertilizer | Applique bone meal automatiquement | :star: |
| Hydroponic Bed | Sol ultra-rapide | :star: |
| Animal Rancher | Collecte laine, lait, oeufs | |
| Animal Baby Separator | Separe bebes des adultes | |
| Mob Duplicator | Clone des mobs captures | |
| Sewage Composter | Transforme sewage en fertilisant | |

```
Setup basique :
[Plant Sower] -> [Zone de farming 9x9] <- [Plant Gatherer]
                         |
                  [Plant Fertilizer]
```

### Cyclic

| Machine | Fonction | Priorite |
|---------|----------|:--------:|
| Harvester | Recolte en zone | :star: |
| Forester | Coupe les arbres automatiquement | |
| Sprinkler | Accelere la croissance | :zap: RUSH |

!!! tip "Harvester de Cyclic"
    Le **Harvester** est une bonne option early-mid game :

    - Recolte les crops matures dans une zone
    - Output vers inventaire adjacent ou hopper
    - Facile a crafter

### Botany Pots

!!! success "Farming Compact 1x1"
    Les **Botany Pots** permettent de farmer n'importe quelle plante en 1x1.

| Variante | Fonction |
|----------|----------|
| Botany Pot | Pot basique, recolte manuelle |
| Hopper Botany Pot | Export automatique vers inventaire en dessous |

**Avantages :**

- Tres compact (1 bloc)
- Supporte presque toutes les plantes
- Compatible Mystical Agriculture
- Facile a automatiser

**Configuration :**

1. Placer un sol dans le pot (dirt, farmland, soul sand...)
2. Placer une seed
3. Attendre la croissance
4. Pour Mystical Agriculture : utiliser **Essence Farmland** comme sol

!!! example "Combo Puissant"
    **Botany Pots + Compacting Drawers** :

    - Hopper Botany Pot avec seed d'Inferium
    - Output vers Compacting Drawer
    - Auto-compression 4x Inferium -> Prudentium -> Tertium -> etc.

### Garden Cloche (Immersive Engineering)

!!! info "Farming Enclosed"
    La **Garden Cloche** est une structure 2 blocs de haut qui fait pousser les plants automatiquement.

    - Necessite de l'eau et de l'energie
    - Farming automatique et continu
    - Output vers inventaire
    - Supporte la plupart des crops

```
[Garden Cloche]
    |
  [Hopper ou Pipe]
    |
[Stockage]
```

### Bonsai Trees

!!! tip "Bois Passif"
    Les **Bonsai Trees** font pousser des arbres miniatures.

    - Parfait pour production de bois passive
    - **Hopping Bonsai Pot** exporte automatiquement
    - Supporte tous les types d'arbres
    - Compact et efficace

---

## Ressources Farmables

### Mystical Agriculture - Seeds pour Tout

!!! success "Cultiver N'importe Quelle Ressource"
    Mystical Agriculture permet de cultiver **toutes les ressources** du jeu via des seeds.

**Progression des Tiers :**

| Tier | Nom | Exemples de Seeds |
|:----:|-----|-------------------|
| 1 | Inferium | Inferium (base de tout) |
| 2 | Prudentium | Copper, Tin, Coal |
| 3 | Tertium | Iron, Redstone, Nether |
| 4 | Imperium | Gold, Diamond, Ender |
| 5 | Supremium | Nether Stars, Dragon Egg |
| 6 | Insanium | Ressources end-game (Agradditions) |

**Objets Essentiels :**

| Objet | Fonction |
|-------|----------|
| Inferium Seeds | Base de toutes les essences |
| Essence Farmland | Sol qui boost les drops (+10% a +50%) |
| Growth Accelerator | Accelere la croissance (stack 64x) |
| Scythe | Recolte en AOE (3x3 a 7x7) |
| Infusion Crystal | Requis pour craft les seeds |
| Soulium Dagger | Augmente drops de Mob Chunks |

!!! tip "Recherche JEI"
    - `@mystical seed` : Toutes les seeds disponibles
    - `essence` : Toutes les essences
    - `inferium` : Items lies a la base

### Productive Bees - Mobs vers Ressources

!!! info "Abeilles Productrices"
    Les abeilles de Productive Bees peuvent produire des ressources de mobs.

    - **Zombie Bee** : Rotten Flesh
    - **Skeleton Bee** : Bones
    - **Wither Bee** : Wither Skeleton drops
    - **Dragon Bee** : Dragon Breath, Dragon Scales

**Setup de base :**

1. Capturer l'abeille avec **Bee Cage**
2. Placer dans **Advanced Beehive**
3. Fournir la bonne fleur (verifier dans JEI)
4. Collecter les combs
5. Traiter dans **Centrifuge**

!!! example "Genetique Optimale"
    | Trait | Niveau Optimal | Effet |
    |-------|----------------|-------|
    | Productivity | Very High | Plus de combs |
    | Endurance | Very High | Duree de vie |
    | Behavior | Metaturnal | Jour et nuit |

### Chickens Mod

!!! note "Poules Productrices"
    Le mod Chickens ajoute des poules qui pondent des ressources.

    - Breeding de poules pour obtenir de nouvelles varietes
    - Progression par croisement
    - Entierement passif une fois setup
    - Compatible avec nests pour auto-collection

### Animal Farming

| Mod | Machine | Fonction |
|-----|---------|----------|
| Industrial Foregoing | Animal Rancher | Collecte laine, lait, oeufs |
| Industrial Foregoing | Animal Baby Separator | Separe bebes pour breeding |
| Industrial Foregoing | Mob Duplicator | Clone les animaux |
| Cyclic | Breeder | Fait reproduire les animaux |
| Cyclic | Transporter | Deplace les mobs |

---

## Setups Optimaux

### Farm Compacte 9x9

!!! success "Setup Recommande"
    Configuration optimale pour une farm Mystical Agriculture :

```
Layout 9x9 :
[S][S][S][S][S][S][S][S][S]
[S][C][C][C][C][C][C][C][S]
[S][C][C][C][C][C][C][C][S]
[S][C][C][C][C][C][C][C][S]
[S][C][C][C][C][C][C][C][S]
[S][C][C][C][C][C][C][C][S]
[S][C][C][C][C][C][C][C][S]
[S][C][C][C][C][C][C][C][S]
[S][S][S][S][S][S][S][S][S]

S = Sprinkler ou bord
C = Crop sur Essence Farmland

Sous chaque bloc de farmland : 64 Growth Accelerators
```

**Automation :**

- **Plant Gatherer** (Industrial Foregoing) au centre ou a cote
- Output vers **Storage Drawers** ou systeme de stockage
- **Plant Sower** pour replanter automatiquement

### Infinite Bone Meal

!!! tip "Bone Meal Infini"
    Plusieurs methodes pour generer du bone meal infiniement :

**Methode 1 : Cactus + Composter**

```
[Cactus sur SNAD]
       |
   [Hopper]
       |
  [Composter]
       |
   [Hopper]
       |
 [Bone Meal]
```

**Methode 2 : Mystical Agriculture**

- Cultiver des **Nature Seeds** pour Fertilized Essence
- Convertir en bone meal

**Methode 3 : Mob Farm**

- Farm de Skeletons avec Mob Crusher
- Collecte automatique des bones

### XP depuis le Farming

!!! info "Gagner de l'XP en Farmant"
    Certaines methodes de farming generent de l'XP :

| Methode | Source d'XP |
|---------|-------------|
| Plant Gatherer | XP des crops avec module XP |
| Smelting | XP du four automatise |
| Mystical Ag Seeds | Certaines seeds donnent XP |
| Mob Farm liee | Kills de mobs = XP |

**Setup XP :**

1. Utiliser **XP Collector** ou **XP Obelisk** a proximite
2. Stocker dans **XP Tome** ou **XP Tank**
3. Utiliser **XP Shower** pour appliquer

---

## Tips JEI pour le Farming

!!! abstract "Recherches Utiles"

### Tags et Filtres

| Recherche | Resultat |
|-----------|----------|
| `#crops` | Tous les items tagges comme crops |
| `#seeds` | Toutes les seeds |
| `seed` | Items contenant "seed" dans le nom |
| `bee` | Tous les items lies aux abeilles |
| `@mystical` | Items de Mystical Agriculture |
| `@productive` | Items de Productive Bees |
| `@industrial` | Items d'Industrial Foregoing |

### Trouver les Recettes de Growth

| Recherche | Ce que ca trouve |
|-----------|------------------|
| `growth` | Accelerateurs de croissance |
| `fertilizer` | Engrais et fertilisants |
| `accelerator` | Growth Accelerators |
| `phyto` | Phyto-Gro de Thermal |
| `sprinkler` | Sprinklers |
| `#crop` | Items qui affectent les crops |

### Astuces JEI

!!! tip "Navigation Rapide"
    - **U** sur un item : Voir ses utilisations (recipes qui l'utilisent)
    - **R** sur un item : Voir comment le crafter
    - **Clic molette** : Voir l'item dans JEI
    - Taper `@mod_name` : Filtrer par mod

!!! example "Exemples de Recherche"
    - `iron seed` : Trouver la seed d'iron
    - `@mystical essence` : Toutes les essences Mystical
    - `bee @productive` : Toutes les abeilles Productive Bees
    - `growth @mystical` : Growth items de Mystical Ag

---

## Synergies entre Mods

!!! success "Combinaisons Puissantes"

### Mystical Agriculture + Botany Pots

Cultiver les essences en format compact 1x1 :

- Hopper Botany Pot avec Essence Farmland
- Seeds Mystical dans le pot
- Output vers Compacting Drawers pour auto-tier up

### Mystical Agriculture + Growth Accelerators + Industrial Foregoing

Setup de farming ultime :

- 64 Growth Accelerators sous chaque farmland
- Plant Gatherer pour recolte auto
- Plant Sower pour replantation
- Vitesse maximale + full automation

### Productive Bees + Mystical Agriculture

Certaines abeilles produisent directement de l'essence :

- Creer des abeilles d'essence via breeding
- Production passive continue
- Moins de maintenance que les crops

### Cyclic Sprinkler + Lily Pad + Phyto-Gro

Stacker les accelerateurs pour early game :

- Sprinkler en bordure de farm
- Lily Pad of Fertility sur l'eau d'irrigation
- Phyto-Gro applique manuellement ou automatiquement
- Effet cumulatif

---

## Checklist Farming

!!! success "Early Game"
    - [ ] Craft un **Sprinkler** de Cyclic
    - [ ] Setup basique avec farmland et eau
    - [ ] Obtenir des **Botany Pots** pour farming compact
    - [ ] Commencer **Mystical Agriculture** avec Inferium Seeds

!!! note "Mid Game"
    - [ ] Obtenir des **Growth Accelerators** (stack sous farmland)
    - [ ] Setup **Industrial Foregoing** (Sower + Gatherer)
    - [ ] Commencer **Productive Bees** pour diversifier
    - [ ] Automatiser la production de bone meal

!!! abstract "Late Game"
    - [ ] 64 Growth Accelerators sous chaque farmland
    - [ ] Seeds Mystical Ag de tous les tiers
    - [ ] Abeilles optimisees genetiquement
    - [ ] Integration complete avec systeme de stockage (AE2/RS)

---

## Ressources Externes

| Ressource | Description |
|-----------|-------------|
| [Mystical Ag Wiki](https://blakesmods.com/wiki/mysticalagriculture/) | Guide officiel Mystical Agriculture |
| [Productive Bees Docs](https://productive-bees.readthedocs.io/) | Documentation Productive Bees |
| [Inferium Farm Reddit](https://www.reddit.com/r/SkyFactory/comments/16vqp0a/help_me_make_a_op_inferium_farm/) | Setup Inferium optimise |
| [All The Guides - Farming](https://allthemods.github.io/alltheguides/atm9/) | Guides ATM9 |
