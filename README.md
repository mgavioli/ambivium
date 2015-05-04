# ambivium
Ambivum is a modification of the nice [Junction](https://github.com/theleagueof/junction) font, designed by Caroline Hadilaksono of [The League of Moveable Type](https://www.theleagueofmoveabletype.com/) and made available under the SIL Open Font License.

Hopefully, it will be possible in the future to merge (some of) the Ambivium additions into the original Junction files and this fork will become useless.

Differences from Junction:
- All glyphs in the light, regular and bold weigths have been ‘cleaned-up’, by:
    - adding missing extrema,
    - correcting self-intersecting paths,
    - rounding non-integral point coordinates.
- Text (‘old-style’) numerals of the standard Junction fonts have been restored into the web fonts.
- Small caps have been added to the regular weight (no kerning yet!!!)

Ambivium is developed with FontForge and its sources are in the FontForge `.sfd` format. It is published under the SIL OFL license.

“Ambivium” is a (not very common) Latin word roughly equivalent to “junction”, at least in its meanign of _crossroad_.

##Folders
- **src**: the sources in FontForge format
- **ttf**: directly usable fonts, as generated by FontForge
- **webfonts**: web fonts in several format as generated by [Fontie](https://fontie.flowyapps.com/home)
