## Notes
Une erreur de compilation des shaders se produit au démarrage du jeu.

Placer le fichier winetricks fourni dans $SPS_GAME_DIR/Steam puis exécuter cette commande avant de lancer le jeu via Steam :
- SPS_GAME_DIR est une variable que vous pouvez modifier. Elle représente le chemin où se situe vos jeux Steam

```
export SPS_GAME_DIR="/media/datas"
WINEPREFIX="$SPS_GAME_DIR/Steam/steamapps/compatdata/35140/pfx/" WINE="$SPS_GAME_DIR/Steam/steamapps/common/Proton - Experimental/files/bin/wine" $SPS_GAME_DIR/Steam/winetricks d3dx9 d3dcompiler_43
```
