# PRG — Programmation procédurale (PRG-B, 2026-2027)

Site du cours PRG à la [HEIG-VD](https://heig-vd.ch), classe PRG-B,
construit avec [Quarto](https://quarto.org) sur le modèle du cours DAI.
Publié sur <https://heigvd-prg-b-26.github.io>.

## Structure

```
_quarto.yml        navigation et thème
_variables.yml     valeurs propres à l'année
index.qmd          Planning (page d'accueil)
materiel/          Matériel de cours : table des decks, liens PDF
slides/            PDF des slides (ajoutés au fil du semestre)
labos/             Consignes et table des laboratoires (rendus sur Roster)
exercices/         Lien vers le recueil public d'exercices, par chapitre
guides/            Installation C++ / CLion, Git en pratique
ressources/        Règles, IA, fiche d'unité, références
```

## Aperçu local

```sh
quarto preview
```

Le site est rendu et déployé sur GitHub Pages par
`.github/workflows/publish.yml` à chaque push sur `main`.
