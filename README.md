# Typeframe

> "I wish I could type my wireframes and send it to developers."
> —Morning of February 2, 2019



## INTRODUCTION

Typeframe will be an note application for typing UXMD that instantly converts in-line to coded components, much like how many Markdown note applications can convert instantly to WYSIWYG.

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

For icons, type the name of the icon file (sans suffix) after a back slash.



`/arrow_back` `/close` `/menu` `/more_horiz`



An alternative to writing the name of the icon, some very commonly used icons can be indicated through shorthands. Here are a few examples:



`/arrow_back` can also be written as `/<`

`/close` can be also written as `/x`

`/menu` can also be written as `/=`

`/more_vert` can be written as `/:`

`/more_horiz` can also be written as `/...`



Some icons don't make sense to be written in shorthand, such as:



`/search` `/favorite` `/shopping_cart` `/zoom_in`



#### APP BARS

```
[] 360x640

/header:fixed =
	= section icon:menu text:San Fransico =
    = section i:file_download i:print i:bookmark =
=
/tab bar:fixed =
	= tab:active i:access_time t:Recents =
	= tab i:near_me t:Nearby =
	= tab i:favorite t:Favorites =
=

# Palo Alto
###### July 9, 1956

Back in the day, there were a bunch of computer scientists building the machines of the future.
```

**V2 REPRESENTATIVE**

```
[] 360x640

= fix: =
= /menu"San Francisco == /file_download/print/bookmark =
= *|/access_time"Recents| |/near_me"Nearby| |/favorite"Favorites| =
= :fix =

# Palo Alto
###### July 9, 1956

Back in the day, there were a bunch of computer scientists building the machines of the future.
```
