# Guide Farming de Mob Drops

Toutes les méthodes pour obtenir des drops de mobs sans combat manuel.

## Comparatif des Méthodes

| Méthode | Mod | Setup | Efficacité | Coût | Drops Spéciaux |
|---------|-----|:-----:|:----------:|:----:|:--------------:|
| Mob Farm Classique | Vanilla+ | Facile | 3/5 | Bas | Non |
| Hostile Neural Networks | HNN | Moyen | 5/5 | Moyen | Oui (simulation) |
| Productive Bees | Productive Bees | Complexe | 4/5 | Moyen | Oui (combs) |
| Drygmy Farm | Ars Nouveau | Moyen | 4/5 | Bas | Oui (boss!) |
| Mob Duplicator | Industrial Foregoing | Facile | 5/5 | Haut | Oui |
| Soul Cage | Spirit | Moyen | 4/5 | Moyen | Non |
| Mystical Agriculture | Mystical Ag | Facile | 4/5 | Moyen | Via seeds |
| Apotheosis Spawner | Apotheosis | Moyen | 5/5 | Variable | Non |

## Méthode 1 : Hostile Neural Networks (HNN)

!!! success "Meilleure Méthode Générale"
    Simule les mobs sans les spawner = pas de lag, drops garantis.

### Setup
```
1. Data Model (mob spécifique)
     ↓
2. Deep Learner (train en tuant des mobs)
     ↓
3. Simulation Chamber (simule le mob)
     ↓
4. Loot Fabricator (produit les drops)
```

### Progression des Modèles
| Tier | Kills requis | Efficacité | Prediction Quality |
|------|--------------|------------|-------------------|
| Faulty | 0 | 0% | Très mauvais |
| Basic | ~6 | 25% | Mauvais |
| Advanced | ~18 | 50% | Correct |
| Superior | ~54 | 75% | Bon |
| Self-Aware | ~162 | 100% | Parfait |

### Mobs Prioritaires
!!! danger "À farmer en premier"
    1. **Wither Skeleton** → Wither Skulls (Nether Stars!)
    2. **Shulker** → Shulker Shells
    3. **Enderman** → Ender Pearls
    4. **Blaze** → Blaze Rods
    5. **Ghast** → Ghast Tears
    6. **Wither** → Nether Stars sans combat!

### Tips
- Un modèle **Self-Aware** = efficacité maximale
- Les **Prediction Matrices** sont consommées
- Automatiser la production de matrices via AE2

## Méthode 2 : Drygmy Farm (Ars Nouveau)

!!! tip "Farm de Boss Possible!"
    Les Drygmys peuvent farmer les drops de BOSS.

### Setup Basique
```
[Enclos avec mobs passifs]
      ↓
[Drygmy x4-8 autour]
      ↓
[Chest/Hopper pour collecter]
```

### Farm de Boss
1. Invoquer un boss dans un enclos sécurisé
2. Placer des **Drygmys** autour
3. Les Drygmys génèrent les drops du boss périodiquement
4. Le boss ne meurt pas = drops infinis

**Fonctionne avec** : Wither, Ender Dragon (certains setups), mobs de mods

### Tips
- Plus de Drygmys = plus de drops
- Ajouter un **Starbuncle** pour collecter les items
- Les mobs doivent être "proches" des Drygmys

## Méthode 3 : Productive Bees

!!! example "Ressources via Abeilles"

### Abeilles de Mobs
| Abeille | Produit | Obtention |
|---------|---------|-----------|
| Skeletal Bee | Bone Comb → Bones | Breeding |
| Zombie Bee | Rotten Comb | Breeding |
| Creeper Bee | Gunpowder Comb | Breeding |
| Ender Bee | Ender Comb | Breeding avec End resources |
| Wither Bee | Wither Comb | Très difficile |
| Dragon Bee | Dragon Comb | Extrêmement rare |

### Optimisation
1. Améliorer les **genes** (Very High Productivity)
2. Utiliser **Advanced Beehive** avec upgrades
3. Automatiser la **Centrifuge** vers le stockage
4. Breeding Chamber pour améliorer les traits

## Méthode 4 : Mob Duplicator (Industrial Foregoing)

!!! warning "Simple mais Coûteux en Énergie"

### Setup
```
1. Safari Net (capturer le mob)
     ↓
2. Mob Duplicator (spawn le mob)
     ↓
3. Mob Crusher (tue et collecte)
```

### Configuration
- **Mob Duplicator** : Clone le mob du Safari Net
- **Mob Crusher** : 300 dégâts/op, tue presque tout en 1 coup
- **Looting Mode** sur Crusher = plus de drops (mais pas d'Essence)

### Tips
- Ne duplique pas les bébés (utile pour breeding farms)
- Très gourmand en énergie
- Safari Net réutilisable

## Méthode 5 : Apotheosis Spawner

!!! success "Spawners Boostés"

### Modifiers de Spawner
| Item | Effet |
|------|-------|
| Sugar | -5 ticks délai min |
| Clock | -5 ticks délai max |
| Fermented Spider Eye | +1 mob/spawn |
| Ghast Tear | Ignore joueur proche |
| Comparator | Redstone control |

### Setup Optimal
```
Spawner + 16x Sugar + 16x Clock + 8x Fermented Spider Eye
     ↓
Spawn très rapide de multiples mobs
     ↓
Mob Masher / Spikes pour kill
     ↓
Vacuum Hopper pour collecter
```

## Méthode 6 : Soul Cage (Spirit)

### Progression
1. **Soul Gem** - Capture les âmes en tuant
2. Collecter assez d'âmes pour le tier voulu
3. **Soul Cage** - Spawner craftable

| Tier | Âmes | Spawn Rate |
|------|------|------------|
| 1 | 16 | Lent |
| 2 | 64 | Normal |
| 3 | 128 | Rapide |
| 4 | 256 | Très rapide |
| 5 | 512 | Maximum |

### Tips
- Compatible avec Apotheosis pour boost supplémentaire
- Redstone pour activer/désactiver
- Soul Pedestals augmentent le tier

## Méthode 7 : Mystical Agriculture Seeds

!!! tip "Crops de Mob Drops"

### Seeds Disponibles
| Seed | Drop | Tier |
|------|------|------|
| Zombie | Rotten Flesh | 1 |
| Skeleton | Bones | 1 |
| Creeper | Gunpowder | 2 |
| Spider | String, Spider Eye | 2 |
| Blaze | Blaze Rod | 3 |
| Enderman | Ender Pearl | 3 |
| Wither Skeleton | Wither Skull | 4 |
| Ghast | Ghast Tear | 4 |

### Optimisation
- **Growth Accelerators** x64 sous le farmland
- **Soulium Dagger** pour obtenir les Mob Chunks
- Automatiser avec **Plant Gatherer** ou **Farming Stencil**

## Tableau des Drops par Méthode

| Drop | HNN | Bees | Drygmy | Seeds | Spawner |
|------|:---:|:----:|:------:|:-----:|:-------:|
| Ender Pearl | 5/5 | 3/5 | 4/5 | 4/5 | 4/5 |
| Blaze Rod | 5/5 | 3/5 | 4/5 | 4/5 | 5/5 |
| Wither Skull | 5/5 | 4/5 | 5/5 | 4/5 | 3/5 |
| Nether Star | 5/5 | 4/5 | 5/5 | - | - |
| Ghast Tear | 5/5 | 3/5 | 4/5 | 4/5 | 4/5 |
| Shulker Shell | 5/5 | 2/5 | 3/5 | 3/5 | 3/5 |
| Dragon Breath | 3/5 | 2/5 | 4/5 | - | - |

---

## Voir aussi

- [:octicons-arrow-right-24: Mob Farm](../mob-farm/index.md) - Structures de mob farms
- [:octicons-arrow-right-24: Farming](../farming/index.md) - Mystical Agriculture détaillé
- [:octicons-arrow-right-24: Magie](../magie/index.md) - Drygmys et Ars Nouveau
