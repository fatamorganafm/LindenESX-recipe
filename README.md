![LindenESX](https://i.imgur.com/SAhoPsx.png)

# LindenESX-recipe
An ESX Legacy server base utilizing resources from mainly from thelindat. 

This is working fork. [ 17.08.2021 ]

This recipe runs inside [**txAdmin**](https://github.com/tabarra/txAdmin).  
Please check the [**Recipe Documentation Page**](https://github.com/tabarra/txAdmin/blob/master/docs/recipe.md).

## If you don't read this, don't complain about things not working.
After initial setup and server start, shut the server down **(do not try and join server yet)** do the following edits:
[esx]\es_extended\config.lua
Set **Config.Multichar = true**

[elements]\cosmo_hud\config.lua
Set **Config.UseRadio = false** (unless you install rp-radio)

[esx]\esx_basicneeds\config.lua
Set **Config.Visible = false**

[esx]\esx_status
Set **Config.Display = false**

**CHECK ALL OTHER CONFIGS AS WELL TO MEET YOUR NEEDS**

## Notes
For linden_inventory please read the docs before you do anything else.
https://thelindat.github.io/linden_inventory/

## Credits for used resources
[thelindat](https://github.com/thelindat)
[OfficialNoms](https://github.com/OfficialNoms)
[brentN5](https://github.com/brentN5)
[nojdh](https://github.com/nojdh)
[nxxnly](https://github.com/nxxnly)
