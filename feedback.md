
Some feedback about the material design guidelines.
This feedback is relevant to the August 2016 release of the spec.

Material design is great and the specifications are formidable to work with,
but I have stumbled upon some details during the creation of this library.


Bottom sheets
-------------

The height of a grid list is not specified (`components_bottomsheets_specs7.png`).

The grid list label (text size?) is defined in dp instead of sp.


Chips
-----

Top specs are that all labels should be 13sp but the closed contact chip specs indicate a value of 14sp.


Divider
-------

Some specs for a large divider could be set here, having a 7dp top padding and a 8dp bottom padding.
These values are specified independently in `Bottom sheets`, `Dialogs` and `Menus` and could reference a common spec here.


Menus
-----

### Specs

Minor fixes:
- "test" at the end of the first paragraph :)
- `Mobile` vs `Various widths`, should `Various widths` be `Tablet`?
- Rename `Mobile` to `Simple menu (mobile)`, `Various widths` to `Simple menu (Various widths)` and merge the `Cascading menu` elements
- The specs for the `Cascading menu` font are in pt
- Mobile: `Menu item text left padding: 16dp` -> `Menu item text left and right padding: 16dp` to match the `components_dialogs_simplemenus8.png` and `components_dialogs_simplemenus9.png` diagrams
- Missing divider specs for the simple menu (present in cascading menu), I suppose it's the same (16 dp height)

Should the position of the text in the simple menu items be specified by a bottom padding?
With tall scripts and scaled text using sp, the text will expand vertically.
Why not centering the text vertically in the item, to match the cascading menu layout?


Progress & activity
-------------------

Last video doesn't load: `error Media "components-progressactivity-behavior_Loading_SwipeDown_noload_xhdpi_005.mp4" not found`


Steppers
--------

Minor fixes:
- Should the `Google Blue 500` color spec be renamed to `Material Blue 500`?
- One color spec is `Google Blue 500`, another is `Grey 400`, rename one for consistency.
