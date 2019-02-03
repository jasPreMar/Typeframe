# UXMD

> "I want to be able to type my UI and hand it to my developers."
>
> (February 2, 2019)



#### ICONS

For icons, use the name of the icon file (sans suffix) surrounded by braces.

**{arrow_back}**
**{close}**
**{menu}**
**{more_horiz}**



An alternative to writing the name of the icon, some very commonly used icons can be indicated through shorthands. Here are a few examples:

**{arrow_back}** *can also be written as* **{<}**
**{close}** *can be also written as* **{x}**
**{menu}** *can also be written as* **{=}**
**{more_horiz}** *can also be written as* **{...}**



Some don't make sense to be written as shorthand, such as:

**{search}**
**{favorite}**
**{shopping_cart}**
**{zoom_in}**



Braces were chosen because of their ornate appearance that enclose the name.

#### APP BARS: BOTTOM
**##** -or- **######**

To create an app bar, use two or more hashes without any text following. Two hashes `##` alone indicates that the bar is only a blank container.

**#text#** -or- **##(({+}))##**

To indicate an element is inside of an app bar, add it between the hashes. To center-align, place an even number on both sides. Here are two app bars with center-aligned text and a center-aligned FAB.

**#{=}##**
To left-align an element inside an app bar, place only one hash to the left, and two or more hashes to the right of it.

**##{search}#**
Similarly, you can indicate right-aligned.

**###{search}{more_vert}#**
Bar with overflow menu control

**#{menu}#(({+}))#{search}{more_vert}#**

Bottom bar with a left aligned icon, center aligned FAB, and two right aligned action icons.

#{<}#Page Title##

All bar components are written in the same way. The bar's type (header, footer) of is indicated by its placement on the page.

To indicate that this is a bottom app bar, place the bar at the bottom.

##### APP BARS: TOP
**Overview:**

Just like the bottom app bar, its placement informs the function. Top app bars should always be placed either at the top of the page or under any existing system elements such as status bar.

**Example:**

={menu}Page title=={favorite}=

1. Bar container:
   `====`
2. Bar container:
   `#####`

##### BACKDROP

##### BANNERS
##### BOTTOM NAVIGATION
##### BUTTONS
##### BUTTONS: FLOATING ACTION BUTTON
##### CARDS
##### CHIPS
##### DATA TABLES
##### DIALOGS
##### DIVIDERS
##### IMAGE LISTS
##### LISTS
##### MENUS
##### NAVIGATION DRAWERS
##### SELECTION CONTROLS
##### SHEETS: BOTTOM
##### SHEETS: SIDE
##### SLIDERS
##### SNACKBARS
##### TABS
##### TEXT FIELDS
##### TOOLTIPS
