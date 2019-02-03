# Typeframe

> "I wish I could type my wireframes and send it to developers."
>
> (Morning of February 2, 2019)
>
> -Jason Marsh



## INTRODUCTION

Typeframe (will be) an electron note application for typing UXMD that instantly converts in-line to coded components, much like how many Markdown note applications can convert instantly to WYSIWYG.

The justification for typeframe is predicated on the idea that the design process is often uncessesarily painstaking and granular for common designer needs.

Problems to solve:

* Rapid ideation
* Pixel-hell
* Reinventing componenets
* "Getting the idea across" to developers
* Instant feedback
* Easy editing



## UXMD

UXMD is a text-to-component conversion tool for designers that is meant to work alongside Markdown. Just like Markdown, the central tenet is to provide an easy-to-read, easy-to-write plain text format that converts to structurally-correct components.

#### ICONS

For icons, use the name of the icon file (sans suffix) surrounded by braces.



`{arrow_back}` `{close}` `{menu}` `{more_horiz}`



An alternative to writing the name of the icon, some very commonly used icons can be indicated through shorthands. Here are a few examples:



`{arrow_back}` can also be written as `{<}`

`{close}` can be also written as `{x}`

`{menu}` can also be written as `{=}`

`{more_vert}` can be written as `{:}`

`{more_horiz}` can also be written as `{...}`



Some icons don't make sense to be written in shorthand, such as:



`{search}` `{favorite}` `{shopping_cart}` `{zoom_in}`



Braces were chosen because of their ornate appearance that enclose the name.



#### APP BARS
To create an app bar, use two or more `==` without any text following. Without any elements inside this only indicates a blank container.



`==` or `====`



To indicate an element is inside of an app bar, add it between two or more `==`. To center-align, place an even number on both sides. Here are two app bars with center-aligned text and a center-aligned FAB.



`= text =` or `== (({+})) ==`



To left-align an element inside an app bar, place only one `=` to the left of the element, and two or more `==` to the right of it.



`= {menu} ==`



Similarly, you can indicate right-aligned.



`== {search} =`



Bar with a left aligned icon, a center aligned floating action button (FAB), and two right aligned action icons.



`= {=} = (({+})) = {search}{:} =`








To indicate that this is a bottom app bar, place the bar at the bottom.

#### TOP VS BOTTOM APP BARS
**Overview:**

All bar components are written in the same way. The bar's type (header, footer) of is indicated by its placement on the page.

```
= Home ==
== * Current * Upcoming ==
# Header
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
((Cancel)) ((Next))
== * {home} * {search} * {cart} ==

```



#### BACKDROP
#### BANNERS
#### BOTTOM NAVIGATION
#### BUTTONS
#### BUTTONS: FLOATING ACTION BUTTON
#### CARDS
#### CHIPS
#### DATA TABLES
#### DIALOGS
#### DIVIDERS
#### IMAGE LISTS
#### LISTS
#### MENUS
#### NAVIGATION DRAWERS
#### SELECTION CONTROLS
#### SHEETS: BOTTOM
#### SHEETS: SIDE
#### SLIDERS
#### SNACKBARS
#### TABS
#### TEXT FIELDS
#### TOOLTIPS
