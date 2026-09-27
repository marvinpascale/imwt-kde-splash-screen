# In Marvin We Trust · KDE Plasma Splash

Una splash screen per **KDE Plasma 6**: fondo nero, Marvin con spada laser rossa, logo pixelato e barra di caricamento a segmenti. La barra segue le fasi di avvio comunicate da KSplashQML; la luce che la attraversa è un effetto decorativo.

## Installazione

```bash
mkdir -p ~/.local/share/plasma/look-and-feel/org.inmarvinwetrust.splash
cp -a metadata.json contents ~/.local/share/plasma/look-and-feel/org.inmarvinwetrust.splash/
```

Poi seleziona **In Marvin We Trust** in **Impostazioni di sistema → Aspetto → Splash screen**. In alternativa:

```bash
ksplashqml --test org.inmarvinwetrust.splash
```

Per disinstallare, elimina la cartella `~/.local/share/plasma/look-and-feel/org.inmarvinwetrust.splash` e seleziona un'altra splash screen nelle impostazioni.

Il logo proviene dal progetto [In Marvin We Trust](https://github.com/marvinpascale/inMarvinWeTrust). L'immagine di Marvin è stata fornita per questo tema; `contents/splash/images/marvin-lightsaber.png` è una copia ridimensionata per caricarla più velocemente. Il tema non cambia la schermata di login SDDM né l'animazione di avvio del sistema.
