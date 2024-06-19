## Notes
Le jeu ne peut pas fonctionner correctement en dessous de 60 images par seconde.

Il est donc nécessaire de configurer votre écran sur une résolution dont sa fréquence est supérieure ou égale à 60Hz.

### A vérifier

Si le jeu utilise un taux d'images supérieur à 60 images par seconde, ajouter en commande personnalisé la ligne suivante :
```
DXVK_FRAME_RATE=60 %command%
```
