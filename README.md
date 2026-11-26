# Exercice_Geni_logiciel

Dépôt de l'exercice de génie logiciel : document d'analyse en LaTeX, son rendu PDF, et les liens vers les diagrammes UML réalisés sur Lucid.

## Diagrammes (Lucid)

| Diagramme | Rôle | Lien |
|---|---|---|
| Cas d'utilisation | Acteurs du système et fonctionnalités qu'ils utilisent | [Ouvrir](URL_CAS_UTILISATION) |
| Séquence | Échanges de messages entre objets dans le temps, pour un scénario donné | [Ouvrir](URL_SEQUENCE) |
| Classes | Structure statique : classes, attributs, méthodes et relations | [Ouvrir](URL_CLASSES) |
| Composants | Organisation en modules et interfaces entre eux | [Ouvrir](URL_COMPOSANTS) |

## Fichiers du dépôt

| Fichier | Rôle |
|---|---|
| [Document.tex](Document.tex) | **Source LaTeX** du document d'analyse. C'est le seul fichier à modifier à la main. |
| [Document.pdf](Document.pdf) | **Rendu final** produit par la compilation de `Document.tex`. |
| [Document.aux](Document.aux) | Fichier auxiliaire LaTeX (références croisées, numérotation). Généré automatiquement. |
| [Document.log](Document.log) | Journal de compilation : avertissements et erreurs. |
| [Document.synctex.gz](Document.synctex.gz) | Correspondance entre le PDF et le source LaTeX. |
| [README.md](README.md) | Ce fichier. |

## Compiler le document

```bash
pdflatex Document.tex
```