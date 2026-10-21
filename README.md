# famine42

Squelette de départ du projet **Famine** de l'École 42, en C.

## État du projet

Ce dépôt contient uniquement une base compilable. Le programme ne modifie aucun fichier et ne contient aucune logique d'infection ou de propagation.

## Compilation

```sh
make
```

La compilation produit un exécutable nommé `Famine`.

## Nettoyage

```sh
make clean
make fclean
make re
```

## Organisation

- `src/main.c` : point d'entrée du programme.
- `include/famine.h` : en-tête du projet.
- `Makefile` : compilation et nettoyage.

## Environnement de travail

Pour respecter le sujet, toutes les expérimentations doivent être réalisées **dans une machine virtuelle isolée**. Les opérations sur les fichiers sont limitées à `/tmp/test` et `/tmp/test2` (ou aux chemins équivalents de l'OS choisi).
