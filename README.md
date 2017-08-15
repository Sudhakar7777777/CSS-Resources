# CSS-Resources - Aug 2017
Useful links &amp; Tips


Primary reference:
https://tympanus.net/codrops/css_reference/					--- Good reference doc with examples
https://developer.mozilla.org/en-US/docs/Web/CSS  			--- Official documentation
http://caniuse.com/#search=flexbox							--- CSS browser support for various attributes

Responsive Design:
https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries#Media_features --- Offical docs
http://mediaqueri.es 										--- Responsive Design
http://www.liquidapsive.com/ 								--- Work effects of various responsive,adaptive patterns
http://gs.statcounter.com/screen-resolution-stats			--- Stats on popular browser resolutions

http://cssspecificity.com/  --- CSS Hierarchy guidelines
http://specificity.keegan.st/ --- Calculate the ranks for your selector

Global Fixes:
https://www.paulirish.com/2012/box-sizing-border-box-ftw/	--- Fix for boxing floater issue
http://meyerweb.com/eric/tools/css/reset/ 					--- Reset stylesheet
https://necolas.github.io/normalize.css/					--- Normalize stylesheet

Color Tools:
http://colours.neilorangepeel.com/				--- Nice list of defined color and their hex values
https://coolors.co/								--- help to create color pallets and use in your project
https://randoma11y.com/#/explore?_k=9gur18		--- See how background & foreground colors look
http://rgb.to 									--- To to convert color hex to RGB values

Online Testing tool:
https://jsfiddle.net/	-- online tool to test snippets of code

Font Tools:
http://www.cssfontstack.com/							--- Web safe fonts per font family
https://css-tricks.com/snippets/css/using-font-face/	--- How to declare/import custom fonts?
https://www.fontsquirrel.com/							--- free font files to download, generated, etc.
https://typekit.com/									--- Paid font hosting solution
https://fonts.google.com/								--- free font hosting solution
http://fontawesome.io/icons/							--- ICON fonts

Others:
http://flukeout.github.io 									--- Hands on Tutorial to check your understanding of CSS selectors
https://pixlr.com/editor/									--- Image trimmers
https://unicode-table.com/en/#control-character				--- Unicode char finder
https://www.sitepoint.com/are-navigation-lists-necessary/	--- Should Nav have List or not?

Royality free Image sites:
https://unsplash.com 
http://publicdomainarchive.com

Selecting elements in your CSS file:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Type Selector 	--- direct html elements
Class Selector	--- .ClassName (many times per page; can be multiple elements in a page)
ID Selector		--- #IdName	(once per page; unique per page)

Pseudo class selectro --- AnySelector:Pseudo part of it.  Example: a:hover , a:visited , p:hover, a:focus , etc.

Best practices
~~~~~~~~~~~~~~
- Use Class instead of ID.  Use ID for primarily inpage linking.
- Do not multi level selectors, keep to 3 levels or less.  The more depth you go, the slower the page will be rendered.


Selector Hierarchy
~~~~~~~~~~~~~~~~~~
Type < Class < Id

So in effect Id selector values can override rest of other values.


- Understand about "display" , "float" & "postion" methods, similarities, differences and use it based on your scenario needs.

Float: Image surrounded by content, Global page structures - header, footer & side bar.
Display: Aligning elements that needs to be center aligned., Doesn't chagne the page natural flow.
Position: Setting elements relative to another element, Aligning elements out of document flow, setting to specific spot on the page.  Should not be used for page layouts.

Note: Float, display & position can't be used for the same element. If using position, float is ignored. If using float, position is ignored. 
