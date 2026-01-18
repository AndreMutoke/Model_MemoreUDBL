# Model_MemoreUDBL
Un modele complet respectant les exigence de l'UDBL
# Commande
Pour compiler, utilisez la commande suivante en CLI
```bash
pdflatex main.tex
```
# Notice importante
Il est important de verifier si latex est deja installé. Si vous etes sous windows, vous devez references le dossier contenant MikTex
dans la variable d'environnement. Sous linux il suffit de l'installer en CLI(voir le site officiel).

# Comment compiler la bibliotheque ?

Dans votre interface CLI
```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
```
## NB
Les references bibliographique se trouvent dans le fichier myBib.bib
A vous de vous faire plaisir.