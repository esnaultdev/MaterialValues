# Typography

## Script families

The values for typography depend on the script family of your text.

The values are defined using the following prefixes:

| Script family | Resource prefix |
| ------------- | --------------- |
| English-like  | `regular`       |
| Dense         | `dense`         |
| Tall          | `tall`          |


## Size

| Text type  | Value |
| ---------- | ----- |
| Display 4  | `@dimen/material_typography_FAMILY_display_4_text_size`  |
| Display 3  | `@dimen/material_typography_FAMILY_display_3_text_size`  |
| Display 2  | `@dimen/material_typography_FAMILY_display_2_text_size`  |
| Display 1  | `@dimen/material_typography_FAMILY_display_1_text_size`  |
| Headline   | `@dimen/material_typography_FAMILY_headline_text_size`   |
| Title      | `@dimen/material_typography_FAMILY_title_text_size`      |
| Subheading | `@dimen/material_typography_FAMILY_subheading_text_size` |
| Body 2     | `@dimen/material_typography_FAMILY_body_2_text_size`     |
| Body 1     | `@dimen/material_typography_FAMILY_body_1_text_size`     |
| Caption    | `@dimen/material_typography_FAMILY_caption_text_size`    |
| Button     | `@dimen/material_typography_FAMILY_button_text_size`     |


## Style

These styles use the previously defined text sizes and also applies the good font-weight.

| Text type  | Value |
| ---------- | ----- |
| Display 4  | `@style/MaterialTypography.FAMILY.Display4`   |
| Display 3  | `@style/MaterialTypography.FAMILY.Display3`   |
| Display 2  | `@style/MaterialTypography.FAMILY.Display2`   |
| Display 1  | `@style/MaterialTypography.FAMILY.Display1`   |
| Headline   | `@style/MaterialTypography.FAMILY.Headline`   |
| Title      | `@style/MaterialTypography.FAMILY.Title`      |
| Subheading | `@style/MaterialTypography.FAMILY.Subheading` |
| Body 2     | `@style/MaterialTypography.FAMILY.Body2`      |
| Body 1     | `@style/MaterialTypography.FAMILY.Body1`      |
| Caption    | `@style/MaterialTypography.FAMILY.Caption`    |
| Button     | `@style/MaterialTypography.FAMILY.Button`     |


## Color

*Some values are missing and will be included in the next version.*


## Locale prefix

A `locale` prefix is also available in the resources.

This prefix will choose the script family corresponding to the current locale, and default to `regular`.

Its usage is not recommended currently as the typography will change even if your text is not translated for the locale.

