# Hi !

I am a french-speaking developer mainly dedicated to creating and maintaining tools for the creation of visual novels,
or related to constitutional law and political science.

If you like what I do and have some monies to spare, I have a [ko-fi page](https://ko-fi.com/gouvernathor) where you can tip my work.

## Ren'Py
I have been contributing to the main [Ren'Py repository](https://github.com/renpy/renpy) since late 2020,
and I have been one of its maintainers - still the second contributor in terms of volume of code and excluding translations. I still come back to it from time to time.

I also created additional tools and snippets which can help creating games in Ren'Py, for example :
* [ChromaGlitch](https://github.com/Gouvernathor/renpy-ChromaGlitch), a glitching effect
* [SWHolo](https://github.com/Gouvernathor/renpy-SWHolo), a hologram effect similar to the Jedi council in Star Wars
* [PronounsClass](https://github.com/Gouvernathor/renpy-PronounsClass), a class to help managing player-chosen or otherwise dynamic pronouns
  for multiple characters
  * Fen's [In-Depth Pronouns](https://github.com/shawna-p/in-depth-pronouns-renpy) offers additional features but doesn't support several characters
    being pronouned in a single game - mine does
* [TranslationTools](https://github.com/Gouvernathor/renpy-TranslationTools), some tools to help managing translation files in renpy games
* [AttributesManager](https://github.com/Gouvernathor/renpy-AttributesManager), a toolkit to help managing the attributes passed to images
  (layeredimages in particular).
* A partial rewrite of the layeredimage syntax striving for optimization, consistency and featurefullness, which may or may not be partially
  or totally included in a future version of Ren'Py.

## Politics and SVG
I am currently hosting a saved (and multilingual) version of [PolitiScales](https://github.com/Gouvernathor/gouvernathor.github.io),
which disappeared from its original website along with the repository hosting its code (of which this was originally a fork).  
I [reimplemented it](https://github.com/Gouvernathor/Politiscales-Angular) using the Angular framework, and it will be eventually available on its own website.

I am also contributing and maintaining the [ParliamentDiagram tool](https://parliamentdiagram.toolforge.org/archinputform.php)
([repo](https://github.com/Slashme/parliamentdiagram)), whose purpose is to create beautiful and solemn displays of the political groups
in a chamber of Parliament. You've probably already seen one of our diagrams, if you went on the Wikipedia page of a legislative assembly.  
The [Parliamentarch](https://github.com/Gouvernathor/parliamentarch) python module manages the geometry calculations and the SVG exports
for those diagrams, offering more customization options than the website offers, you can import and use it yourself !  
A TypeScript/JavaScript reimplementation is available as the [`parliamentarch` NPM package](https://github.com/Gouvernathor/ParliamentArch-TS).

I have another tool, [Py-Spangled Banner](https://github.com/Gouvernathor/py-spangled-banner), for making SVG displays of the american flag
with a variable number of stars (among other parameters).  
A [TypeScript/JavaScript reimplementation](https://github.com/Gouvernathor/ts-spangled-banner) is also available.

[Ecclesia-TS](https://github.com/Gouvernathor/Ecclesia-TS), or just `ecclesia` on NPM, is a library of various functions and classes for constitutional and parliamentary simulations. A demo website implementing it, named Eligo, should come to life (eventually).
