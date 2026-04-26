# cub3D

Un raycaster en C avec collisions et collectibles.

## 📖 Description

**cub3D** est un projet de l'école 42 inspiré du mythique jeu **Wolfenstein 3D**, considéré comme le père des FPS modernes.

L'objectif est de créer un moteur graphique en 3D utilisant la technique du **raycasting**, une méthode mathématique qui simule une perspective 3D à partir d'une carte 2D. Le tout en C pur, avec la bibliothèque graphique **MiniLibX**.

## Prérequis

- Compilateur C (Clang)
- Make

### Compilation

```bash
make
```

### Lancement

```bash
./cub3D maps/valid/map.cub
```

### Exemple de fichier `.cub`

```
NO ./textures/north_wall.xpm
SO ./textures/south_wall.xpm
WE ./textures/west_wall.xpm
EA ./textures/east_wall.xpm

F 220,100,0     # couleur du sol en rgb
C 135,206,235   # couleur du ciel en rgb

11111111111111
10001000000001
10001110001101
10100000001001
101000N0001001
11111111111111
```