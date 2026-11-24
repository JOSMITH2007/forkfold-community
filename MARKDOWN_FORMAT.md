# Forkfold Data & Obsidian Markdown Format

Forkfold is built on open, portable file formats so you never experience vendor lock-in:
1. **Obsidian / Local Markdown Sync (`.md`)** — continuous two-way/local sync to any folder on Android.
2. **Portable Recipe JSON (`.json`)** — lossless single-recipe and cookbook backup/sharing format.

---

## 1. Obsidian Markdown Format (`.md`)

When you connect a local folder in **Forkfold → Settings → Local Folder / Markdown Sync** (via Android Storage Access Framework), recipes are stored as clean `.md` files with YAML frontmatter — ready for **Obsidian**, **Syncthing**, **Nextcloud**, or **FolderSync**.

```markdown
---
title: Klassische Lasagne al Forno
category: Hauptspeise
subCategory: Auflauf & Pasta
prepTime: 45 Min
servings: 4
tags:
  - italienisch
  - auflauf
  - mealprep
  - deftig
isFavorite: true
rating: 5.0
---

# Klassische Lasagne al Forno

> Deftige Lasagne mit langsam geschmorter Bolognese, feiner Béchamelsauce und goldbrauner Kruste.

## Zutaten
- 500 g Rinderhackfleisch
- 1 Stück Zwiebel (fein gewürfelt)
- 2 Zehen Knoblauch (gehackt)
- 800 g stückige Tomaten
- 2 EL Tomatenmark
- 250 g Lasagneplatten
- 50 g Butter
- 50 g Weizenmehl
- 500 ml Milch
- 200 g geriebener Mozzarella
- 1 Prise Muskatnuss
- Salz und Pfeffer

## Zubereitung
1. Den Backofen auf 180 °C Ober-/Unterhitze vorheizen.
2. Zwiebel und Knoblauch in etwas Olivenöl anschwitzen, Hackfleisch dazugeben und kräftig anbraten.
3. Tomatenmark und stückige Tomaten einrühren, mit Salz und Pfeffer würzen und 20 Minuten sanft köcheln lassen.
4. Für die Béchamel die Butter schmelzen, Mehl einrühren und unter ständigem Rühren mit Milch aufgießen, bis eine sämige Sauce entsteht. Mit Muskat abschmecken.
5. In einer Auflaufform abwechselnd Bolognese, Lasagneplatten und Béchamel schichten. Mit Mozzarella abschließen.
6. Im Ofen ca. 35–40 Minuten goldbraun überbacken.
