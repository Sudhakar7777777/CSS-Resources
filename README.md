# CSS-Resources - Aug 2017
Useful links &amp; Tips


## Primary reference:
* [Good reference doc with examples](https://tympanus.net/codrops/css_reference/) :star2::star2::star2::star2::star2:
* [Official Mozilla CSS documentation](https://developer.mozilla.org/en-US/docs/Web/CSS) 
* [Check CSS attribute support for various browsers and their issues](http://caniuse.com/#search=flexbox)

## Responsive Design:
* [Official Mozilla docs on Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries#Media_features)
* [Responsive Design sample designs](http://mediaqueri.es)
* [Working prototype to understand Responsive/Adaptive/Fluid designs](http://www.liquidapsive.com/)
* [Stats on popular browser resolutions](http://gs.statcounter.com/screen-resolution-stats)

## Fundamentals like Hierarchies, Selectors
* [CSS Hierarchy guidelines](http://cssspecificity.com/)
* [Calculate the ranks for your selector](http://specificity.keegan.st/)
* [Hands on Tutorial to check your understanding of CSS selectors](http://flukeout.github.io) :star2::star2::star2::star2::star2:

## Global Fixes: Copy & Paste in your project
* [Fix for boxing floater issue](https://www.paulirish.com/2012/box-sizing-border-box-ftw/)
* [Reset default stylesheet](http://meyerweb.com/eric/tools/css/reset/)
* [Normalize stylesheet](https://necolas.github.io/normalize.css/)

## Color Tools:
* [Nice list of defined color and their hex values](http://colours.neilorangepeel.com/)
* [help to create color pallets and use in your project](https://coolors.co/) :star2::star2::star2::star2::star2:
* [See how background & foreground colors look](https://randoma11y.com/#/explore?_k=9gur18)
* [To to convert color hex to RGB values](http://rgb.to)

## Online Testing tool:
* [online tool -"jsfiddle.net" to test snippets of code](https://jsfiddle.net/)

## Font Tools:
* [Web safe fonts per font family](http://www.cssfontstack.com/)
* [How to declare/import custom fonts?](https://css-tricks.com/snippets/css/using-font-face/)
* [free font files to download, generated, etc.](https://www.fontsquirrel.com/)
* [Paid font hosting solution](https://typekit.com/)
* [free font hosting solution](https://fonts.google.com/)
* [ICON fonts](http://fontawesome.io/icons/)

## Others references:
* [Image trimmers](https://pixlr.com/editor/) ; also instead can use jpegtran commandline tool
* [Unicode char finder](https://unicode-table.com/en/#control-character)
* [Debate about should Nav use List or not?](https://www.sitepoint.com/are-navigation-lists-necessary/)

## Royality free Image sites:
* [Free images](https://unsplash.com) :star2::star2::star2::star2::star2:
* [Free High quality images](http://publicdomainarchive.com)

### Notes
1. Selecting elements in your CSS file:
    * Type Selector 	--- direct html elements
    * Class Selector	--- .ClassName (many times per page; can be multiple elements in a page)
    * ID Selector		--- #IdName	(once per page; unique per page)

2. Pseudo class selector --- AnySelector:Pseudo part of it.  Example: a:hover , a:visited , p:hover, a:focus , etc.

3. Best practices for selectors
    * Use Class instead of ID.  Use ID for primarily inpage linking.
    * Do not multi level selectors, keep to 3 levels or less.  The more depth you go, the slower the page will be rendered.

4. Selector Hierarchy
    * Type < Class < Id
        * So in effect Id selector values can override rest of other values.

5. Understanding about "display" , "float" & "postion" methods, similarities, differences is very important.  Use them based on your scenario needs.
    * Float: Image surrounded by content, Global page structures - header, footer & side bar.
    * Display: Aligning elements that needs to be center aligned., Doesn't chagne the page natural flow.
    * Position: Setting elements relative to another element, Aligning elements out of document flow, setting to specific spot on the   page.  Should not be used for page layouts.

```
Note: Float, display & position can't be used for the same element. If using position, float is ignored. If using float, position is ignored.
```
