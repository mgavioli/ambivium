# Ambivium

Ambivium is a modification of the nice [Junction](https://github.com/theleagueof/junction) font,
designed by Caroline Hadilaksono of [The League of Moveable Type](https://www.theleagueofmoveabletype.com/)
and made available under the SIL Open Font License.

![Ambivium sample](sample.png?raw=true)

Hopefully, it will be possible in the future to merge (some of) the Ambivium additions into the original Junction files
and this fork will become obsolete.

Differences from Junction:
- All glyphs in the light, regular and bold weigths have been ‘cleaned-up’, by:
    - adding missing extrema,
    - correcting self-intersecting paths,
    - rounding non-integral point coordinates.
- Text (‘old-style’) numerals of the standard Junction fonts have been restored into the web fonts and made the default in all fonts.
- Small caps have been added to the regular weight.

Ambivium is developed with FontForge and its sources are in the FontForge `.sfd` format. It is published under the SIL OFL license.

“Ambivium” is a (not very common) Latin word roughly equivalent to “junction”, at least in its meaning of _crossroad_.

## Folders

- **src**: the sources in FontForge format
- **ttf**: directly usable fonts, as generated by FontForge
- **webfonts**: .WOFF web fonts as generated by FontForge

## To do

- **anchors**: Junction had no anchors; a system of anchors to support on-the-fly composition of compound glyphs
    in OpenType-aware applications would be helpful.
- **small capitals** for light and bold weights.
- **Cyrillic** is already under development for the regular weight; light and bold will hopefully follow.
- **Italics** ?

## Development

If you have a github account, are familiar with FontForge and git and would like to help:
- fork this repository into your github account and clone the fork to your PC;
- create a new branch for each change / improvement you want to propose;
- once the change is ready, push it to your fork ("origin") and...
- ... from your github fork create a Pull Request to this repository (a.k.a. "upstream").

Thank you!
