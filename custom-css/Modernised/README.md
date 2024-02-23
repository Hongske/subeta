# Modernised Theme

## Basic theme

Paste this into the box on your [CustomCSS page](https://subeta.net/preferences.php?act=customcss):
```
@import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css')
```


## Options

The theme uses CSS Variables, which can be overridden to customise the theme.
To do so, you'll need to add the following snippet **after** your `@import` code:
```
:root {
    /* insert your CSS-variables here */
}
```

Then add your overrides between the curly brackets. An example would be:
```
@import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css');

:root {
    --color-primary: #b4d455;
    --display-floating-item: none;
}
```

### There are 2 types of CSS Variables that can be used in the theme (so far):
- Colours: Begin with `--colour` and need a valid CSS colour value.
  - Examples of valid values are `crimson`, `#DC143C` and `rgb(220, 20, 60)`.
  - [You can find more info about valid CSS colour values here](https://www.w3schools.com/cssref/css_colors_legal.php).
  - These are used to customise the colours on the website.
- Display: Begin with `--display` and need a valid CSS display value.
  - Examples of valid values are `none`, `block` and `flex`.
  - [You can find more info about valid CSS display values here](https://www.w3schools.com/cssref/pr_class_display.php).
  - These are most often used to _hide_ certain parts of the website, which can be done by changing the value to `none`.

### Overview of all options:

| Code                      | Option                                                                    |
|---------------------------|---------------------------------------------------------------------------|
| `--color-primary`         | Main colour. **Default:** `#9BA84F`.                                      |
| `--color-blue`            | Blue colour. **Default:** `#0DCAF0`.                                      |
| `--color-green`           | Green colour. **Default:** `#20C997`.                                     |
| `--color-red`             | Red colour. **Default:** `#DC3545`.                                       |
| `--color-yellow`          | Red colour. **Default:** `#FFC107`.                                       |
| `--display-floating-item` | Display for floating items (e.g. survival flowers). **Default:** `block`. |