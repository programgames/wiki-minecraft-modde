# Optimisation et Performances

<div class="grid cards" markdown>

-   :zap: **Graphiques**

    ---

    Rubidium, shaders légers et corrections visuelles pour des FPS stables.

    [:octicons-arrow-right-24: Voir les mods](#graphiques)

-   :rocket: **Performance**

    ---

    Clumps, FastFurnace, AI Improvements pour réduire le lag serveur et client.

    [:octicons-arrow-right-24: Voir les mods](#performance-generale)

-   :globe_with_meridians: **Réseau**

    ---

    Connectivity, Packet Fixer pour des connexions stables en multijoueur.

    [:octicons-arrow-right-24: Voir les mods](#reseau-et-serveur)

-   :tools: **Debug & Diagnostic**

    ---

    Spark, Observable, BetterF3 pour identifier et résoudre les problèmes de lag.

    [:octicons-arrow-right-24: Voir les mods](#debug-et-diagnostic)

</div>

!!! tip "Checklist Optimisation de Base"
    - [ ] Installer **Rubidium** (ou Sodium) pour le rendu
    - [ ] Ajouter **Clumps** pour regrouper les XP orbs
    - [ ] Configurer la **distance de rendu** (8-12 chunks recommandé)
    - [ ] Installer **Spark** pour le diagnostic de performance
    - [ ] Allouer la bonne quantité de **RAM** (voir section JVM)
    - [ ] Désactiver les **effets visuels non essentiels**

## Guides Généraux

!!! abstract "Ressources Communautaires"
    - [Optimiser son client/serveur pour les perfs (Reddit)](https://www.reddit.com/r/feedthebeast/comments/1fp7u65/lets_talk_about_modpack_optimization/)
    - [Guide amélioration FPS (Reddit)](https://www.reddit.com/r/feedthebeast/comments/wy2s4b/the_ultimate_updated_guide_on_increasing_fps_and/)
    - [Rubidium vs Sodium (Reddit)](https://www.reddit.com/r/feedthebeast/comments/wbers1/rubidium_sodium_etc_which_should_i_use_and_whats/)

## Comparaison des Mods

| Mod | Catégorie | Effet | Gain Performance | Difficulté |
|-----|:---------:|-------|:----------------:|:----------:|
| [Rubidium](https://www.curseforge.com/minecraft/mc-mods/rubidium) | Graphiques | Refonte du rendu | ----- | - |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | Entités | Regroupe XP orbs | ---- | - |
| [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements) | Serveur | Optimise IA mobs | ---- | - |
| [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fastfurnace) | Processing | Accélère fours | --- | - |
| [Farsight](https://www.curseforge.com/minecraft/mc-mods/farsight) | Rendu | Cache chunks distants | --- | - |
| [Connectivity](https://www.curseforge.com/minecraft/mc-mods/connectivity) | Réseau | Stabilise connexion | --- | - |
| [Spark](https://www.curseforge.com/minecraft/mc-mods/spark) | Debug | Profiling complet | N/A (diagnostic) | -- |

---

## Mods de Performance Recommandés

<a id="graphiques"></a>
=== "Graphiques"

    !!! success "Mods Essentiels"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Rubidium](https://www.curseforge.com/minecraft/mc-mods/rubidium) | Port de Sodium pour Forge - refonte complète du rendu | :zap: RUSH |
    | [Makeup Ultra Fast Shader](https://www.curseforge.com/minecraft/shaders/makeup-ultra-fast-shader) | Shaders ultra légers pour PC modestes | - |
    | [FlickerFix](https://www.curseforge.com/minecraft/mc-mods/flickerfix) | Corrige le scintillement des textures | - |

    !!! tip "Rubidium vs Sodium"
        - **Rubidium** = Port Forge de Sodium (utiliser sur Forge/NeoForge)
        - **Sodium** = Version originale Fabric
        - Les deux offrent les mêmes gains (~200-300% FPS en moyenne)
        - Vérifier la compatibilité avec les autres mods graphiques

=== "Rendu et Chunks"

    !!! success "Mods de Rendu"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Farsight](https://www.curseforge.com/minecraft/mc-mods/farsight) | Garde les chunks distants en mémoire | - |
    | [Fast Leaf Decay](https://www.curseforge.com/minecraft/mc-mods/fast-leaf-decay) | Les feuilles disparaissent rapidement | - |

    !!! warning "Attention"
        - **Farsight** augmente la RAM utilisée
        - Réduire la distance de rendu si le PC a moins de 8GB RAM
        - **Fast Leaf Decay** peut causer du lag temporaire avec beaucoup d'arbres

<a id="performance-generale"></a>
=== "Performance Générale"

    !!! success "Optimisations Serveur/Client"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | Regroupe les XP orbs (essentiel pour mob farms) | :zap: RUSH |
    | [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fastfurnace) | Optimise les opérations des fours | - |
    | [FastSuite](https://www.curseforge.com/minecraft/mc-mods/fastsuite) | Optimise les lookups de recettes | - |
    | [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements) | Réduit le lag de l'IA des mobs | :zap: RUSH |
    | [Get It Together, Drops!](https://www.curseforge.com/minecraft/mc-mods/get-it-together-drops) | Regroupe les drops au sol | - |

    !!! example "Impact sur les Mob Farms"
        Une mob farm sans optimisation peut générer 500+ entités XP orbs.
        Avec **Clumps** + **Get It Together, Drops!** = ~50 entités seulement!

<a id="reseau-et-serveur"></a>
=== "Réseau et Serveur"

    !!! success "Stabilité Multijoueur"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Connectivity](https://www.curseforge.com/minecraft/mc-mods/connectivity) | Améliore la connexion client/serveur | - |
    | [Packet Fixer](https://www.curseforge.com/minecraft/mc-mods/packet-fixer) | Corrige les problèmes de paquets réseau | - |
    | [Login Protection](https://www.curseforge.com/minecraft/mc-mods/login-protection) | Protège les joueurs pendant le chargement | - |

    !!! tip "Pour les Serveurs"
        - **Connectivity** est essentiel si tu as des déconnexions fréquentes
        - **Login Protection** empêche les morts pendant le chargement du monde
        - Combiner avec des **plugins papier/spigot** côté serveur pour plus d'effet

<a id="debug-et-diagnostic"></a>
=== "Debug et Diagnostic"

    !!! success "Outils de Diagnostic"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Spark](https://www.curseforge.com/minecraft/mc-mods/spark) | Profiler de performance complet | :zap: RUSH |
    | [Observable](https://www.curseforge.com/minecraft/mc-mods/observable) | Visualise ce qui cause le lag | - |
    | [BetterF3](https://www.curseforge.com/minecraft/mc-mods/betterf3) | Écran debug amélioré et coloré | - |

    !!! tip "Utiliser Spark"
        1. `/spark profiler start` - Démarre le profiling
        2. Joue pendant 1-2 minutes normalement
        3. `/spark profiler stop` - Génère un rapport
        4. Analyse le rapport pour identifier les sources de lag

    !!! tip "Utiliser Observable"
        - Appuie sur la touche configurée pour voir les **tick times** de chaque bloc/entité
        - Les zones **rouges** = sources de lag majeures
        - Utile pour identifier les machines/mobs problématiques

=== "Stabilité"

    !!! success "Prévention des Crashes"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Crash Assistant](https://www.curseforge.com/minecraft/mc-mods/crash-assistant) | Aide à comprendre les crashes | - |
    | [Crash Utilities](https://www.curseforge.com/minecraft/mc-mods/crash-utilities) | Outils pour débugger les crashes | - |
    | [Better Compatibility Checker](https://www.curseforge.com/minecraft/mc-mods/better-compatibility-checker) | Vérifie la compatibilité des mods | - |
    | [Attribute Fix](https://www.curseforge.com/minecraft/mc-mods/attributefix) | Corrige les limites d'attributs vanilla | - |

    !!! warning "En cas de Crash"
        1. Lis le **crash report** (dans le dossier `crash-reports/`)
        2. Cherche la ligne `Caused by:` pour la cause principale
        3. Utilise **Crash Assistant** pour une analyse simplifiée
        4. Vérifie les mises à jour des mods concernés

=== "Compatibilité"

    !!! success "Unification et APIs"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Almost Unified](https://www.curseforge.com/minecraft/mc-mods/almost-unified) | Unifie les items similaires (copper, etc.) | - |
    | [Common Capabilities](https://www.curseforge.com/minecraft/mc-mods/common-capabilities) | API commune entre mods tech | - |

    !!! tip "Almost Unified"
        - Empêche les doublons d'items (ex: 5 types de copper ingot)
        - Réduit le chaos dans JEI
        - Améliore les crafts multi-mods

=== "Sauvegarde"

    !!! success "Protection des Données"

    | Mod | Description | Priorité |
    |-----|-------------|:--------:|
    | [Simple Backups](https://www.curseforge.com/minecraft/mc-mods/simple-backups) | Backups automatiques du monde | :zap: RUSH |

    !!! danger "Toujours faire des backups!"
        - Configure **Simple Backups** pour des sauvegardes toutes les 30-60 minutes
        - Garde au moins **5 backups** récents
        - Vérifie que les backups fonctionnent AVANT d'en avoir besoin

---

## Configuration JVM et RAM

!!! abstract "Arguments JVM Recommandés"

    Pour **8GB+ de RAM**, utilise ces arguments dans ton launcher :

    ```
    -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200
    -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC
    -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40
    -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20
    -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4
    -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90
    -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32
    -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1
    ```

=== "Allocation RAM"

    !!! tip "Guide d'Allocation"

    | RAM Totale PC | Allocation Minecraft | Notes |
    |:-------------:|:--------------------:|-------|
    | 8 GB | 4-5 GB | Minimum pour modpacks moyens |
    | 16 GB | 6-8 GB | Recommandé pour la plupart |
    | 32 GB | 8-12 GB | Gros modpacks (ATM, Ragnamod) |
    | 64 GB+ | 12-16 GB | Maximum utile |

    !!! warning "Attention"
        - **Ne jamais allouer plus de 12-16GB** - le garbage collector devient inefficace
        - **Laisser 4GB minimum** pour Windows/autres applications
        - Plus de RAM = pauses GC plus longues si mal configuré

=== "Par Type de Modpack"

    !!! example "Recommandations par Modpack"

    | Modpack | RAM Recommandée | Notes |
    |---------|:---------------:|-------|
    | Vanilla + quelques mods | 3-4 GB | Suffisant pour <50 mods |
    | Modpack moyen | 6-8 GB | 100-200 mods |
    | ATM (All The Mods) | 8-10 GB | 300+ mods, très gourmand |
    | Ragnamod | 8-10 GB | Similaire à ATM |
    | Serveur dédié | +2 GB | Ajouter par rapport au client |

=== "Troubleshooting"

    !!! danger "Problèmes Courants"

    **Lag spikes réguliers (toutes les X secondes)**
    :   Garbage collection trop agressive. Augmente la RAM ou utilise les arguments G1GC ci-dessus.

    **Out of Memory Error**
    :   Pas assez de RAM allouée. Augmente dans le launcher.

    **Jeu qui freeze puis reprend**
    :   Garbage collection. Vérifie les arguments JVM et réduis les paramètres graphiques.

    **FPS bas constant**
    :   Pas lié à la RAM. Installe Rubidium et réduis la distance de rendu.

---

## Conseils et Astuces

!!! tip "Optimisation In-Game"
    - **Réduire la distance de rendu** à 8-12 chunks (plutôt que 32)
    - **Désactiver les particules** ou les mettre en "minimal"
    - **Limiter les entités** visibles dans les options graphiques
    - **Désactiver le VSync** si tu as des FPS stables au-dessus de 60
    - **Mode plein écran** plutôt que fenêtré pour de meilleurs FPS

!!! example "Sources d'Inspiration"
    Regarde les modpacks **ATM (All The Mods)** et **Ragnamod** pour les mods QOL et optimisations bien sélectionnés. Ces modpacks sont testés avec des centaines de mods et incluent les meilleurs mods de performance.

!!! warning "Chunk Loading"
    - Utilise les **chunk loaders** avec modération
    - Chaque chunk chargé = plus de calculs serveur
    - Préfère des designs compacts plutôt que des bases étendues
    - Décharge les zones non utilisées régulièrement

!!! abstract "Priorités d'Installation"

    **Tier 1 - Indispensables** :zap:

    - Rubidium (FPS)
    - Clumps (entités)
    - AI Improvements (serveur)
    - Spark (diagnostic)
    - Simple Backups (sécurité)

    **Tier 2 - Fortement Recommandés** -

    - FastFurnace / FastSuite
    - Connectivity
    - BetterF3
    - Almost Unified

    **Tier 3 - Situationnels**

    - Farsight (si tu veux voir loin)
    - Observable (pour debug avancé)
    - Autres mods de stabilité
