# Guide Integrated Dynamics - Pas à Pas

Integrated Dynamics est un mod de logique et d'automation très puissant mais complexe. Ce guide vous accompagne étape par étape.

## Pourquoi Integrated Dynamics ?

!!! success "Avantages"
    - **Filtres ultra-précis** : NBT, enchantements, durabilité, n'importe quelle condition
    - **Logique conditionnelle** : Si X alors Y
    - **Transfert intelligent** : Items, fluides, énergie avec conditions
    - **Pas de lag** : Très optimisé comparé à d'autres solutions
    - **Lecture de données** : Monitorer n'importe quoi dans votre base

!!! warning "Courbe d'apprentissage"
    Ce mod demande de la patience. Suivez ce guide pas à pas!

## Chapitre 1 : Les Bases

### Vocabulaire Essentiel

| Terme | Description |
|-------|-------------|
| **Variable** | Une donnée (nombre, booléen, item, etc.) |
| **Variable Card** | Carte contenant une variable |
| **Reader** | Lit des données depuis un bloc |
| **Writer** | Écrit/agit sur un bloc |
| **Logic Programmer** | Crée des opérations logiques |
| **Variable Store** | Stocke des variables |

### Crafts de Départ

!!! tip "Premier Setup"
    Vous aurez besoin de :

    1. **Logic Programmer** - Interface principale
    2. **Variable Cards** (beaucoup!) - Stockent les variables
    3. **Cable** - Connecte les composants
    4. **Readers/Writers** - Interagissent avec les blocs

```
Craft basique :
Menril Log → Menril Planks → Cables et composants
```

### Trouver le Menril

Le **Menril Tree** est la ressource de base. Chercher dans les biomes tempérés ou cultiver :

1. Trouver un **Menril Sapling**
2. Planter et laisser pousser
3. Récolter les **Menril Logs**
4. Extraire la **Menril Resin** avec Squeezer

## Chapitre 2 : Premier Circuit

### Objectif : Lire le contenu d'un coffre

```
[Chest] ←── [Inventory Reader] ←── [Cable] ←── [Variable Store]
```

**Étape 1** : Placer un **câble** à côté du coffre

**Étape 2** : Attacher un **Inventory Reader** au câble (face vers le coffre)

**Étape 3** : Clic droit sur le Reader → Mettre une **Variable Card vide**

**Étape 4** : La carte contient maintenant les données de l'inventaire!

### Lecture des Données

Le Reader peut lire :
- **Inventory** : Liste des items
- **Slot count** : Nombre de slots
- **Item count** : Nombre total d'items
- **Is empty** : Booléen (vrai/faux)
- Et bien plus...

## Chapitre 3 : Le Logic Programmer

!!! danger "Cœur du Mod"
    Le **Logic Programmer** permet de créer des opérations logiques.

### Interface

```
┌────────────────────────────────────────┐
│  [Input 1]  [Opérateur]  [Input 2]     │
│                                        │
│           [Output Card]                │
│                                        │
│  [Liste des opérateurs disponibles]    │
└────────────────────────────────────────┘
```

### Exemple : "Le coffre contient-il du fer ?"

1. **Input 1** : Variable Card avec l'inventaire du coffre
2. **Opérateur** : "List Contains" (liste contient)
3. **Input 2** : Variable Card avec "Iron Ingot"
4. **Output** : Boolean (true/false)

### Opérateurs Utiles

| Opérateur | Input | Output | Usage |
|-----------|-------|--------|-------|
| Greater Than | 2 nombres | Boolean | Comparaison |
| Equals | 2 valeurs | Boolean | Égalité |
| List Contains | Liste + Item | Boolean | Recherche |
| List Count | Liste | Nombre | Comptage |
| If Then Else | Bool + 2 val | Valeur | Condition |
| AND / OR | 2 booleans | Boolean | Logique |

## Chapitre 4 : Automation avec Writers

### Inventory Writer

!!! example "Transfert Conditionnel"
    Transférer des items SEULEMENT si une condition est vraie.

```
[Coffre Source] → [Reader] → [Cable] → [Writer] → [Coffre Destination]
                     ↑
              [Logic: condition]
```

**Setup** :
1. Reader sur le coffre source
2. Writer sur le coffre destination
3. Logic Programmer pour créer la condition
4. Insérer la condition dans le Writer

### Exemple Pratique : Trier le Cobblestone

**Objectif** : Envoyer le cobblestone vers un void, le reste vers le stockage.

1. **Reader** sur coffre d'entrée → Lit les items
2. **Logic Programmer** : "Item equals Cobblestone?"
3. **Writer 1** (vers void) : Active si TRUE
4. **Writer 2** (vers stockage) : Active si FALSE

## Chapitre 5 : Filtres Avancés

### Filtrer par NBT/Enchantement

!!! success "La vraie puissance d'Integrated Dynamics"

**Exemple** : Garder seulement les épées avec Sharpness V+

```
1. Reader lit l'inventaire
2. Logic: "Get Enchantments" sur chaque item
3. Logic: "List Contains Sharpness"
4. Logic: "Enchantment Level >= 5"
5. Writer transfère seulement si TRUE
```

### Filtrer par Durabilité

Envoyer les outils cassés vers réparation :

```
Item → Get Damage → Greater Than 90% → Si TRUE → Vers réparation
```

### Filtrer par Mod

```
Item → Get Mod ID → Equals "mekanism" → Si TRUE → Vers stockage Mekanism
```

## Chapitre 6 : Integrated Tunnels

!!! tip "Extension Essentielle"
    **Integrated Tunnels** ajoute le transfert réel d'items/fluides/énergie.

### Composants Tunnels

| Bloc | Fonction |
|------|----------|
| Item Interface | Import/Export items |
| Fluid Interface | Import/Export fluides |
| Energy Interface | Import/Export RF/FE |
| World Item Interface | Ramasse items par terre |
| World Block Reader | Lit les blocs du monde |

### Exemple : Import/Export avec Conditions

```
[Machine] ←→ [Item Interface] ←→ [Cable avec Logic] ←→ [AE2 Interface]

Logic: Exporter vers AE2 seulement si la machine a fini
       (slot output non vide ET slot input vide)
```

## Chapitre 7 : Monitoring

### Afficher des Données

**Display Panel** : Affiche des variables sur un écran

```
[Variable Store] → [Cable] → [Display Panel]

Affiche :
- Niveau d'énergie
- Nombre d'items
- État de machines
- Alertes
```

### Alertes

Créer une alerte si l'énergie est basse :

```
Energy Reader → "Is Less Than 10000?" → Si TRUE → Redstone Writer (alarme)
```

## Recettes Importantes

### Ressources de Base

| Item | Craft |
|------|-------|
| Menril Log | Arbre Menril |
| Logic Cable | Menril Planks |
| Variable Card | Paper + Menril |
| Logic Programmer | Menril + Redstone + Chest |

### Readers/Writers

| Item | Usage |
|------|-------|
| Inventory Reader | Lit les inventaires |
| Redstone Reader | Lit signal redstone |
| Energy Reader | Lit l'énergie RF |
| Machine Reader | Lit l'état des machines |
| Block Reader | Lit les blocs du monde |

## Projets Pratiques

### Projet 1 : Auto-Smelting Intelligent
Envoie les minerais vers la fonderie, le reste vers le stockage.

### Projet 2 : Alarme Low Energy
Alerte quand l'énergie passe sous un seuil.

### Projet 3 : Tri par Mod
Chaque mod a son propre coffre de stockage.

### Projet 4 : Repair Station
Envoie automatiquement les outils endommagés vers la réparation.

## Ressources

!!! info "Liens Utiles"
    - [Wiki Officiel](https://integrateddynamics.rubensworks.net/)
    - [Guide Vidéo](https://www.youtube.com/results?search_query=integrated+dynamics+tutorial)
    - In-game: **On the Dynamics of Integration** (livre guide)

---

## Voir aussi

- [:octicons-arrow-right-24: Technologie](../technologie/index.md) - Autres mods d'automation
- [:octicons-arrow-right-24: Automation](automation.md) - Techniques générales
- [:octicons-arrow-right-24: Stockage](../stockage/index.md) - Intégration avec systèmes de stockage
