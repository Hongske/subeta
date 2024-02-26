# Modernised Theme

## ⭐ Features
Below features are mostly for both desktop *and* mobile views, but features preceded by 👁‍🗨 are mobile-only!

<details>
<summary>📌 List of general layout changes</summary>

- Modernised the layout
  - Unified various design elements (banners, menu's, buttons, ...)
  - Improved readability of various bits and bobs
  - Upated icons (using FontAwesome 6.5.1)
  - Gave the total layout a max-width, so that it doesn't look so stretched on bigger screens
  - Added mobile version for smartphone users
- Modified main menu-bar
  - Fixed the main menu-bar to the top of the page, so that it's always in view (even if you scroll down)
  - Reversed the order of menu-items
  - Added icons to the menu-items
  - 👁‍🗨 Modified menu dropdowns so that they're shown in 2 columns
  - 👁‍🗨 Removed text in the menu-items, so that only icons are shown
  - 👁‍🗨 Removed nested dropdowns (e.g. Freinds, Pets, ...)
- Modified bookmarks
  - Fixed the bookmarks-bar to the top of the page instead of the side, underneath the main menu-bar
  - 👁‍🗨 Removed bookmarks
- Modified sidebar
  - Made sidebar wider
  - Moved the time-display to the left and made it bigger
  - Modified the sidebar-toggle so that it's an icon instead of text
  - Modified sidebar-widgets so they can only be dragged via their icon (instead of the whole widget)
  - Added custom styling to various sidebar-widgets
  - Added option `--display-sidebar-battlepet-buttons` to hide buttons for the battlepet-widget
- Modified item-views
  - Modified the item orientation so that item-images and -text are shown next to each other (instead of below each other)
  - Modified styling for wishlist-items so that they're more obvious
  - Removed styling for wishlist-items in forum-images and signatures
  - 👁‍🗨 Resized item-images so they take up less space
- Added other general options
  - [ ] Added option `--display-all-text` to hide **all** intro- and flavor-texts
  - Added option `--display-floating-item` to hide floating items (like flowers during Survival)
  - Added option `--display-hustler` to hide Hustler-banner
  - Added options to modify theme colours ([see overview of all available options](#overview-of-all-available-options))
</details>
<details>
<summary>📌 List of page changes</summary>

- **Vending**
  - Modified the items so that they're easier to read
  - 👁‍🗨 Changed the image of the vending machine to a big red button
- **Quests**
  - Restyled **[main quests](https://subeta.net/quests.php/wizard)**
    - [ ] Added option to hide intro-text
    - Removed the item-description on hover (less distraction)
  - Restyled **[Major Drills' quests](https://subeta.net/explore/major_drills.php)**
  - Restyled **[Shinwa's quests](https://subeta.net/explore/goddess.php)**
  - 👁‍🗨 Removed NPC-images
- Restyled **[Your Events](https://subeta.net/events.php)**
</details>
<details>
<summary>📌 List of page changes [Commerce]</summary>

- **[Special Shops](https://subeta.net/ss.php)**
  - Restyled overview of shops to match the styling of [Subeta » News » Dailies](https://subeta.net/dailies.php)
  - Restyled [Esther's Shop](https://subeta.net/ss.php/esther#/shop/), [L'Amour Parlor](https://subeta.net/ss.php/louis#/shop/), [Libertine Lounge](https://subeta.net/ss.php/lounge#/shop/), [New Years Shop](https://subeta.net/ss.php/newyears#/shop/), [Steamworks Menagerie](https://subeta.net/ss.php/menagerie#/shop/) and [Zombie Den](https://subeta.net/ss.php/skitters#/shop/)
    - Restyled the items
    - Removed the sidebar with NPC-image, NPC name and buttons
- **[Your Shops](https://subeta.net/user_shops.php/mine)**
  - [ ] Restyled overview of shops and galleries
  - Restyled **Edit Items**
    - Added option `--display-yourshop-item-category` to hide categories (from the filters *and* items-list)
    - Removed Item ID from the items-list
  - Restyled **Quick Stock**
    - Replaced locations' text with icons
    - [ ] Added option to hide "delete"-option completely
    - 👁‍🗨 Removed the "delete"-option
  - Restyled **Autopricer**
    - Removed info-text about new prices (lowest, average and no change)
    - Removed old price and average price columns from results table, so only lowest price is visible
    - Restyled pricing to emphasise whether a price has gone up or down
  - Restyled **Profits**
    - 👁‍🗨 Removed piggybank-images
  - Restyled **Sales History**
    - Added option `--display-yourshop-sales-info` to hide info-text
</details>
<details>
<summary>📌 List of page changes [Interact]</summary>

- **[Forums](https://subeta.net/forums.php)**
  - Restyled **[Forum Home](https://subeta.net/forums.php)**
    - Added option `--display-forum-pulse` to completely hide forum-pulse
    - Replaced "collapse"-text with an icon (same icon as for sidebar-widgets)
    - Removed images for forum boards
    - Modified order of forum-details so that the list of subforums is last
    - Restyled **Subforums**
      - Topics with unread posts have their text in bold
      - Topics with unread posts also have a bullhorn icon, which you can click to go the most recent unread post
      - Topics you have replied on have their text in black
      - Topics you haven't replied on have their text in your theme's accent colour
    - Restyled **Topics**
      - Removed user avatars, leashed pets and options to like avatar/post
      - Added option `--display-forum-post-image` to hide post images
      - Added option `--display-forum-post-signature` to hide signatures
      - 👁‍🗨 Removed forum images and signatures
      - Fixed reply-form to the bottom of the page, so that it's always visible
      - Removed the ping-options from the reply form
      - 👁‍🗨 Removed the formatting-options from the reply form
</details>
<details>
<summary>📌 List of page changes [Personal]</summary>

- Restyled **[Account Search](https://subeta.net/isearch.php)**
- Restyled **[Achievements](https://subeta.net/achievements.php)**
  - Removed achievement-counter at the top of the page
  - Resized the sidebar
  - 👁‍🗨 Removed subcategories
- Restyled **Comments**
- Restyled **[Inventory](https://subeta.net/inventory.php)**
  - Replaced the lock-images with colour-coded icons
  - Restyled the item detail page
    - [ ] Added option to hide toggle-buttons and show the contents instead, for books, food, toys and treasure
    - [ ] Added option to hide pets from the toggle-dropdowns
- Restyled **[Pets](https://subeta.net/pets.php)**
  - [ ] Added option to always show the pet dropdown-menu
  - [ ] Added option to put specific links in bold, in the pet dropdown-menu
  - [ ] Added option to have a set number of pets per row
  - [ ] Added option to have an automatic number of pets per row (calculated based on number of pets)
  - Added icons for hunger and happiness
  - Modified icon for likes
- **Vault**
  - Restyled **[Currency Storage](https://subeta.net/explore/vaults.php?vault=currency)**
  - Restyled **[Item Storage](https://subeta.net/explore/vaults.php?vault=item)**
    - Removed flavor-image and -text
- Restyled **[Wishlist](https://subeta.net/wishlists.php)**
</details>
<details>
<summary>📌 List of page changes [Subeta]</summary>

- **[Explore » Darkside » Ultimate Pet Zapper](https://subeta.net/explore/zapper.php)**
  - Removed NPC-image
  - Added option `--display-pet-zapper-warning` to hide warning-text
  - Added option `--display-pet-zapper-intro` to hide intro-text
  - Added option `--display-pet-zapper-adoption` to hide adoption-text
- **[Explore » Shadowglen » Crypts](https://subeta.net/explore/crypts.php)**
  - Made the crypts-map-images scrollable on mobile
  - 👁‍🗨 Removed NPC-image
- **[Explore » Shengui Guo » Floating Market](https://subeta.net/explore/shengui_guo/river.php)**
  - Restyled **[Dara's Darlings](https://subeta.net/explore/shengui_guo/dara.php)**, **[Fine Fabrics](https://subeta.net/explore/shengui_guo/clothing.php)** and **[Fresh and Flavorful](https://subeta.net/explore/shengui_guo/ujin.php)**
    - [ ] Added option to hide intro-text
    - 👁‍🗨 Removed intro-text
    - 👁‍🗨 Removed NPC-image
- **Games » Battle**
  - Removed images in the menu-bar
  - Restyled **[Training Center](https://subeta.net/explore/train.php)**
    - Removed NPC-image
    - Added option `--display-battle-training-intro` to hide intro-text
    - Added option `--display-battle-training-warning` to hide warning about level cap and autotraining
    - Added option `--display-battle-training-auto` to hide autotraining buttons
    - [ ] Added option to have a set number of pets per row
    - [ ] Added option to have an automatic number of pets per row (calculated based on number of pets)
    - [ ] Added option to hide specific pets
- **[Games » Chance » Fishing](https://subeta.net/games/fishing.php)**
  - 👁‍🗨 Removed NPC-image
- **[Games » Chance » Scratchcards](https://subeta.net/games/scratchcards.php)**
  - 👁‍🗨 Removed NPC-image
- **Games » Collections**
  - Restyled **Plushie**, **Trading Card**, **Beanbag**, **Pumpkin**, **Pastry** and **Tile** collections
  - Restyled **[Minion Zoo](https://subeta.net/games/minions/index.php)**
    - Removed all gaming options so that it's just a collection
- **[News](https://subeta.net/news.php)**
  - Moved Check Out, Upcoming and Daily to be above the posts (instead of next to them)
  - [ ] Added option to hide Check Out
  - [ ] Added option to hide Upcoming
  - [ ] Added option to hide Daily
  - [ ] Added option to hide Daily » Dailies
  - [ ] Added option to hide Daily » Recycle Beast
  - [ ] Added option to hide Daily » Potion Lottery Winner
  - Removed daily support goal (but only because it doesn't seem to work anymore)
  - Restyled **[Dailies](https://subeta.net/dailies.php)**
- **[Subetapedia](https://subeta.net/subetapedia/)**
  - [ ] Restyle overview (so links all have same style and non-links are removed)
  - [ ] Restyle pages
</details>

<br/>

## ⭐ Installing the theme
To get started, paste the following code into the box on your [CustomCSS page](https://subeta.net/preferences.php?act=customcss):
```css
@import url('https://hongske.github.io/subeta/custom-css/Modernised/theme.css')
```

<br/>

## ⭐ Customising the theme
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
    --display-battle-training-intro: none;
    --display-battle-training-warning: none;
}
```

- [ ] Write a script to auto-generate needed import & :root-code, based on checkboxes
<br/>

### There are 2 categories of CSS Variables that can be used in the theme (so far):
- Colours:
  - Variables begin with `--colour` and need a valid CSS colour value
  - Examples of valid values are `crimson`, `#DC143C` and `rgb(220, 20, 60)`
  - [You can find more info about valid CSS colour values here](https://www.w3schools.com/cssref/css_colors_legal.php)
  - These are used to customise the colours on the website
- Display:
  - Variables begin with `--display` and need a valid CSS display value
  - Examples of valid values are `none`, `block` and `flex`
  - [You can find more info about valid CSS display values here](https://www.w3schools.com/cssref/pr_class_display.php)
  - These are most often used to _hide_ certain parts of the website, **which can be done by changing the value to `none`**

<br/>

### Overview of all available options:

| Colour options                        | Info                                                                      | Default value |
|---------------------------------------|---------------------------------------------------------------------------|---------------|
| `--color-primary`                     | Main theme colour                                                         | `#9BA84F`     |
| `--color-blue`                        | Blue colour, used for alerts                                              | `#0DCAF0`     |
| `--color-green`                       | Green colour, used for alerts, buttons, etc                               | `#20C997`     |
| `--color-red`                         | Red colour, used for alerts, buttons, etc                                 | `#DC3545`     |
| `--color-yellow`                      | Yellow colour, used for alerts                                            | `#FFC107`     |

<br/>

| Display options                       | Info                                                                      | Default value |
|---------------------------------------|---------------------------------------------------------------------------|---------------|
| `--display-sidebar-battlepet-buttons` | General » Sidebar » Hide buttons for the battlepet widget                 | `block`       |
| `--display-floating-item`             | General » Hide floating items (like flowers during survival)              | `block`       |
| `--display-hustler`                   | General » Hide Hustler-banner                                             | `block`       |
| `--display-yourshop-item-category`    | Commerce » Your Shops » Edit Items » Hide categories-options              | `block`       |
| `--display-yourshop-sales-info`       | Commerce » Your Shops » Sales History » Hide info-text                    | `block`       |
| `--display-forum-pulse`               | Interact » Forums » Home » Hide forum pulse                               | `block`       |
| `--display-forum-post-image`          | Interact » Forums » Hide post images                                      | `block`       |
| `--display-forum-post-signature`      | Interact » Forums » Hide signatures                                       | `block`       |
| `--display-pet-zapper-warning`        | Explore » Darkside » Ultimate Pet Zapper » Hide warning-text              | `block`       |
| `--display-pet-zapper-intro`          | Explore » Darkside » Ultimate Pet Zapper » Hide intro-text                | `block`       |
| `--display-pet-zapper-adoption`       | Explore » Darkside » Ultimate Pet Zapper » Hide adoption-text             | `block`       |
| `--display-battle-training-intro`     | Subeta » Games » Battle » Training Center » Hide intro-text               | `block`       |
| `--display-battle-training-warning`   | Subeta » Games » Battle » Training Center » Hide warning-text             | `block`       |
| `--display-battle-training-auto`      | Subeta » Games » Battle » Training Center » Hide autotraining buttons     | `block`       |

<br/>

## ⭐ Credits
- [spacemage](https://subeta.net/users/spacemage), for their [year indicators for yearly event shops](https://subeta.net/forums.php/gotopost/66366953)
- [Sorcerer](https://subeta.net/users/Sorcerer), for their [very helpful collection of Custom CSS](https://karlpiper.com/subeta/customcss/)
- Icons by [FontAwesome](https://fontawesome.com/)
- Roboto font by [Google Fonts](https://fonts.google.com/specimen/Roboto)

<br/>

## ⭐ Changelog (most recent first)
### 2024/02/26
- Rewrote the page-specific section, for easier expansion considering the design patterns on the current Subeta website
- Added `--display-battle-training-intro` option to hide Jim's intro-text in the Training Center
- Added `--display-battle-training-warning` option to hide Jim's warning about level cap and autotraining at the Training Center
- Added `--display-battle-training-auto` option to hide autotraining options at the Training Center
- Added `--display-forum-pulse` option to completely hide forum-pulse at the Forums
- Added `--display-forum-post-image` option to hide forum images in posts at the Forums
- Added `--display-forum-post-signature` option to hide signatures in posts at the Forums
- Added `--display-pet-zapper-warning` option to hide warning about the pet zapper at the Ultimate Pet Zapper
- Added `--display-pet-zapper-intro` option to hide Euclid's intro-text at the Ultimate Pet Zapper
- Added `--display-pet-zapper-adoption` option to hide message about adopting a Qrykee or Yaherra at the Ultimate Pet Zapper
- Added `--display-yourshop-item-category` option to hide category-search (in both the filter- and item-list) for Your Shop » Edit Items
- Added `--display-yourshop-sales-info` option to hide info-text for Your Shop » Sales History

### 2024/02/25
- Added extra styling for sidebar-widgets, inspired by [the Widget Overhaul](https://karlpiper.com/subeta/customcss/#Overhaul-All-Widgets) that [Sorcerer](https://subeta.net/users/Sorcerer) made
- Added `--display-sidebar-battlepet-buttons` option to hide battlepet buttons in the sidebar, again inspired by Sorcerer's Widget Overhaul (see link above)
- Added minor layout tweaks for Ruffie Raffle, after you get a doll (mostly mobile)
- Fixed spacing for the Ruffie Raffle buttons, after you get a doll

### 2024/02/24
- Added styling for [the special shops page](https://subeta.net/ss.php)
- Added button-styles for the link back to Shinwa on quest-pages (after finishing the quest)
- Fixed sidebar toggling so that content correctly displays over the whole page when you hide sidebar
- Fixed events counter in the sidebar, so that it overflows correctly
- Fixed click-area for floating items so that it's limited to the item itself

### 2024/02/23
- Initial commit (rewrite of the original theme)