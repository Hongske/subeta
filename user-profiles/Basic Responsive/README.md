# Basic Responsive Theme

## Basic theme
Paste this into the box on your [CustomCSS](https://subeta.net/preferences.php?act=customcss) page.
`@import url('https://hongske.github.io/subeta/user-profiles/Basic-Responsive/theme_v1.css')`

## Options
There are several options to customise this theme, which have all been set using variables. To use these options, you'll need to overwrite the variables, which you can do by adding this snippet beneath your `@import` code:

```
:root {

}
```

Then you'll have to add variables from the tables between those brackets. An example would be:

```
:root {
  --colour_1: #b4d455;
}
```

### Options - Colours
| Option | Code + default value |
| -------------- | --------------------- |
| Colour 1 | `--colour_1: #554b49;` |
| Colour 2 | `--colour_2: #232323;` |
| Colour 3 | `--colour_3: #9a2d2d;` |
| Colour 4 | `--colour_4: #4a060c;` |

### Options - Fonts
| Option | Code + default value |
| Font-family | `--font_family: 'Barlow !important';` |
| Font-size | `--font_size: 16px;` |
| Font-icons | `--font_icons: 'Material Icons';` |

### Options - Borders
| Border-radius | `--border_radius: 0.25rem;` |

## To do's
1. Add options
2. Update README

```

```
