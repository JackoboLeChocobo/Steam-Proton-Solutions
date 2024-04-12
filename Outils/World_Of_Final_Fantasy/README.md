## Notes
Le jeu fonctionnant de base sur un taux d'images de 30 images / secondes, nous allons configurer l'option "dxgi.syncInterval" pour obtenir la bonne valeur :
- valeur = Taux de Fréquence de l'écran / 30

Dans le dossier "steamapps/common/WOFF", créer le fichier "dxvk.conf" ( vous devez avoir dans ce dossier le fichier WOFF.exe ) et ajouter le contenu suivant :
```
[WOFF.exe]
dxgi.syncInterval = valeur
```

### Exemple
- L'écran est configuré sur une résolution de 1920x1080 avec une fréquence de 60Hz
- La valeur est donc de 60 / 30 = 2

Le contenu du fichier "dxvk.conf" contiendra les informations suivantes :
```
[WOFF.exe]
dxgi.syncInterval = 2
```
