# Modernised Theme

This is my first official CustomCSS Theme! Here's the feature-list so far:
- Modernised layout for Subeta
  - Unified design elements (buttons, spacing, ...)
  - Updated icons (using FontAwesome 6.5.1)
- Mobile version for smartphone users
  - Optimised layouts (so things aren't squished so much on the screen)
  - Smaller item- and pet-images
  - No NPC-images
- More emphasised styling for wishlist items
- Options for custom theme colours
- Options for hiding parts of the website

<br/>

## Installing the theme
To get started, paste the following code into the box on your [CustomCSS page](https://subeta.net/preferences.php?act=customcss):
```css
@import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css')
```

<br/>

## Customising the theme
To customise this theme, you'll need to override certain CSS Variables. To do so, you'll need to add the following snippet **after** your `@import` code:
```css
:root {
    /* insert your theme options here */
}
```

Then, add your overrides between the curly brackets. An example would be:
```css
@import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css');

:root {
    --color-primary: #b4d455;
    --display-floating-item: none;
}
```
<br/>

### There are 2 categories of CSS Variables that can be used in the theme (so far):
- Colours: Begin with `--colour` and need a valid CSS colour value.
  - Examples of valid values are `crimson`, `#DC143C` and `rgb(220, 20, 60)`.
  - [You can find more info about valid CSS colour values here](https://www.w3schools.com/cssref/css_colors_legal.php).
  - These are used to customise the colours on the website.
- Display: Begin with `--display` and need a valid CSS display value.
  - Examples of valid values are `none`, `block` and `flex`.
  - [You can find more info about valid CSS display values here](https://www.w3schools.com/cssref/pr_class_display.php).
  - These are most often used to _hide_ certain parts of the website, **which can be done by changing the value to `none`.**

<br/>

### Overview of all available options:

| Code                                  | Option                                                       | Default value |
|---------------------------------------|--------------------------------------------------------------|---------------|
| `--color-primary`                     | Main theme colour.                                           | `#9BA84F`     |
| `--color-blue`                        | Blue colour, used for alerts.                                | `#0DCAF0`     |
| `--color-green`                       | Green colour, used for alerts, buttons, etc.                 | `#20C997`     |
| `--color-red`                         | Red colour, used for alerts, buttons, etc.                   | `#DC3545`     |
| `--color-yellow`                      | Yellow colour, used for alerts.                              | `#FFC107`     |
| `--display-floating-item`             | Display floating items (e.g. survival flowers).              | `block`       |
| `--display-hustler`                   | Display hustler.                                             | `block`       |
| `--display-sidebar-battlepet-buttons` | Display buttons for battlepet in the sidebar.                | `table`       |

<br/>

## Credits
- [spacemage](https://subeta.net/users/spacemage), for their [year indicators for yearly event shops](https://subeta.net/forums.php/gotopost/66366953)
- [Sorcerer](https://subeta.net/users/Sorcerer), for their [very helpful collection of Custom CSS](https://karlpiper.com/subeta/customcss/)
- Icons by [FontAwesome](https://fontawesome.com/)
- Roboto font by [Google Fonts](https://fonts.google.com/specimen/Roboto)

<br/>

## Changelog (most recent first)
### 2024/02/25
- Added extra styling (and options) for sidebar-widgets, inspired by [the Widget Overhaul](https://karlpiper.com/subeta/customcss/#Overhaul-All-Widgets) that [Sorcerer](https://subeta.net/users/Sorcerer) made.

### 2024/02/24
- Added styling for [the special shops page](https://subeta.net/ss.php).
- Added button-styles for the link back to Shinwa on quest-pages (after finishing the quest).
- Fixed sidebar toggling so that content correctly displays over the whole page when you hide the sidebar.
- Fixed events counter in the sidebar, so that it overflows correctly.
- Fixed click-area for floating items so that it's limited to the item itself.

### 2024/02/23
- Initial commit (rewrite of the original theme)