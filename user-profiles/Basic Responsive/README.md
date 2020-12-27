# Basic Responsive Theme

## Basic theme
Paste this into the box on your [profile](https://subeta.net/preferences.php?act=profile) page:
```
<style>
@import url('https://hongske.github.io/subeta/user-profiles/Basic%20Responsive/theme_v1.css')
</style>
```

## Options
There are several options to customise this theme, which have all been set using variables. To edit the variables, you'll have to add this snippet beneath your `@import` code:

```
:root {

}
```

Then you'll have to add variables from the tables below between those brackets. A full example would be:

```
<style>
@import url('https://hongske.github.io/subeta/user-profiles/Basic-Responsive/theme_v1.css')

:root {
  --colour_1: #b4d455;
}
</style>
```

### Colours
| Option | Code + default value |
| -------| -------------------- |
| Colour 1 | `--colour_1: #554b49;` |
| Colour 2 | `--colour_2: #232323;` |
| Colour 3 | `--colour_3: #9a2d2d;` |
| Colour 4 | `--colour_4: #4a060c;` |

### Fonts
| Option | Code + default value |
| -------| -------------------- |
| Font-family | `--font_family: 'Barlow !important';` |
| Font-size | `--font_size: 16px;` |
| Font-icons | `--font_icons: 'Material Icons';` |

### Borders
| Option | Code + default value |
| -------| -------------------- |
| Border-radius | `--border_radius: 0.25rem;` |

### Display headers
By default, all headers have been set to `display: block`. To hide a header, find the appropriate one in the table below and copy the code as-is (you don't have to edit it).
| Option | Code |
| -------| -------------------- |
| Achievements | `--display_header_achievements: none;` |
| Avatar | `--display_header_avatar: none;` |
| Blank | `--display_header_blank: none;` |
| Comment | `--display_header_comment: none;` |
| Comments | `--display_header_comments: none;` |
| Friends | `--display_header_friends: none;` |
| Interests | `--display_header_interests: none;` |
| Medals | `--display_header_medals: none;` |
| Options | `--display_header_options: none;` |
| Pets | `--display_header_pets: none;` |
| Profile | `--display_header_profile: none;` |
| Shops | `--display_header_shops: none;` |
| Stickers | `--display_header_stickers: none;` |
| Basic userinfo | `--display_header_userinfo1: none;` |
| Extra userinfo | `--display_header_userinfo2: none;` |
| Wishlist | `--display_header_wishlist: none;` |

### Display blocks
By default, all blocks have been set to `display: block`. To hide a header, find the appropriate one in the table below and copy the code as-is (you don't have to edit it).
| Option | Code |
| -------| -------------------- |
| Achievements | `--display_content_achievements: none;` |
| Avatar | `--display_content_avatar: none;` |
| Blank | `--display_content_blank: none;` |
| Comment | `--display_content_comment: none;` |
| Comments | `--display_content_comments: none;` |
| Friends | `--display_content_friends: none;` |
| Interests | `--display_content_interests: none;` |
| Medals | `--display_content_medals: none;` |
| Options | `--display_content_options: none;` |
| Pets | `--display_content_pets: none;` |
| Profile | `--display_content_profile: none;` |
| Shops | `--display_content_shops: none;` |
| Stickers | `--display_content_stickers: none;` |
| Basic userinfo | `--display_content_userinfo1: none;` |
| Extra userinfo | `--display_content_userinfo2: none;` |
| Wishlist | `--display_content_wishlist: none;` |

## To do's
1. Add options
2. Update README