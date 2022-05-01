# London TFL Dot Matrix Typeface

A set of dot matrix fonts in the style of TFL's Underground network. Each font weight represents a unique typeface featured on TFL arrivals boards and rolling stock led announcement boards.

## London Underground Regular

This typeface sets out to recreate the font used on dot matrix arrival boards found across London Underground stations in late-2019 / early-2020.

![London Underground Regular Station Names](resources/examples/London-Underground-Regular-Station-Names.png)

### Character Set Details
This font includes a full alpha character set (upper and lower cases), numbers, and symbols `- ' & * +`.

![London Underground Regular](resources/examples/London-Underground-Regular.png)

## London Underground Medium

This typeface sets out to recreate the dot matrix font found displayed on London Underground 1996 Stock.

![London-Underground-Medium](resources/examples/London-Underground-Medium-Next-Station.png)

### Character Set Details
This font includes a partial alpha character set (upper and lower cases) and symbols `: .`.

![London-Underground-Medium](resources/examples/London-Underground-Medium.png)

**NOTE: Missing Characters!** This font does not currently include the following characters due to a lack of reference materials. Please contact me on [Twitter](https://twitter.com/petykowski_) if you have photographs of these characters.
* `A C E F I J K M O Qq S T U V X Yy Z`

## London Underground Bold

![London-Underground-Bold-Numbers](resources/examples/London-Underground-Bold-Numbers.png)

### Character Set Details
This font only includes a full number set and symbols `:`.

## London Underground Heavy

This typeface sets out to recreate the font used on dot matrix arrival boards found across London DLR stations in late-2019 / early-2020.

![London-Underground-Heavy-Station-Names](resources/examples/London-Underground-Heavy-Station-Names.png)

### Character Set Details
This font includes a full alpha character set (upper and lower cases), numbers, and symbols `- ' , * ()`.

![London Underground Heavy](resources/examples/London-Underground-Heavy.png)

## Reference

London Underground Regular, Bold, and Heavy is sourced from original photographs of dot matrix arrival boards found across London Underground stations during late-2019 / early-2020.

The following photographs are an example of the particular dot matrix style which was referenced in the typeface creation.

![London-Underground-Arrival-Board](resources/examples/London-Underground-Arrival-Board.jpeg)

![DLR-Arrival-Board](resources/examples/DLR-Arrival-Board.jpeg)

London Underground Medium is sourced from video recordings found on YouTube. Attributes as follows:
* [X2K9](https://www.youtube.com/watch?v=MpcsaVmps-Q)
* [Random Transport](https://www.youtube.com/watch?v=1G5eaNuZYDc)

![Random Transport](resources/examples/London-Underground-Jubilee-Line.png)

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