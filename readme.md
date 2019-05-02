# Installation Instructions.

1. Download the latest release bin.zip from the releases page.
2. Extract the contents into your ClassicUO/data/plugins/ folder
3. Edit your settings.json file to include CEasyUO
```   
"plugins": [
    "./Razor/Razor.exe",
    "./CEasyUO/CEasyUO.exe"
  ]
```

## Functionality Changes
#### #GUMPSERIAL and #GUMPTYPE #LGUMPBUTTON new variables for gumps.

#### Mobile Health bars do not show via #ContType, Use #LTARGETTYPE


## New commands

### Gump Handling

#### event gump wait {timeout}
Waits until timeout( default 10 seconds) or a gump appears

#### event gump last
Repeats the last gump input action

#### event gump button {index}
Responds to the current gump with the specified index


### Context Menus

#### event contextmenu {serial} {index}
Triggers a context menu click at the specified index on the specified object


## Depreceated commands

#### Menu
#### Click

## Depreceated Variables

#### #NEXTCPOSX/Y Gone 
#### #CONTPOSX #GUMPOSX replaces much of this functionality but GUMP handling should move to using the new events.
#### #CONTPOSY #GUMPOSY replaces much of this functionality but GUMP handling should move to using the new events.
#### #CONTSIZEX/Y have been replaced with #GUMPSIZEX/Y
These only update when a new gump opens, and do not update when you change focus in game.



