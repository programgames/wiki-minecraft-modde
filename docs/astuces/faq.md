# :material-frequently-asked-questions: FAQ - Questions Fréquentes

!!! tip "Bienvenue dans la FAQ"
    Retrouvez ici les réponses aux questions les plus courantes sur les modpacks. Utilisez ++ctrl+f++ pour rechercher rapidement.

---

## :material-rocket-launch: Démarrage

??? question "Par quel mod commencer ?"
    **Cela dépend du modpack**, mais voici un ordre classique :

    1. **Tinkers' Construct** - Outils améliorables sans enchantements
    2. **Thermal Series** - Machines simples et polyvalentes
    3. **Mekanism** - Production d'énergie efficace

    :material-lightbulb: **Conseil** : Suivez les quêtes du modpack si disponibles !

    [:octicons-arrow-right-24: Guide de progression](../building/index.md)

??? question "Comment trouver des recettes ?"
    Utilisez **JEI** (Just Enough Items) :

    | Touche | Action |
    |--------|--------|
    | ++r++ | Voir la recette d'un item |
    | ++u++ | Voir les utilisations d'un item |
    | ++ctrl+f++ | Rechercher dans JEI |

    :material-magnify: Tapez `@modname` pour filtrer par mod (ex: `@mekanism`)

??? question "Pourquoi JEI ne montre pas certaines recettes ?"
    Plusieurs raisons possibles :

    - :material-close: **Recette cachée** - Certains modpacks masquent des recettes avancées
    - :material-close: **Mauvaise machine** - La recette nécessite une machine spécifique
    - :material-close: **Mode de craft** - Essayez de regarder avec ++u++ sur la machine

    !!! tip "Astuce"
        Certaines recettes apparaissent uniquement après avoir débloqué certains achievements.

---

## :material-lightning-bolt: Énergie

??? question "RF et FE c'est pareil ?"
    **Oui !** RF (Redstone Flux) et FE (Forge Energy) sont **interchangeables**.

    | Nom | Origine | Compatibilité |
    |-----|---------|---------------|
    | RF | Thermal Expansion | Universel |
    | FE | Forge | Universel |
    | EU | IC2 | Nécessite conversion |

    :material-check: Tous les mods modernes utilisent FE/RF de manière transparente.

    [:octicons-arrow-right-24: Guide Énergie](../energie/index.md)

??? question "Pourquoi mes machines ne fonctionnent pas ?"
    Vérifiez ces points :

    - [x] **Énergie connectée** - Câble branché côté entrée
    - [x] **Assez d'énergie** - Vérifiez la jauge de la machine
    - [x] **Items en entrée** - Slot d'input correct
    - [x] **Slot de sortie libre** - Output non plein
    - [x] **Redstone** - Certaines machines sont sensibles au redstone

    !!! warning "Erreur courante"
        Les machines ont souvent des **côtés configurables**. Vérifiez la configuration I/O !

??? question "Quel générateur utiliser en early ?"

    | Générateur | Mod | RF/t | Difficulté |
    |------------|-----|------|------------|
    | :material-fire: Stirling Generator | Ender IO | 40-80 | :material-star: |
    | :material-water: Water Wheel | Immersive Eng. | 30 | :material-star: |
    | :material-barrel: Culinary Generator | Culinary | 32-64 | :material-star: |
    | :material-gas-cylinder: Heat Generator | Mekanism | 100+ | :material-star::material-star: |

    [:octicons-arrow-right-24: Comparatif générateurs](../energie/index.md)

---

## :material-archive: Stockage

??? question "AE2 ou Refined Storage ?"

    | Critère | AE2 | Refined Storage |
    |---------|-----|-----------------|
    | **Difficulté** | :material-star::material-star::material-star: | :material-star::material-star: |
    | **Ressources** | Channels limités | Illimité |
    | **Performance** | Meilleure | Bonne |
    | **Flexibilité** | Très haute | Haute |

    !!! tip "Recommandation"
        - **Débutant** → Refined Storage (plus simple)
        - **Expérimenté** → AE2 (plus optimisé)

    [:octicons-arrow-right-24: Guide Stockage](../stockage/index.md)

??? question "Pourquoi mon réseau ME ne marche plus ?"
    Diagnostic rapide :

    1. :material-lightning-bolt: **Énergie** - Vérifiez l'Energy Acceptor
    2. :material-numeric-8: **Channels** - Maximum 8 par câble normal
    3. :material-connection: **Connexion** - Pas de boucle dans le réseau
    4. :material-chip: **Contrôleur** - Nécessaire pour grands réseaux

    ```
    Erreur courante : Trop d'appareils sur un seul câble
    Solution : Utilisez des Dense Cables (32 channels)
    ```

??? question "Comment organiser mon stockage ?"
    Structure recommandée :

    ```
    📦 Stockage Principal
    ├── 🔧 Composants & Machines
    ├── ⛏️ Minerais & Lingots
    ├── 🌾 Farming & Nourriture
    ├── 🧪 Fluides
    └── 📚 Divers
    ```

    !!! tip "Conseil pro"
        Utilisez des **Storage Drawers** pour les items en grande quantité (cobble, dirt...) et ME/RS pour le reste.

---

## :material-cog-sync: Automation

??? question "Mes items ne se déplacent pas, pourquoi ?"
    Checklist de dépannage :

    - [ ] **Direction du flux** - Vérifiez entrée/sortie
    - [ ] **Alimentation** - Certains conduits nécessitent de l'énergie
    - [ ] **Configuration** - Mode Extract activé ?
    - [ ] **Filtres** - Aucun filtre bloquant ?

    !!! example "Solutions par mod"
        - **Thermal** : Servo nécessaire pour extraire
        - **Mekanism** : Configurez le mode Pull/Push
        - **Ender IO** : Vérifiez les filtres de conduit

??? question "Comment filtrer les items ?"

    | Mod | Méthode |
    |-----|---------|
    | **Thermal** | Servo + Filter |
    | **Mekanism** | Logistical Sorter |
    | **Ender IO** | Item Filter sur conduit |
    | **AE2** | ME Interface + Export Bus |

    :material-lightbulb: Les **tags** permettent de filtrer par catégorie (tous les minerais, tous les logs...)

??? question "Comment auto-crafter ?"
    Options par complexité :

    1. **Simple** : RFTools Crafter / Thermal Sequential Fabricator
    2. **Intermédiaire** : ME Crafting Terminal (AE2)
    3. **Avancé** : Create Mechanical Crafter

    !!! tip "Conseil"
        Pour les recettes complexes, AE2/RS avec patterns encodés reste la meilleure solution.

---

## :material-sword-cross: Combat & Boss

??? question "Je meurs tout le temps, que faire ?"
    Progression défensive recommandée :

    | Étape | Équipement | Protection |
    |-------|------------|------------|
    | 1 | Armure fer | :material-shield: 15 |
    | 2 | Armure diamant | :material-shield: 20 |
    | 3 | Armure enchantée | :material-shield: 20+ |
    | 4 | Armure modée | :material-shield: Variable |

    !!! warning "Points critiques"
        - **Totem of Undying** : Gardez-en toujours un !
        - **Golden Apples** : Craftez-en d'avance
        - **Potions** : Régénération + Force

    [:octicons-arrow-right-24: Guide Combat](../combat/index.md)

??? question "Comment battre le Wither facilement ?"
    Méthodes éprouvées :

    1. **Méthode Bedrock** : Spawner sous le plafond du Nether (Y=127)
    2. **Méthode Tank** : Armure Mekanism + Jetpack
    3. **Méthode Cage** : Obsidienne + Smite V

    !!! tip "Astuce"
        Certains mods ajoutent des **Wither Cages** automatiques (Industrial Foregoing).

??? question "Quelle armure utiliser ?"
    Top armures par mod :

    | Armure | Mod | Protection | Bonus |
    |--------|-----|------------|-------|
    | MekaSuit | Mekanism | :material-infinity: | Vol, Vision, Tools |
    | Draconic | Draconic Evo. | :material-infinity: | Bouclier énergie |
    | Dark Steel | Ender IO | Haute | Upgrades modulaires |
    | Manasteel | Botania | Moyenne | Mana regen |

---

## :material-speedometer: Performance

??? question "Mon jeu lag, que faire ?"
    Optimisations par ordre de priorité :

    1. **Allouer plus de RAM** (voir question suivante)
    2. **Réduire render distance** (8-12 chunks max)
    3. **Installer mods de performance**
    4. **Désactiver animations inutiles**

    !!! danger "À éviter"
        - Trop de machines chunk-loaded
        - Réseaux de stockage mal optimisés
        - Mob farms sans limite d'entités

    [:octicons-arrow-right-24: Mods QOL & Performance](../qol/index.md)

??? question "Combien de RAM allouer ?"

    | Type de pack | RAM recommandée |
    |--------------|-----------------|
    | Petit (50 mods) | 4-6 GB |
    | Moyen (150 mods) | 6-8 GB |
    | Gros (300+ mods) | 8-12 GB |

    !!! warning "Attention"
        **Plus n'est pas toujours mieux !** Au-delà de 12 GB, le garbage collector peut causer des freezes.

    ```
    Arguments JVM recommandés :
    -Xms4G -Xmx8G -XX:+UseG1GC
    ```

??? question "Quels mods de performance installer ?"

    | Mod | Effet | Version |
    |-----|-------|---------|
    | **Sodium/Rubidium** | FPS x2-3 | 1.16+ |
    | **Starlight** | Lighting optimisé | 1.17+ |
    | **FerriteCore** | RAM -30% | 1.16+ |
    | **Entity Culling** | Entités optimisées | 1.16+ |

    [:octicons-arrow-right-24: Liste complète](../qol/index.md)

---

## :material-dots-horizontal: Divers

??? question "Comment transporter des spawners ?"
    Options disponibles :

    | Méthode | Mod | Difficulté |
    |---------|-----|------------|
    | Cardboard Box | Mekanism | :material-star: |
    | Diamond Dolly | Carrier | :material-star: |
    | Silk Touch Pick | Certains packs | :material-star::material-star: |
    | Soul Vial | Ender IO | Mob seulement |

    !!! tip "Alternative"
        **Mob Duplicator** (Industrial Foregoing) peut reproduire n'importe quel mob sans spawner !

??? question "Comment avoir du vol infini ?"
    Solutions par progression :

    | Item | Mod | Énergie | Vitesse |
    |------|-----|---------|---------|
    | Jetpack | Mekanism/SF | Oui | Moyenne |
    | Angel Ring | Extra Utils | Non | Créative |
    | MekaSuit | Mekanism | Oui | Très rapide |
    | Flight Tiara | Botania | Mana | Moyenne |
    | Supreme Jetpack | Iron Jetpacks | Oui | Variable |

    [:octicons-arrow-right-24: Guide Déplacement](../deplacement/index.md)

??? question "Où trouver [ressource rare] ?"
    Ressources problématiques courantes :

    | Ressource | Localisation |
    |-----------|--------------|
    | **Certus Quartz** | Y 0-40, veines moyennes |
    | **Draconium** | End, minage ou Chaos Guardian |
    | **Iridium** | End, très rare ou craft |
    | **Nether Stars** | Wither ou Mob Farm |
    | **Blaze Rods** | Forteresse Nether |

    !!! tip "Conseil"
        Utilisez **JEI** avec ++u++ sur la ressource pour voir toutes les méthodes d'obtention !

    [:octicons-arrow-right-24: Guide Farming](../farming/index.md)

---

!!! question "Votre question n'est pas ici ?"
    N'hésitez pas à consulter les guides détaillés ou à poser votre question sur le Discord de la communauté !
