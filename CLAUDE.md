# Wiki Minecraft Moddé - Contexte pour l'IA

## Description du projet

Wiki MkDocs (Material theme) pour documenter les mods Minecraft, leurs objets importants, addons, tips et guides.
Destiné aux joueurs de modpacks "expert" (ATM, FTB, etc.).

## Structure du projet

```
fandom/
├── mkdocs.yml              # Configuration MkDocs + Material theme
├── CLAUDE.md               # Ce fichier (contexte IA)
├── .gitignore              # Fichiers ignorés par git
├── docs/
│   ├── index.md            # Page d'accueil
│   ├── tags.md             # Page des tags
│   ├── astuces/
│   │   ├── index.md        # Astuces générales
│   │   ├── getting-started.md
│   │   ├── early-game.md
│   │   ├── mid-game.md
│   │   ├── late-game.md
│   │   ├── automation.md
│   │   ├── base-building.md
│   │   ├── boss-prep.md
│   │   ├── dimensions.md
│   │   ├── enchantements.md
│   │   ├── energie.md
│   │   ├── erreurs-communes.md
│   │   ├── faq.md
│   │   ├── farming.md
│   │   ├── gear-progression.md
│   │   ├── glossaire.md
│   │   ├── jei-mastery.md
│   │   ├── keybinds.md
│   │   ├── optimisation.md
│   │   └── organisation-coffres.md
│   ├── magie/
│   │   └── index.md        # Ars Nouveau, Blood Magic, Botania, Occultism...
│   ├── technologie/
│   │   └── index.md        # AE2, Create, Mekanism, Thermal, PneumaticCraft...
│   ├── utilitaire/
│   │   └── index.md        # Apotheosis, Cyclic, Modular Routers, RFTools...
│   ├── farming/
│   │   └── index.md        # Mystical Agriculture, Productive Bees, Farmer's Delight...
│   ├── combat/
│   │   └── index.md        # Tinker's Construct, Silent Gear, Apotheosis, Iron's Spells...
│   ├── building/
│   │   └── index.md        # Chipped, Building Gadgets, Construction Wand...
│   ├── stockage/
│   │   └── index.md        # Functional Storage, Sophisticated Backpacks...
│   ├── deplacement/
│   │   └── index.md        # Waystones, Jetpacks, Gliders...
│   ├── energie/
│   │   └── index.md        # Powah, Flux Networks, générateurs...
│   ├── mob-farm/
│   │   └── index.md        # Apotheosis spawners, Mob Grinding Utils, HNN...
│   └── qol/
│       └── index.md        # Mods QOL, performance, UI
```

## Template de page par catégorie

Chaque page de catégorie utilise les composants Material :

```markdown
# Nom de la Catégorie

<div class="grid cards" markdown>
-   :icon: **Mod Principal**
    ---
    Description courte
    [:octicons-arrow-right-24: Découvrir](#anchor)
</div>

## Comparaison Rapide
| Mod | Difficulté | Phase | Recommandé pour |
|-----|:----------:|:-----:|-----------------|

## Progression Recommandée
!!! tip "Early Game"
!!! note "Mid Game"
!!! success "Late Game"

---

## Nom du Mod
[CurseForge](url) | [Wiki](url)

### Addons
- [Addon](url) : Description

=== "Tips"
    !!! tip "Titre"
        Contenu

=== "Objets Importants"
    | Objet | Priorité | Description |

=== "Guides"
    - [Guide](url)
```

## Conventions

### Marqueurs de priorité
- `:zap: **[RUSH]**` : À faire le plus tôt possible
- `[EARLY]` : Early game
- `[MID]` : Mid game
- `[LATE]` : Late game

### Format des ratings
- Utiliser `/5` au lieu d'emojis étoiles (ex: `3/5`)

### Liens
- Liens CurseForge préférés pour les URLs de mods
- Format : `[Nom](url)`

## Extensions MkDocs activées

- `pymdownx.tabbed` : Onglets avec `=== "Titre"`
- `pymdownx.details` : Sections pliables avec `??? note "Titre"`
- `admonition` : Blocs !!! tip/warning/note/success/danger/example
- `pymdownx.keys` : Raccourcis clavier avec `++ctrl+f++`
- `attr_list` + `md_in_html` : Grilles de cartes
- `pymdownx.superfences` : Blocs de code avancés

## Commandes mkdocs

```bash
# Serveur de développement
mkdocs serve

# Build du site
mkdocs build

# Déployer sur GitHub Pages
mkdocs gh-deploy
```

## Mise à jour du wiki

Lors de l'ajout d'un nouveau mod :
1. Identifier sa catégorie principale
2. L'ajouter dans le fichier de la catégorie correspondante
3. Respecter l'ordre alphabétique dans les sections
4. Remplir : Quick Start, Addons, Tips, Objets Importants, Guides
5. Vérifier les liens CurseForge

## Ressources utiles

### Guides officiels
- [AE2 Players Guide](https://guide.appliedenergistics.org/)
- [Mekanism Wiki](https://wiki.aidancbrady.com/wiki/)
- [Thermal Docs](https://teamcofh.com/docs/)
- [Create Wiki](https://create.fandom.com/wiki/)
- [Ars.Guide](https://ars.guide/)
- [Mystical Agriculture Wiki](https://blakesmods.com/wiki/mysticalagriculture/)
- [Productive Bees Docs](https://productive-bees.readthedocs.io/)
- [Iron's Spells Wiki](https://iron.wiki/)

### Communauté
- [All The Guides - ATM9](https://allthemods.github.io/alltheguides/atm9/)
- [r/feedthebeast](https://www.reddit.com/r/feedthebeast/)
- [r/allthemods](https://www.reddit.com/r/allthemods/)
- [CurseForge](https://www.curseforge.com/minecraft/mc-mods)

## Dernière mise à jour

- **Date** : 2026-03-19
- **Modifications** :
  - Nettoyage du repo (suppression fichiers sources obsolètes)
  - Intégration complète des astuces dans le wiki
  - Ajout de nombreux mods : Refined Storage, NuclearCraft, Extreme Reactors, Deep Resonance, SFM, Productive Trees, Aquaculture 2, Eidolon, etc.
  - Enrichissement des objets détaillés pour PneumaticCraft, Nature's Aura, EvilCraft
  - Correction de l'extension pymdownx.keys pour les raccourcis clavier
  - Theme changé vers light (default) avec couleurs teal/cyan
- **Catégories** : Magie, Technologie, Utilitaire, Farming, Combat, Stockage, Énergie, Mob Farm, Building, Déplacement, QOL, Astuces
