
Components
=========

Divider
-------

Some specs for a large divider could be set here, having a 7dp top padding and a 8dp bottom padding.
These values are specified independently in `Bottom sheets` and `Dialog` and could reference to a common spec here.


Menus
-----

### Specs

Minor fixes:
- "test" at the end of the first paragraph :)
- `Mobile` vs `Various widths`, should `Various widths` be `Tablet`?
- Rename `Mobile` to `Simple menu (mobile)`, `Various widths` to `Simple menu `(Various widths)` and merge the `Cascading menu` elements
- The specs for the `Cascading menu` font are in pt
- Mobile: `Menu item text left padding: 16dp` -> `Menu item text left and right padding: 16dp` to match the `components_dialogs_simplemenus8.png` and `components_dialogs_simplemenus9.png` diagrams
- Missing divider specs for simple menu (present in cascading menu)

Should the position of the text in the simple menu items be specified by a bottom padding?
With tall scripts and scaled text using sp, the text will expand vertically.
Why not centering the text vertically in the item, to match the cascading menu layout?
