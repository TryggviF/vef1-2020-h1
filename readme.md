# Hópverkefni 1

## Keyrsla verkefnis

Til þess að keyra verkefnið er keyrt skipunina `npm run dev`

Tryggt verður að allt SCSS sé með löglegum hætti með skipuninni `npm run lint`

## Uppsetning verkefnis
### Almennt
Verkefnið stólar á node-sass, browser-sync, stylelint og concurrently,
sem og stylelint-config-standard og stylelint-config-sass-guidelines. 
Allar myndir eru geymdar í img möppu og allir stýlar eru settir í
styles möppu og síðan sameinaðir í styles.scss, sem skal síðan þýða til að keyra síðuna með réttu sniði
### Hvar má finna síður
* Recipe Overview finnst með því að smella á *'Recipes'* í valmynd efst
* Recipe finnst með því að smella á *'Read more'* á venjuleg uppskriftarspjöld
* Video recipe finnst með því að smella á *'Videos'* í valmynd efst
* Grid-Overlay er kommentað út, en finnst í head sérhvers HTML skjals
### Uppbygging SCSS skjala
* announcement.scss geymir css stíla fyrir bókartilkynningu í index.html
* config.scss geymir helstu breytur, og skilgreiningu á föllum fyrir column og row
* footer.scss geymir stíla fyrir fót sérhverrar vefsíðu
* global.scss geymir stíla fyrir öll html element sem eiga ekki tiltekinn stíl, sem og lóðréttar línur
* grid.scss geymir stíla fyrir grid, column og row, sem nýtast þegar hlutir skalast niður
* header.scss geymir stíla fyrir haus sérhverrar síðu
* hero-section.scss geymir stíla fyrir "Hero section" í index, recipe og video-recipe
* newsletter.scss geymir stíla fyrir "Newsletter" sectionið
* recipecard.scss geymir stíla fyrir uppskriftarspjöld sem finnast í index, recipe-overview og video-recipe
* video-recipe.scss geymir síla fyrir myndbandsspjöld sem finnast í index og recipe

## Þáttakendur verkefnis

Þáttakendur þessa verkefnis eru: 

* Tryggvi Freyr Sigurgeirsson - tfs2@hi.is - `Tryggvi F`
* Jóhannes Kári Sólmundarson - jks21@hi.is - `jaykaytherobot`
* Marcelo Felix Auditbert - mfa5@hi.is - `Gitcelo`
* Andreas Máni Helgason - amh50@hi.is - `amh50`

> Útgáfa 1.0
