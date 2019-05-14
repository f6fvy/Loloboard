# Loloboard

## Experimentation board designed with KiCad

- Top layer : Connections can bea easily made to the plane with a solder drop.
- Bottom layer : Larger pads with no plane
- Thru all pads pitch 2.54 mm / 100 mils
- Mounting holes connected to the plane or not
- Can be easily split in 2 or 4 smaller boards

!(loloboard.jpg "Loloboard")

**CAUTION** : As asymetrical pads are used (the pads dimensions are different on each layer), KiCad (5.1.2) considers it as an error and fix it after opening in pcbnew. DO NOT SAVE when exit pcbnew. Work on a copy, and manually fix the pads with a text editor if needed.

When ordering your PCBs, don't forget to mention :

- No silkscreen (both layers)
- Tinned layers, no soldermask (both layers)
- V-cuts as specified in v-cuts.png
