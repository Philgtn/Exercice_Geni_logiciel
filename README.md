# Exercice_Geni_logiciel

Dépôt de l'exercice de génie logiciel : document d'analyse en LaTeX, son rendu PDF, et les liens vers les diagrammes UML réalisés sur Lucid.

## Diagrammes (Lucid)

Les diagrammes sont regroupés sur **deux documents Lucid**, chacun contenant plusieurs diagrammes accessibles sur des pages différentes.

| Lien Lucid | Diagrammes inclus | Rôle |
|---|---|---|
| [Ouvrir le document 1](https://lucid.app/lucidchart/24c1c51b-c5d9-4874-8372-94b7308577d1/edit?viewport_loc=-1163%2C-384%2C3006%2C1270%2CS0-PFrnG1pE9&invitationId=inv_87c0ee0d-7f44-47a7-8205-060f06157fbc) | Cas d'utilisation, Activités | Acteurs du système et fonctionnalités qu'ils utilisent ; enchaînement des traitements d'un scénario |
| [Ouvrir le document 2](https://lucid.app/lucidchart/741f6a2b-3b74-4b4e-b0e5-5848bc77c504/edit?viewport_loc=-679%2C-42%2C2156%2C883%2Cclasses&invitationId=inv_79bca8a8-1596-40c4-864a-2f5000a2be80) | Classes, Séquence, Composants | Structure statique (classes, attributs, méthodes, relations) ; échanges de messages dans le temps ; organisation en modules et interfaces |

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