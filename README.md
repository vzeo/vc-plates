# Vice City License Plates

<img width="1338" height="720" alt="Vice City License Plates" src="https://github.com/user-attachments/assets/f795d907-b72d-4169-a1d2-d3d4ef99b351" />


License plate mod for every car model in the original GTA VC, complete with a customizable design and text.

__! Xbox vehicle models are recommended for this mod!__


## Features
- Unique plates for every car – each vehicle gets its own randomly generated plate, which stays with it until the vehicle despawns.
- Custom plate text – give your current vehicle a personalized plate using an in-game dialog.
- Your own plate designs – use different plate images, fonts, colors and text layouts.
- Model-specific plates – assign dedicated designs to particular vehicles, such as police cars or taxis.
- Flexible configuration – adjust plate positions, sizes, rotation, mirroring and image fitting.
- Live config reloading – save your configuration file and the mod automatically reloads it (no game restart required).


## Cheat code

While driving, type the cheat:

`SWEETPLATEBABY`

An in-game dialog will open, allowing you to enter custom text for the vehicle you're currently driving.
Use up to 12 characters – letters, numbers, spaces, symbols and even non-Latin characters (if your font supports them).

Your custom plate stays on that vehicle until it despawns or the configuration is reloaded.



## Customization

The mod uses license_plates.cfg to define where license plates are located in vehicle textures.
You can add your own plate templates, choose fonts and colors, set text formats, and assign particular designs to specific vehicle models.
For example:
```
@text format=***_%%% font=Plate.ttf color=202020
@template plate_generic.jpg chance=0.7
@template plate_old.jpg chance=0.3
@template plate_police.jpg chance=0 models=policar:enforcer
```
- `*` is a random letter;
- `%` is a random digit.

You can also adjust individual plate positions, dimensions, rotation, mirroring and image fitting.

_Plate templates and fonts go into the `assets` folder next to the .asi file._

## Known bugs
1. Flipped plates on some vehicle models:
   - Mule
   - Spand Express
   - Bobcat
   - Pony
   - Rumpo
   - Topfun


