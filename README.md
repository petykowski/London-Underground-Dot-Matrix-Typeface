# London TFL Dot Matrix Typeface

A set of dot matrix fonts in the style of TFL's Underground arrivals board. These fonts are based on original photographs of dot matrix arrival boards found across London Underground stations during late-2019 / early-2020.

## London Underground Regular

This font includes a full alpha character set (upper and lower cases), numbers, and symbols `- ' & * +`.

![London Underground Regular](resources/examples/London-Underground-Regular.png)![London Underground Regular Station Names](resources/examples/London-Underground-Regular-Station-Names.png)

## London Underground Bold

This font only includes a full number set and symbols `:`.

![London-Underground-Bold-Numbers](resources/examples/London-Underground-Bold-Numbers.png)

## London Underground Heavy

This font includes a full alpha character set (upper and lower cases), numbers, and symbols `- ' , * ()`.

![London Underground Heavy](resources/examples/London-Underground-Heavy.png)![London-Underground-Heavy-Station-Names](resources/examples/London-Underground-Heavy-Station-Names.png)

## Reference

The following photographs are an example of the particular dot matrix style which was referenced in the typeface creation.

![London-Underground-Arrival-Board](resources/examples/London-Underground-Arrival-Board.jpeg)



![DLR-Arrival-Board](resources/examples/DLR-Arrival-Board.jpeg)

## Contribute

#### Build Additional Characters to Existing Typeface
From Adobe Illustrator template file:
1. Build New Character
   - Add new artboard
   - Provide name of character for layer and artboard
   - Build character on separate layer
2. File > Export > Export As...
2. Export Artboards as SVG
   - Choose Export location
   - Format: SVG (svg)
   - Use Artboards Checked
   - All Artboards Selected
   - Maintain default SVG options

#### Add Characters to Existing Typeface
Open .sdf file in FontForge
1. Select character to update
2. File > Import
3. Element > Transformations > Transform
   - Scale Uniformly: 83.33333333%
4. Set width to width of character + 100
   - If svg width is 600 then set element width to 700
5. Align leading edge and baseline to element frame

#### Generate Font
1. File > Generate Fonts
   - Maintain default export values
2. Save into `font` directory of repo 

## License

This typeface is distributed with an [SIL Open Font License](http://scripts.sil.org/OFL).