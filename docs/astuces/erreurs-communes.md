# Top Erreurs de Débutants

!!! danger "Attention"
    Ces erreurs peuvent ruiner votre expérience de jeu ou vous faire perdre des heures de progression. Lisez attentivement !

---

## 1. Erreurs de Démarrage

### Ne pas lire les guides in-game

!!! warning "Erreur fréquente"
    Ignorer les **Patchouli Books** et autres guides fournis par les mods.

    Ces livres contiennent souvent des informations cruciales sur :

    - Les recettes spéciales non visibles dans JEI
    - L'ordre de progression recommandé
    - Les mécaniques uniques du mod

!!! tip "Solution"
    **Toujours** craft le guide book d'un mod dès que vous commencez à l'explorer :

    | Mod | Guide Book |
    |-----|------------|
    | Botania | Lexica Botania |
    | Blood Magic | Sanguine Scientiem |
    | Astral Sorcery | Astral Tome |
    | Thaumcraft | Thaumonomicon |
    | Immersive Engineering | Engineer's Manual |

---

### Ignorer JEI (Just Enough Items)

!!! danger "Erreur critique"
    Ne pas utiliser JEI, c'est se priver de l'outil le plus important du modded.

!!! tip "Solution"
    Apprenez ces raccourcis essentiels :

    | Touche | Action |
    |--------|--------|
    | ++r++ | Voir la recette |
    | ++u++ | Voir les utilisations |
    | ++ctrl+r++ | Recette avec bookmarks |
    | ++a++ | Ajouter aux favoris |
    | ++backspace++ | Retour en arrière |

---

### Rush les gros mods sans bases solides

!!! warning "Erreur commune"
    Vouloir faire Mekanism Fusion ou Draconic Evolution dès le début sans avoir :

    - ❌ Un système d'énergie stable
    - ❌ Du ore processing automatisé
    - ❌ Un stockage organisé
    - ❌ Des ressources en quantité

!!! tip "Solution"
    **Ordre de progression recommandé :**

    ```
    1. Base temporaire sécurisée
    2. Ferme de nourriture automatique
    3. Ore doubling (Furnace amélioré minimum)
    4. Système d'énergie basique
    5. Stockage centralisé
    6. ENSUITE les gros mods
    ```

---

## 2. Erreurs de Ressources

### Stocker sans organisation

!!! warning "Erreur très répandue"
    Des coffres partout, sans logique, sans labels.

    **Résultat :** Vous passez plus de temps à chercher qu'à jouer.

!!! tip "Solution"
    Investissez tôt dans un système de stockage :

    === "Début de partie"
        - **Storage Drawers** avec Controller
        - Labels sur chaque drawer
        - Un drawer pour chaque type de ressource commune

    === "Mid-game"
        - **Refined Storage** ou **Applied Energistics 2**
        - Crafting automatique configuré
        - Catégories dans les terminaux

    === "Organisation minimale"
        ```
        📦 Coffre Minerais
        📦 Coffre Composants Tech
        📦 Coffre Magie
        📦 Coffre Mob Drops
        📦 Coffre Building
        📦 Coffre Divers (à trier)
        ```

---

### Ne pas automatiser le ore doubling

!!! danger "Erreur coûteuse"
    Faire fondre directement les minerais = **perdre 50% ou plus** de vos ressources.

    | Méthode | Rendement |
    |---------|-----------|
    | Furnace vanilla | 1x |
    | Pulverizer/SAG Mill | 2x |
    | Mekanism (5x) | 5x |

!!! tip "Solution"
    **Priorité absolue early-game :**

    1. Craft un **SAG Mill** (Ender IO) ou **Pulverizer** (Thermal)
    2. Alimenter en énergie
    3. **Ne plus jamais** utiliser la furnace pour les minerais

    !!! note "Astuce"
        Stockez vos minerais bruts jusqu'à avoir le ore doubling !

---

### Jeter des items "inutiles"

!!! danger "Erreur irréversible"
    Jeter ou brûler des items qui semblent inutiles maintenant mais seront précieux plus tard.

    **Ne jetez JAMAIS :**

    - 🔴 Redstone (toujours utile)
    - 🟡 Blaze Rods/Powder
    - 🟢 Slime Balls
    - 🔵 Lapis Lazuli
    - ⚫ Ender Pearls
    - 🟤 Tous les mob drops rares
    - ⬜ Certaines "mauvaises herbes" (Mystical Agriculture)

!!! tip "Solution"
    ```
    Règle d'or : Si vous ne savez pas à quoi ça sert,
    cherchez dans JEI avec "U" avant de jeter !
    ```

    Créez un coffre "À identifier" pour les items inconnus.

---

## 3. Erreurs d'Énergie

### Pas assez de stockage

!!! warning "Erreur de dimensionnement"
    Produire de l'énergie sans pouvoir la stocker = énergie perdue.

    **Problèmes courants :**

    - Générateurs qui tournent dans le vide
    - Pics de consommation non gérés
    - Machines qui s'arrêtent la nuit (solaire)

!!! tip "Solution"
    **Ratio recommandé :**

    | Production | Stockage minimum |
    |------------|------------------|
    | 100 RF/t | 100k RF |
    | 1000 RF/t | 1M RF |
    | 10000 RF/t | 10M RF |

    Utilisez des **Energy Cells** (Thermal), **Energy Cubes** (Mekanism), ou **Capacitor Banks** (Ender IO).

---

### Câbles sous-dimensionnés

!!! danger "Erreur de transfert"
    Vos machines ne reçoivent pas assez d'énergie malgré une production suffisante.

    **Symptômes :**

    - Machines lentes malgré énergie disponible
    - Stockage plein mais machines vides
    - Goulot d'étranglement invisible

!!! tip "Solution"
    **Vérifiez la capacité de transfert de vos câbles :**

    | Câble | Transfert max |
    |-------|---------------|
    | Leadstone Fluxduct | 1,000 RF/t |
    | Hardened Fluxduct | 4,000 RF/t |
    | Redstone Fluxduct | 9,000 RF/t |
    | Signalum Fluxduct | 16,000 RF/t |
    | Resonant Fluxduct | 25,000 RF/t |
    | Cryo-Stabilized | **Illimité** |

    !!! note "Conseil"
        Utilisez des câbles surdimensionnés plutôt que justes - ça coûte peu et évite les problèmes.

---

### Machines sans alimentation

!!! warning "Erreur basique mais fréquente"
    Placer des machines et se demander pourquoi elles ne marchent pas.

!!! tip "Solution"
    **Checklist avant de placer une machine :**

    - [ ] La machine nécessite-t-elle de l'énergie ?
    - [ ] Quel type d'énergie ? (RF, EU, Mana, etc.)
    - [ ] Câble connecté du bon côté ?
    - [ ] Transfert suffisant ?
    - [ ] Configuration des faces (entrée/sortie) ?

---

## 4. Erreurs de Base Building

### Base trop petite

!!! warning "Erreur de planification"
    Construire une base "suffisante" qui devient vite trop petite.

    **Conséquences :**

    - Machines entassées
    - Pas de place pour agrandir
    - Câbles qui se croisent
    - Lag potentiel

!!! tip "Solution"
    **Règle : Prévoyez 3x plus grand que nécessaire**

    **Structure recommandée :**

    | Zone | Pourcentage |
    |------|-------------|
    | ZONE STOCKAGE | 25% |
    | ZONE PROCESSING | 25% |
    | ZONE ÉNERGIE | 15% |
    | ZONE MAGIE | 15% |
    | ZONE EXPANSION | 20% |

---

### Pas de chunk loading

!!! danger "Erreur critique"
    Vos machines s'arrêtent quand vous vous éloignez.

    **Affecté :**

    - ❌ Farms automatiques
    - ❌ Processing d'ores
    - ❌ Génération d'énergie
    - ❌ Crafting automatique
    - ❌ Tout ce qui est automatisé

!!! tip "Solution"
    **Options de chunk loading :**

    | Méthode | Mod | Difficulté |
    |---------|-----|------------|
    | Chunk Loader | ChickenChunks | Facile |
    | Dimensional Anchor | Immibis | Moyen |
    | FTB Chunks claim | FTB Utilities | Facile |
    | World Anchor | Railcraft | Moyen |
    | Spot Loader | - | Facile |

    !!! warning "Attention"
        Ne chargez que les chunks nécessaires ! (Voir section Optimisation)

---

### Pas de backup

!!! danger "Erreur FATALE"
    **Pas de backup = Risque de tout perdre**

    Causes de perte de monde :

    - 💥 Corruption de fichiers
    - 🔄 Mise à jour de mod ratée
    - 🐛 Bug destructeur
    - ⚡ Coupure de courant
    - 🤦 Erreur humaine

!!! tip "Solution"
    **Système de backup recommandé :**

    1. **Mod FTB Backups** ou **AromaBackup**
        - Backup automatique toutes les 30 min
        - Conservation sur 7 jours minimum

    2. **Backup manuel** avant :
        - Mise à jour de mods
        - Grosses constructions
        - Expérimentations risquées

    3. **Backup externe** :
        - Copie sur un autre disque
        - Cloud (Dropbox, Google Drive)

---

## 5. Erreurs de Combat

### Pas de Totem of Undying

!!! danger "Erreur mortelle"
    Explorer sans Totem = Mort permanente de vos items en lave/void.

!!! tip "Solution"
    **Toujours avoir un Totem en offhand :**

    - Farm de Raid pour les obtenir
    - Ou farm d'Evokers
    - Gardez-en plusieurs en inventaire

    !!! note "Priorité"
        Le Totem devrait être votre **premier objectif** avant toute exploration dangereuse.

---

### Pas de waypoint avant exploration

!!! warning "Erreur de navigation"
    Partir explorer sans marquer sa base = risque de se perdre.

    Encore pire : mourir loin sans savoir où.

!!! tip "Solution"
    **Utilisez les waypoints de votre minimap :**

    | Waypoints essentiels | Couleur suggérée |
    |---------------------|------------------|
    | Base principale | 🟢 Vert |
    | Portail Nether | 🔴 Rouge |
    | Portail End | 🟣 Violet |
    | Spots de farming | 🟡 Jaune |
    | Points de mort | ⚫ Noir |

    ```
    Règle : Nouveau lieu intéressant = Nouveau waypoint
    ```

---

### Sous-estimer les boss moddés

!!! danger "Erreur fatale"
    Les boss moddés sont **BEAUCOUP** plus difficiles que les boss vanilla.

    | Boss | Difficulté vs Ender Dragon |
    |------|---------------------------|
    | Twilight Forest Bosses | 2-5x |
    | Ender Dragon (Draconic) | 10x |
    | Chaos Guardian | 50x+ |
    | Gaia Guardian (Botania) | 5-10x |
    | Wither (moddé) | 3-5x |

!!! tip "Solution"
    **Préparation obligatoire avant boss moddé :**

    - [ ] Armure complète enchantée/moddée
    - [ ] Arme appropriée au boss
    - [ ] Potions (Régénération, Force, Résistance)
    - [ ] Totems (plusieurs)
    - [ ] Nourriture saturante
    - [ ] Waypoint posé
    - [ ] Backup du monde
    - [ ] Recherche sur le wiki du mod

---

## 6. Erreurs d'Optimisation

### Trop de chunk loaders

!!! danger "Erreur de performance"
    Chaque chunk chargé = ressources serveur/client utilisées.

    **Impact :**

    - 📉 Baisse de FPS
    - 🐌 Lag serveur
    - 💾 Utilisation mémoire excessive
    - ⏰ Temps de sauvegarde rallongé

!!! tip "Solution"
    **Optimisation des chunks chargés :**

    1. **Centralisez** vos opérations
        - Une grosse base > plusieurs petites

    2. **Minimisez** la zone chargée
        - 1 chunk pour une farm compacte
        - Pas besoin de charger toute la base

    3. **Utilisez les bons outils**
        - Spot Loader pour un seul block
        - Chunk Loader pour une zone

    ```
    Règle : Maximum 9-16 chunks chargés en solo
    ```

---

### Farms non optimisées qui lag

!!! warning "Erreur technique"
    Une farm mal conçue peut ruiner les performances.

    **Causes de lag :**

    - 🐄 Trop d'entités (mobs, items)
    - 🔄 Trop de tile entities (coffres, hoppers)
    - ⚡ Redstone complexe avec updates constants
    - 💧 Eau qui coule sur grande surface
    - 🌱 Trop de crops qui tick

!!! tip "Solution"
    **Bonnes pratiques :**

    | Problème | Solution |
    |----------|----------|
    | Items au sol | Hoppers/Vacuum rapides |
    | Trop de mobs | Kill instantané, cap de spawn |
    | Hoppers lents | Pipes moddées (Ender IO, Mekanism) |
    | Redstone | Utiliser des mods (Project Red, RS) |
    | Grande farm | Diviser en sections |

---

### Pas de nettoyage des entities

!!! danger "Erreur cumulative"
    Les entities s'accumulent et causent du lag progressif.

    **Entities problématiques :**

    - Items au sol non ramassés
    - Mobs dans des zones non prévues
    - Minecarts/boats abandonnés
    - Flèches, XP orbs, etc.

!!! tip "Solution"
    **Nettoyage régulier :**

    1. **Commande admin** (si disponible) :
        ```
        /kill @e[type=item]
        /kill @e[type=experience_orb]
        ```

    2. **Mods de nettoyage** :
        - ClearLag
        - Mob Cleaner

    3. **Prévention** :
        - Trash cans pour items indésirables
        - Void pipes pour overflow
        - Mob caps sur les spawners

---

## Récapitulatif

!!! abstract "Les 10 Commandements du Modded"
    1. **Tu liras** les guides in-game
    2. **Tu maîtriseras** JEI
    3. **Tu progresseras** étape par étape
    4. **Tu organiseras** ton stockage
    5. **Tu doubleras** tes minerais (minimum)
    6. **Tu garderas** tous les items
    7. **Tu dimensionneras** ton énergie correctement
    8. **Tu prévoiras** grand pour ta base
    9. **Tu chargeras** tes chunks
    10. **Tu sauvegarderas** régulièrement

!!! success "Devise du joueur modded"
    **"Prépare, planifie, automatise, optimise"**
