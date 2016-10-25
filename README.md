Material Values
===============

All the values from the [Material Design guidelines](https://material.google.com) defined in resources for Android.


Available values
----------------

| Style |     |
|-------|-----|
| Color      | [[Documentation]](https://aodevblue.github.io/MaterialValues/style/colors/) [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-style/values/colors.xml) [[Specs]](https://material.google.com/style/color.html) |
| Icon       | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-style/values/icons.xml) [[Specs]](https://material.google.com/style/icons.html) |
| Typography | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-style/values/typography.xml) [[Specs]](https://material.google.com/style/typography.html) |

| Layout |     |
|--------|-----|
| Metrics & keylines | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-layout/values/keylines.xml)   [[Specs]](https://material.google.com/layout/metrics-keylines.html) |
| Responsive UI      | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-layout/values/responsive.xml) [[Specs]](https://material.google.com/layout/responsive-ui.html) |
| Elevation          | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-layout/values/elevation.xml)  [[Specs]](https://material.google.com/material-design/elevation-shadows.html) |


| Components |     |
|------------|-----|
| Bottom navigation | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/bottom_navigation.xml) [[Specs]](https://material.google.com/components/bottom-navigation.html) |
| Bottom sheets     | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/bottom_sheet.xml) [[Specs]](https://material.google.com/components/bottom-sheets.html) |
| Buttons           | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/button.xml) [[Specs]](https://material.google.com/components/buttons.html) |
| Cards             | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/card.xml) [[Specs]](https://material.google.com/components/cards.html) |
| Chips             | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/dialog.xml) [[Specs]](https://material.google.com/components/chips.html) |
| Dialogs           | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/dialog.xml) [[Specs]](https://material.google.com/components/dialogs.html) |
| Dividers          | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/divider.xml) [[Specs]](https://material.google.com/components/dividers.html) |
| Expansion panels  | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/expansion_panel.xml) [[Specs]](https://material.google.com/components/expansion-panels.html) |
| Grid lists        | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/grid_list.xml) [[Specs]](https://material.google.com/components/grid-lists.html) |
| Lists             | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/list.xml) [[Specs]](https://material.google.com/components/lists.html) |
| Menus             | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/menu.xml) [[Specs]](https://material.google.com/components/menus.html) |
| Steppers          | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/stepper.xml) [[Specs]](https://material.google.com/components/steppers.html) |
| Subheaders        | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/subheader.xml) [[Specs]](https://material.google.com/components/subheaders.html) |
| Tooltips          | [[Source]](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/tooltip.xml) [[Specs]](https://material.google.com/components/tooltips.html) |


If a section of the Material Design specs is not in the above list, it may be because it has no values or is only available on desktop.

Note that the values for the following components are not available as they are already well implemented in Android: Selection controls, Sliders, Snackbars & toasts, Tabs, Text fields.


Usage
-----

Just add this dependency to your build.gradle:
```
compile 'blue.aodev:material-values:1.0.1'
```

The artifact is currently only available on jCenter, not mavenCentral.
Make sure that your buildscript repositories include jCenter.


You can now use the values referenced in the available values, for example:

| In xml | Programmatically (`blue.aodev.materialvalues.R`) |
| :--- | :--- |
| `@color/material_color_green_primary`                | `R.color.material_color_green_primary`
| `@dimen/material_list_two_line_dense_height`         | `R.dimen.material_list_two_line_dense_height`
| `@dimen/material_elevation_card_raised`              | `R.dimen.material_elevation_card_raised`
| `@dimen/material_typography_regular_title_text_size` | `R.dimen.material_typography_regular_title_text_size`


Remaining tasks
---------------

- Add missing values in Layout (Structure)
- Add missing values in Patterns (Navigation drawer, Scrolling techniques)
- Create a wiki to document the values


-----

Inspired by DmitryMalkovich's [material-design-dimens](https://github.com/DmitryMalkovich/material-design-dimens).

© 2016 Ao (Matthieu Esnault) - Released under [Apache-2.0 License](https://raw.githubusercontent.com/AoDevBlue/MaterialValues/master/LICENSE)

