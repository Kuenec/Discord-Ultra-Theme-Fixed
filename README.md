# Ultra (Fixed)

**A Smooth, Black Discord Theme - Updated & Working\!**

-----

## Overview

This theme is a fixed and updated version of the popular **Ultra** theme originally created by TheCommieAxolotl. The original theme is no longer maintained and has compatibility issues with current Discord versions. I've gone through and fixed the necessary values to make sure it works seamlessly again, while keeping the original aesthetic and functionality intact. All core values remain consistent with the original design.

-----

## Preview

![]("https://github.com/Kuenec/Discord-Ultra-Theme-Fixed/blob/main/Screenshot%202025-06-03%20093346.png?raw=true")

-----

## Installation

### For BetterDiscord

1.  **Download the theme:** Right-click [this link](https://github.com/Kuenec/Discord-Ultra-Theme-Fixed/blob/main/ultra-fixed.css) and select "Save link as..." to download the `ultra-fixed.css` file.
2.  **Open BetterDiscord Themes Folder:** In Discord, go to `User Settings` -\> `BetterDiscord` -\> `Themes`. Click on "Open Themes Folder".
3.  **Move the Theme:** Drag and drop the `ultra-fixed.css` file you downloaded into this folder.
4.  **Enable the Theme:** Go back to Discord, and you should see "Ultra (Fixed)" in your themes list. Toggle it on\!

### For Vencord

#### Method 1: Using the Themes Folder (Recommended for easier updates)

1.  **Download the theme:** Right-click [this link](https://github.com/Kuenec/Discord-Ultra-Theme-Fixed/blob/main/ultra-fixed.css) and select "Save link as..." to download the `ultra-fixed.css` file.
2.  **Open Vencord Themes Folder:** In Discord, go to `User Settings` -\> `Vencord` -\> `Themes`. Click on "Open Themes Folder".
3.  **Move the Theme:** Drag and drop the `ultra-fixed.css` file you downloaded into this folder.
4.  **Enable the Theme:** Go back to Discord, and you should see "Ultra (Fixed)" in your themes list. Toggle it on\!

#### Method 2: Using QuickCSS (Good for quick testing or small adjustments)

1.  **Copy the theme code:** Go to [this link](https://github.com/Kuenec/Discord-Ultra-Theme-Fixed/blob/main/ultra-fixed.css), click the "Raw" button, and copy all the CSS code.
2.  **Open QuickCSS:** In Discord, go to `User Settings` -\> `Vencord` -\> `QuickCSS`.
3.  **Paste the code:** Paste the copied CSS code into the QuickCSS editor.
4.  The theme should apply instantly. Remember that changes here are saved directly within Discord's Vencord settings.

-----

## Customization

This theme offers several custom CSS variables you can modify to personalize your experience. You can find these variables at the top of the `ultra-fixed.css` file, within the `:root` and `.theme-dark` selector.

To change these, you'll need to edit the `ultra-fixed.css` file directly (if using Method 1 for Vencord/BetterDiscord) or modify them in the QuickCSS editor (if using Method 2 for Vencord).

### Custom Variables Explained:

| Variable Name                | Default Value (in your code) | Description                                                                                                                                                                                                                                                                                                                                                                                         |
| :--------------------------- | :--------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--background-modifier-selected` | `rgba(0, 0, 0, 0)`         | Controls the **background color of a selected channel**. It's set to fully transparent (`0` alpha) by default, meaning no background highlight on selected channels. Change the last number (alpha) to `0.1` - `1` for visibility, or the RGB values for a different color.                                                                                                            |
| `--background-modifier-hover`    | `rgba(0, 0, 0, 0)`        | Controls the **background color of a channel when you hover over it**. Also fully transparent by default. Adjust the alpha for visibility, or RGB values for color. This is distinct from the hover *dot*.                                                                                                                                                                                              |
| `--background-modifier-active`   | `rgba(0, 0, 0, 0)`         | Controls the **background color of a channel when it's actively clicked/pressed**. Fully transparent by default.                                                                                                                                                                                                                                                                    |
| `--bg-base-primary`          | `#000000`                    | Sets the **primary background color** for various Discord elements, like sidebars and main content areas. This is what gives the theme its smooth black appearance.                                                                                                                                                                                                                 |
| `--font-primary`             | `"Lato"`                     | Defines the **main font** used throughout Discord's interface. You can change this to any font installed on your system or linked via `@import`.                                                                                                                                                                                                                              |
| `--font-code`                | `"Source Code Pro"`          | Defines the **font specifically for code blocks** in Discord messages.                                                                                                                                                                                                                                                                                                               |
| `--channel-icon`             | `#4a4a52`                    | Sets the **color of the default channel icons** (like the `#` for text channels).                                                                                                                                                                                                                                                                                                   |
| `--selected-indicator`       | `var(--brand-experiment, #e21c1c)` | Controls the **color of the small circle/dot that appears next to a currently selected channel**. It defaults to Discord's `--brand-experiment` color (often a blue/purple), or a fallback red if that's not defined. You can set it to any color like `#FF0000` for red.                                                                                              |
| `--hover-indicator`          | `var(--brand-experiment, #040faa)` | Controls the **color of the small circle/dot that appears when you hover over a channel**. Similar to `--selected-indicator`, it defaults to `--brand-experiment` or a fallback blue. Customize this to match your preferred hover highlight.                                                                                                                                 |
| `--unread-indicator`         | `var(--brand-experiment, #7309ff)` | Controls the **color of the small circle/dot that indicates unread messages** next to a channel. It also defaults to `--brand-experiment` or a fallback purple. Change this to make your unread channels stand out with a specific color.                                                                                                                                   |
