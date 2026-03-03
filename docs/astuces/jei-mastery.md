# Maîtriser JEI (Just Enough Items)

!!! info "Le compagnon indispensable"
    JEI est **LE** mod essentiel pour naviguer dans les centaines de mods d'un modpack.
    Maîtriser ses fonctionnalités avancées vous fera gagner des heures de jeu.

---

## Utilisation de Base

=== "Raccourcis Essentiels"

    | Touche | Action | Contexte |
    |--------|--------|----------|
    | ++r++ | Voir les **recettes** d'un item | Survoler un item |
    | ++u++ | Voir les **utilisations** d'un item | Survoler un item |
    | ++clic-gauche++ | Voir les recettes | Dans la liste JEI |
    | ++clic-droit++ | Voir les utilisations | Dans la liste JEI |
    | ++shift+clic++ | Voir l'item dans le wiki | Si configuré |
    | ++ctrl+clic++ | Ajouter aux favoris | Sur un item |

=== "Navigation Interface"

    | Touche | Action |
    |--------|--------|
    | ++page-up++ / ++page-down++ | Naviguer dans les pages |
    | ++home++ | Retour à la première page |
    | ++end++ | Aller à la dernière page |
    | ++escape++ | Fermer la fenêtre de recette |
    | ++backspace++ | Retour à la recette précédente |

=== "Dans l'Inventaire"

    | Touche | Action |
    |--------|--------|
    | ++ctrl+o++ | Ouvrir les options JEI |
    | ++ctrl+f++ | Focus sur la barre de recherche |
    | ++delete++ | Effacer la recherche |
    | ++flèche-haut++ / ++flèche-bas++ | Historique de recherche |

!!! tip "Astuce de base"
    Cliquez sur la barre de recherche et tapez le nom d'un item pour filtrer instantanément la liste.

---

## Syntaxe de Recherche Avancée

### Filtres Principaux

=== "@modname - Par Mod"

    Filtre les items appartenant à un mod spécifique.

    | Recherche | Résultat |
    |-----------|----------|
    | `@thermal` | Tous les items de Thermal Series |
    | `@mekanism` | Tous les items de Mekanism |
    | `@create` | Tous les items de Create |
    | `@botania` | Tous les items de Botania |
    | `@ae2` | Tous les items d'Applied Energistics 2 |

    !!! example "Exemples pratiques"
        ```
        @thermal machine     → Machines de Thermal
        @mekanism ore        → Minerais de Mekanism
        @create gear         → Engrenages de Create
        ```

=== "#tagname - Par Tag"

    Filtre par tags Forge/Fabric (catégories d'items).

    | Recherche | Résultat |
    |-----------|----------|
    | `#forge:ores` | Tous les minerais |
    | `#forge:ingots` | Tous les lingots |
    | `#forge:gems` | Toutes les gemmes |
    | `#forge:storage_blocks` | Tous les blocs de stockage |
    | `#c:crops` | Toutes les cultures |

    !!! info "Tags vs Noms"
        Les tags permettent de trouver des items **fonctionnellement équivalents** entre mods.
        Un `#forge:ingots/copper` trouvera le cuivre de tous les mods !

=== "$tooltip - Par Tooltip"

    Recherche dans les descriptions et tooltips des items.

    | Recherche | Résultat |
    |-----------|----------|
    | `$rf` | Items mentionnant "RF" dans leur tooltip |
    | `$energy` | Items liés à l'énergie |
    | `$shift` | Items avec info supplémentaire au Shift |
    | `$tier` | Items mentionnant leur tier |

    !!! warning "Performance"
        La recherche par tooltip est plus lente. Combinez avec d'autres filtres pour de meilleurs résultats.

=== "^color - Par Couleur"

    Filtre les items par leur couleur dominante.

    | Recherche | Résultat |
    |-----------|----------|
    | `^red` | Items rouges |
    | `^blue` | Items bleus |
    | `^green` | Items verts |
    | `^yellow` | Items jaunes |
    | `^purple` | Items violets |
    | `^black` | Items noirs |
    | `^white` | Items blancs |

    !!! tip "Utilité"
        Parfait pour trouver des blocs décoratifs assortis ou des items de même "famille visuelle".

### Combinaison de Filtres

!!! success "La puissance des recherches combinées"
    Combinez plusieurs filtres avec des **espaces** pour des recherches ultra-précises.

| Recherche Combinée | Résultat |
|--------------------|----------|
| `@thermal #forge:ingots` | Lingots de Thermal uniquement |
| `@mekanism $energy machine` | Machines Mekanism liées à l'énergie |
| `#forge:ores ^green` | Minerais de couleur verte |
| `@create gear #forge:ingots` | Engrenages Create en lingot |
| `sword @botania $mana` | Épées Botania utilisant le mana |

!!! example "Recherche complexe"
    ```
    @thermal #forge:gears $rf copper
    ```
    Trouve : Engrenages en cuivre de Thermal mentionnant RF

---

## Tags Utiles à Connaître

### Tags Forge Standards

=== "Matériaux"

    | Tag | Description | Exemple |
    |-----|-------------|---------|
    | `#forge:ores` | Tous les minerais | Fer, Cuivre, Osmium... |
    | `#forge:ores/iron` | Minerai de fer spécifiquement | |
    | `#forge:ingots` | Tous les lingots | |
    | `#forge:nuggets` | Toutes les pépites | |
    | `#forge:dusts` | Toutes les poudres | |
    | `#forge:gems` | Toutes les gemmes | Diamant, Émeraude... |
    | `#forge:raw_materials` | Minerais bruts (raw) | |

=== "Blocs"

    | Tag | Description | Exemple |
    |-----|-------------|---------|
    | `#forge:storage_blocks` | Blocs de stockage | Bloc de fer, d'or... |
    | `#forge:glass` | Tous les verres | |
    | `#forge:glass_panes` | Vitres | |
    | `#forge:stone` | Pierres | |
    | `#forge:cobblestone` | Cobblestones | |
    | `#forge:gravel` | Graviers | |
    | `#forge:sand` | Sables | |

=== "Equipement"

    | Tag | Description |
    |-----|-------------|
    | `#forge:tools` | Tous les outils |
    | `#forge:tools/swords` | Épées |
    | `#forge:tools/pickaxes` | Pioches |
    | `#forge:tools/axes` | Haches |
    | `#forge:tools/shovels` | Pelles |
    | `#forge:tools/hoes` | Houes |
    | `#forge:armors` | Toutes les armures |

=== "Nourriture & Farming"

    | Tag | Description |
    |-----|-------------|
    | `#forge:crops` | Cultures |
    | `#forge:seeds` | Graines |
    | `#c:crops` | Cultures (Common tag) |
    | `#forge:foods` | Nourriture |
    | `#forge:vegetables` | Légumes |
    | `#forge:fruits` | Fruits |
    | `#forge:grain` | Céréales |

### Tags Spéciaux par Mod

=== "Mekanism"

    | Tag | Description |
    |-----|-------------|
    | `#mekanism:alloys` | Alliages Mekanism |
    | `#mekanism:enriched` | Items enrichis |
    | `#mekanism:crystals` | Cristaux |
    | `#mekanism:dirty_dusts` | Poudres sales |
    | `#mekanism:clumps` | Morceaux |
    | `#mekanism:shards` | Éclats |

=== "Thermal"

    | Tag | Description |
    |-----|-------------|
    | `#forge:gears` | Engrenages |
    | `#forge:plates` | Plaques |
    | `#forge:rods` | Tiges |
    | `#forge:coins` | Pièces |

=== "Botania"

    | Tag | Description |
    |-----|-------------|
    | `#botania:petals` | Pétales |
    | `#botania:mystical_flowers` | Fleurs mystiques |
    | `#botania:special_flowers` | Fleurs fonctionnelles |
    | `#botania:runes` | Runes |

=== "Create"

    | Tag | Description |
    |-----|-------------|
    | `#create:crushed_raw_materials` | Minerais concassés |
    | `#create:upright_on_belt` | Items debout sur convoyeur |
    | `#create:valve_handles` | Poignées de valve |

---

## Système de Favoris (Bookmarks)

### Gestion des Favoris

=== "Ajouter/Retirer"

    | Action | Comment |
    |--------|---------|
    | **Ajouter** un favori | ++a++ sur un item OU ++ctrl+clic++ |
    | **Retirer** un favori | ++a++ sur le favori OU ++ctrl+clic++ |
    | **Ajouter avec quantité** | ++shift+a++ (garde la quantité) |

    !!! tip "Zone de favoris"
        Les favoris apparaissent sur le **côté gauche** de l'inventaire par défaut.

=== "Organisation"

    **Réorganiser les favoris :**

    - **Glisser-déposer** pour réordonner
    - Les favoris persistent entre les sessions
    - Sauvegardés par monde/serveur

    **Groupes de favoris (si supporté) :**

    1. ++shift+clic++ et glisser pour créer un groupe
    2. Nommer le groupe pour mieux s'organiser
    3. Replier/déplier les groupes

=== "Bonnes Pratiques"

    !!! success "Organisation recommandée"

        **Groupez vos favoris par catégorie :**

        - :material-pickaxe: **Crafting actuel** - Items pour votre projet en cours
        - :material-star: **Essentiels** - Items fréquemment craftés
        - :material-cog: **Machines** - Machines que vous construisez souvent
        - :material-help-circle: **À rechercher** - Items à investiguer plus tard

    !!! example "Mon setup de favoris"
        ```
        [Favoris]
        ├── En cours : Circuit Avancé, Plaque d'acier
        ├── Bases : Redstone, Fer, Or, Diamant
        ├── Energy : Capacitor, Cable, Machine Frame
        └── À craft : Quantum Ring, ME Controller
        ```

---

## Astuces de Visualisation des Recettes

### Transfert vers la Grille de Craft

=== "Transfert Basique"

    | Action | Résultat |
    |--------|----------|
    | ++plus++ | Transfère la recette vers la grille |
    | ++shift+plus++ | Transfère le maximum craftable |
    | Clic sur ++"+"++ | Bouton visuel de transfert |

    !!! warning "Prérequis"
        - La grille de craft doit être ouverte
        - Vous devez avoir les ingrédients
        - La recette doit être compatible (3x3 pour table de craft)

=== "Transfert Avancé"

    **Avec les mods de craft automatique :**

    | Mod | Fonctionnalité |
    |-----|----------------|
    | **Crafting Tweaks** | Rotation, balance, clear de la grille |
    | **Mouse Tweaks** | Glisser pour distribuer |
    | **Inventory Tweaks** | Tri automatique |

    !!! tip "Combo puissant"
        JEI + Crafting Tweaks = Craft ultra-rapide !

        1. ++r++ sur l'item voulu
        2. ++plus++ pour transférer
        3. ++shift+clic++ pour craft tout

=== "Machines"

    **Pour les recettes de machines :**

    - Le transfert fonctionne avec les machines compatibles
    - Les slots sont automatiquement reconnus
    - Certaines machines ont des intégrations spéciales

    | Machine | Support JEI |
    |---------|-------------|
    | Thermal Machines | :material-check: Complet |
    | Mekanism Machines | :material-check: Complet |
    | Create Machines | :material-check: Complet |
    | AE2 Crafting | :material-check: Via pattern |

### Visualisation Multi-Recettes

=== "Navigation"

    Quand un item a **plusieurs recettes** :

    | Navigation | Action |
    |------------|--------|
    | Flèches gauche/droite | Changer de recette |
    | Cliquer sur les flèches | Navigation visuelle |
    | ++page-up++ / ++page-down++ | Page suivante/précédente |

    !!! info "Indicateur"
        Le nombre de recettes est affiché : `1/5` signifie recette 1 sur 5.

=== "Types de Recettes"

    JEI affiche différents **types** de recettes :

    | Icône | Type | Description |
    |-------|------|-------------|
    | :material-grid: | Crafting | Table de craft |
    | :material-fire: | Smelting | Four |
    | :material-lightning-bolt: | Machine | Recette de machine |
    | :material-anvil: | Smithing | Table de forgeron |
    | :material-pot: | Brewing | Alchimie |
    | :material-campfire: | Campfire | Feu de camp |
    | :material-snowflake: | Freezing | Congélation (mods) |

=== "Onglets de Recettes"

    En haut de la fenêtre de recette, des **onglets** organisent par type :

    1. Cliquez sur un onglet pour filtrer
    2. Survolez pour voir le nom du type
    3. Les onglets dépendent des mods installés

    !!! example "Exemple avec Mekanism"
        Un minerai peut avoir des onglets pour :

        - Furnace (four vanille)
        - Enrichment Chamber
        - Crusher
        - Energized Smelter
        - etc.

---

## Addons JEI Recommandés

### Extensions Essentielles

=== "JEI Integration"

    !!! success "Indispensable"
        Ajoute le support de nombreux mods qui n'ont pas d'intégration native.

    **Fonctionnalités :**

    - Support étendu des mods populaires
    - Tooltips améliorés
    - Informations supplémentaires sur les items

    | Mod Supporté | Ajout |
    |--------------|-------|
    | Enchantments | Voir les enchantements possibles |
    | Mob Drops | Voir les drops des mobs |
    | Villager Trades | Voir les échanges villageois |

=== "Just Enough Resources (JER)"

    !!! info "Pour les ressources"
        Affiche OÙ trouver les ressources.

    **Informations ajoutées :**

    | Info | Description |
    |------|-------------|
    | **Génération minerai** | Couches Y, biomes, chances |
    | **Drops de mobs** | Avec pourcentages exacts |
    | **Loot de donjons** | Coffres, chances, quantités |
    | **Drops de plantes** | Agriculture |

    !!! example "Exemple d'utilisation"
        ++u++ sur un diamant → Voir à quelles couches il spawn,
        dans quels biomes, avec quelles chances.

=== "Just Enough Professions"

    **Pour les villageois :**

    - Voir tous les métiers possibles
    - Échanges par niveau
    - Blocs de métier requis

=== "Just Enough Effect Descriptions"

    **Pour les effets de potion :**

    - Description détaillée de chaque effet
    - Durée et puissance
    - Sources de l'effet

### Configuration des Addons

=== "JER - Configuration"

    ```
    Config → Just Enough Resources

    ☑ Show ore distribution graph
    ☑ Show mob drops percentages
    ☑ Show dungeon loot
    ☑ Show villager trades
    ☐ Show plant drops (optional)
    ```

=== "Compatibilité"

    | Addon | Forge | Fabric | Version |
    |-------|-------|--------|---------|
    | JEI Integration | :material-check: | :material-check: | 1.18+ |
    | Just Enough Resources | :material-check: | :material-close: | 1.16+ |
    | JEI Professions | :material-check: | :material-check: | 1.19+ |

---

## Pro Tips & Exemples

### Workflows Optimisés

=== "Recherche de Recette Inconnue"

    !!! tip "Méthode systématique"

    **Scénario :** Vous voulez crafter un item mais ne connaissez pas la recette.

    1. **Recherche directe**
       ```
       quantum ring
       ```

    2. **Si pas trouvé, chercher par mod**
       ```
       @ae2 ring
       ```

    3. **Chercher par fonction**
       ```
       @ae2 $wireless
       ```

    4. **Utiliser les tags**
       ```
       #ae2:cables
       ```

=== "Trouver des Alternatives"

    !!! tip "Même fonction, différents mods"

    **Scénario :** Vous voulez du cuivre mais votre mod habituel n'est pas là.

    ```
    #forge:ingots/copper
    ```

    → Trouve TOUS les lingots de cuivre de TOUS les mods !

    **Autres exemples :**

    | Besoin | Recherche |
    |--------|-----------|
    | N'importe quel fer | `#forge:ingots/iron` |
    | N'importe quelle pioche | `#forge:tools/pickaxes` |
    | N'importe quel câble énergétique | `cable $rf` ou `cable $energy` |

=== "Debug de Craft"

    !!! tip "Quand ça ne marche pas"

    **Scénario :** La recette ne fonctionne pas.

    1. **Vérifier les tags**
       - ++u++ sur chaque ingrédient
       - Vérifier qu'ils ont les bons tags

    2. **Chercher des variantes**
       ```
       @modname ingredient
       ```

    3. **Vérifier les tooltips**
       - Certains items ont des restrictions
       - Lire les tooltips avec ++shift++

### Raccourcis Mémorisés

=== "Cheatsheet Recherche"

    | Je veux... | Je tape... |
    |------------|------------|
    | Items d'un mod | `@nomdumod` |
    | Items d'une catégorie | `#forge:categorie` |
    | Items avec un mot dans tooltip | `$motclé` |
    | Items d'une couleur | `^couleur` |
    | Combinaison précise | `@mod #tag $tooltip nom` |

=== "Cheatsheet Navigation"

    | Je veux... | Je fais... |
    |------------|------------|
    | Voir comment crafter | ++r++ |
    | Voir à quoi ça sert | ++u++ |
    | Ajouter aux favoris | ++a++ ou ++ctrl+clic++ |
    | Transférer la recette | ++plus++ |
    | Retour recette précédente | ++backspace++ |
    | Effacer la recherche | ++delete++ |

=== "Cheatsheet Tags Courants"

    | Catégorie | Tags Utiles |
    |-----------|-------------|
    | **Métaux** | `#forge:ingots`, `#forge:ores`, `#forge:nuggets`, `#forge:dusts` |
    | **Craft** | `#forge:gears`, `#forge:plates`, `#forge:rods` |
    | **Blocs** | `#forge:storage_blocks`, `#forge:glass`, `#forge:stone` |
    | **Outils** | `#forge:tools`, `#forge:armors` |
    | **Food** | `#forge:crops`, `#forge:foods`, `#forge:seeds` |

### Exemples de Recherches Complexes

!!! example "Recherches Avancées en Action"

=== "Exemple 1 : Énergie"

    **Objectif :** Trouver toutes les machines générant de l'énergie

    ```
    $rf $generate
    ```
    ou
    ```
    $fe generator
    ```
    ou par mod :
    ```
    @thermal dynamo
    @mekanism generator
    @powah reactor
    ```

=== "Exemple 2 : Stockage"

    **Objectif :** Trouver des solutions de stockage

    ```
    #forge:chests
    ```
    ```
    @ae2 storage
    ```
    ```
    @refinedstorage disk
    ```
    ```
    drawer @storagedrawers
    ```

=== "Exemple 3 : Processing"

    **Objectif :** Trouver toutes les façons de traiter un minerai

    1. ++u++ sur le minerai brut
    2. Voir tous les onglets de machines
    3. Comparer les outputs (doubling, tripling, etc.)

    ```
    @mekanism #forge:ores $5x
    ```

=== "Exemple 4 : Décoration"

    **Objectif :** Trouver des blocs décoratifs assortis

    ```
    ^blue @chisel
    ```
    ```
    #forge:glass ^red
    ```
    ```
    @supplementaries decorat
    ```

---

## Configuration Recommandée

!!! settings "Paramètres JEI Optimaux"

=== "Général"

    | Paramètre | Valeur Recommandée | Raison |
    |-----------|-------------------|--------|
    | Mode recherche | `REQUIRE_PREFIX` | Plus précis |
    | Afficher tooltips | `ON` | Plus d'infos |
    | Animations | `OFF` | Meilleure perf |
    | Items par page | `9x9` ou `9x10` | Bon compromis |

=== "Recherche"

    | Paramètre | Valeur | Description |
    |-----------|--------|-------------|
    | Search mode | `ENABLED` | Toujours actif |
    | Search color | `ENABLED` | Permet ^color |
    | Search tooltip | `ENABLED` | Permet $tooltip |
    | Async search | `ON` | Recherche fluide |

=== "Avancé"

    | Paramètre | Valeur |
    |-----------|--------|
    | Low memory mode | Selon votre RAM |
    | Debug mode | OFF (sauf problèmes) |
    | Cheat mode | OFF (survie) / ON (créatif) |

---

## Résumé

!!! abstract "Les Points Clés"

    1. **++r++ et ++u++** sont vos meilleurs amis
    2. **Combinez les filtres** pour des recherches précises
    3. **Utilisez les tags** pour trouver des alternatives entre mods
    4. **Organisez vos favoris** par projet/catégorie
    5. **Installez JER** pour savoir où trouver les ressources
    6. Le **transfert ++plus++** accélère énormément le craft

!!! quote "Citation de joueur expérimenté"
    *"Je ne pourrais plus jouer à Minecraft moddé sans JEI. C'est comme essayer de coder sans documentation."*

---

*Guide complet - Mis à jour pour les versions modernes de JEI*
