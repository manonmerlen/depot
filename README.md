#Drunk_player

##Description

Drunk_player est un système de lecture de vidéos qui a trop bu. Il lit
les vidéos contenues dans un dossier par morceaux, aléatoirement et parfois

Drunk_player est composé :
- d'une bibliothèque (drunk_player) contenant le code de base
- d'un programme graphique (drunk_player_gui) qui affiche le résultat à l'écran
- d'un programme console (drunk_player_cli) qui sort le résultat dans un fichier

##Dépendances

- OpenCV
- Boost

##Compilation

```
mkdir build
cd build
cmake ..
make
```

##Utilisation

```
./a.out
```

![](drunk_player_gui.png)


