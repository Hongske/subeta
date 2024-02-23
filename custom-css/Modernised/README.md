# Modernised Theme

## Basic theme
Paste this into the box on your [CustomCSS](https://subeta.net/preferences.php?act=customcss) page.
```
    @import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css')
```

## Options
The theme uses CSS Variables, which can be overridden to customise the theme.
To do so, you'll need to add the following snippet _above_ your `@import` code:
```
:root {
    /* insert your CSS-variables here */
}
```

Then add your overrides between the curly brackets. An example would be:
```
:root {
    --color-primary: #b4d455;
    --display-floating-item: none;
}

@import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css')
```

These are the CSS Variables you can use in the theme:
### Colours
These options are to customise the colours used in the theme.
| Code                      | Option                                                               |
| `--color-primary`         | Main color of the theme, default is `#9BA84F`.                       |
| `--color-blue`            | Blue color, used for alerts etc, default is #0DCAF0.                 |
| `--color-green`           | Green color, used for alerts etc, default is #20C997.                |
| `--color-red`             | Red color, used for alerts etc, default is #DC3545.                  |
| `--color-yellow`          | Red color, used for alerts etc, default is #FFC107.                  |

### Display options
These options are to hide certain parts of the website. Default values are usually either `block` or `flex`.
To hide these options on the website, simply use the value `none` (see example above).
| `--display-floating-item` | Display-property for floating items (e.g. survival flowers). Default value is `block`. |