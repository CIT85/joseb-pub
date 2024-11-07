# What is Cascading

My understanding of cascading is a way of how the style is applied, like top to bottom from the css style sheet.

external refers to a css sheet file we have and we have to link it

internal is when we have the ruleset inside the head

inline style is when its applied in the html right in the tag.

I did not see the video until after the commit

# CSS Ruleset
- inline take precedence over the other two
- external css keeps code clean
- the declaration is the whole chunk of code
- the selector is what selects the html tag
- it has to be spelled in american english
- if declaration is not detected it will be ignored
- validate the file with css validation from w3c

# how selectors work
- selectors work by selecting all the element type to be modified
- class starts with a period, can be called anything
- classes are reused, and they are specific
- id should be unique
- id are not used inside css
- grouped declarations without a coma, only look for nested elements
- with coma it look at all elements.
- universal selector selects everything
- any definition read last will be applied
- only typography are inherited
- universal selector selects all elements
- DRY = Dont Repeat Yourself
- form element do not inherit, need to explicitly select the form elements
- !important overrides the code, its sloppy

# CSS Colors
- we chan choose color names
- RGB can also be used
- Hex can be used too
- vs code helps alot with choosing the colors
- color pallet can be dragged to choose color
- pair numbers can be shorthanded

# CSS Units
- default size in pixels is 16
- a pixel is 1/96th of an inch
- percentages are relative
- its best to use rem instead of em
- em is best used for buttons and margins

# CSS Box Model
- the computed tab shows the size of the content and the margin, border and padding in color.
- you can see what is being ignored
