# Obsidian CSS Snippets

A collection of custom CSS snippets for Obsidian, designed to enhance your note-taking experience.
![Obsidian CSS Snippets](gifs/Obsidian%20CSS%20Snippets.gif)


## Table of Contents

1. [00 - Sleek Zen](#00---sleek-zen)
2. [01 - Zen](#01---zen)
3. [02 - Sidebar Folder Colors](#02---sidebar-folder-colors)
4. [03 - Fat Sidebar Folders](#03---fat-sidebar-folders)
5. [04 - Custom Heading Colors](#04---custom-heading-colors)
6. [05 - Fat Heading](#05---fat-heading)
7. [06 - Text Formatting](#06---text-formatting)
8. [07 - Hover Properties](#07---hover-properties)
9. [08 - Translucent View](#08---translucent-view)
10. [09 - Hide Scrollbar](#09---hide-scrollbar)
11. [10 - Solid Black Background](#10---solid-black-background)

---

## 00 - Sleek Zen
![00 - Sleek Zen](gifs/00%20-%20sleek-zen.gif|)
**File:** `00 - sleek-zen.css`  

### Description
Ultimate Sleek Zen Mode - "The cleanest workspace possible. Everything is there, nothing is visible."

### Features
- **Top Tab Bar:** Collapses to invisible trigger area (6px), expands on hover to 40px
- **Left Sidebar:** Collapses to 12px trigger, expands to 350px on hover
- **Right Sidebar:** Collapses to 12px trigger, expands to 350px on hover
- **Ribbon:** Fades to opacity 0, visible on hover
- **Status Bar:** Hidden (opacity 0), visible on hover
- **Title Bar:** Hidden, visible on hover
- **View Header:** Hidden, visible on hover
- **Internal Controls:** Sidebar buttons and headers collapse to 2px, expand to 40px

---

## 01 - Zen
![01 - Zen](gifs/01%20-%20zen.gif)
**File:** `01 - zen.css`  

### Description
Simpler Zen Mode implementation - Hide UI elements and show them on hover.

---

## 02 - Sidebar Folder Colors
![02 - Sidebar Folder Colors](gifs/02%20-%20sidebar-folder-colors.gif)
**File:** `02 - sidebar-folder-colors.css`  

### Description
Colored sidebar items by CyanVoxel v2.0.0. Modified for subtle muted contrast spectrum (prefixes 00-15) and grays (93-99).

### Color Spectrum (00-15)
- **00:** Muted Red - `rgba(170, 70, 80, 0.95)`
- **01:** Muted Crimson - `rgba(185, 85, 95, 0.95)`
- **02:** Muted Red-Orange - `rgba(200, 100, 70, 0.95)`
- **03:** Muted Orange - `rgba(215, 120, 60, 0.95)`
- **04:** Muted Amber - `rgba(220, 150, 70, 0.95)`
- **05:** Muted Gold - `rgba(210, 170, 80, 0.95)`
- **06:** Muted Yellow-Green - `rgba(180, 180, 90, 0.95)`
- **07:** Muted Lime Green - `rgba(150, 190, 100, 0.95)`
- **08:** Muted Emerald Green - `rgba(120, 180, 130, 0.95)`
- **09:** Muted Teal - `rgba(90, 170, 160, 0.95)`
- **10:** Muted Sky Blue - `rgba(80, 140, 170, 0.95)`
- **11:** Muted Blue - `rgba(70, 110, 180, 0.95)`
- **12:** Muted Indigo - `rgba(90, 90, 190, 0.95)`
- **13:** Muted Violet - `rgba(120, 80, 180, 0.95)`
- **14:** Muted Magenta - `rgba(150, 70, 170, 0.95)`
- **15:** Muted Rose - `rgba(170, 70, 140, 0.95)`

### Gray Scale (93-99)
- **93:** Very Pale Cool Gray - `rgba(180, 185, 190, 0.95)` (most visible)
- **94-98:** Gradually decreasing visibility
- **99:** Mid Cool Gray - `rgba(120, 125, 130, 0.65)` (least visible)

### Usage
Folders with prefixes `00` through `15` and `93` through `99` will be automatically colored based on their prefix.

---

## 03 - Fat Sidebar Folders
![03 - Sidebar Folder Colors](gifs/03%20-%20fat-sidebar-folders.gif)
**File:** `03 - fat-sidebar-folders.css`  

### Description
Modified version of CyanVoxel's colored sidebar snippets with subtle button/chip layout styling.


---

## 04 - Custom Heading Colors
![04 - Custom Heading Colors](gifs/04%20-%20custom-heading-colors.gif)
**File:** `04 - custom-heading-colors.css`  

### Description
Custom heading colors with subtle muted contrast for both reading view and live preview.

### Heading Color Scheme
- **H1:** Dusty Blue - `rgba(122, 165, 194, 0.9)`
- **H2:** Muted Sage Green - `rgba(143, 184, 159, 0.9)`
- **H3:** Soft Ochre/Amber - `rgba(212, 160, 99, 0.9)`
- **H4:** Gentle Lavender - `rgba(164, 140, 191, 0.9)`
- **H5:** Rose Dust - `rgba(196, 132, 160, 0.9)`
- **H6:** Subtle Teal - `rgba(136, 199, 197, 0.9)`

---

## 05 - Fat Heading
![05 - Fat Heading](gifs/05%20-%20fatheading.gif)
**File:** `05 - fatheading.css`  

### Description
Boxed headings effect with structure, collapse icons, and visual styling. Use with custom text color snippet.

---

## 06 - Text Formatting
![06 - Text Formatting](gifs/06%20-%20text-formatting.gif)
**File:** `06 - text-formatting.css`  

### Description
Custom colors for italic, bold, strikethrough, and highlight text formatting.

### Color Scheme
- **Italic:** Muted Green - `#9ACD95`
- **Bold:** Dusty Rose/Mauve - `#DE819C` (font-weight: 700)
- **Bold + Italic:** Dusty Rose/Mauve - `#DE819C` (both styles applied)
- **Strikethrough:** Muted Mauve - `#A17087` (opacity: 0.75)
- **Highlight:** Muted Pastel Green - `rgba(160, 190, 170, 0.45)`

---

## 07 - Hover Properties
![07 - Hover Properties](gifs/07%20-%20hover-properties.gif)
**File:** `07 - hover-properties.css`  

### Description
Hide properties panel and show on hover with smooth transitions.

### Features
- Properties panel collapses to 2.7rem height
- Reduced opacity (0.6) when collapsed
- Smooth transitions (250ms/300ms)
- Works in both edit and preview mode
- Disables Minimal theme table hover effect

---

## 08 - Translucent View
![08 - Translucent View](gifs/08%20-%20translucent-view.gif)
**File:** `08 - translucent-view.css`  

### Description
Translucent view for Hyprland compatibility - "Glassy look for tiled window managers."

### Features
- Transparent main window background
- Translucent panes and splits
- Backdrop blur effects (5px)
- Adaptive to light/dark mode using `--mono-rgb-0`
- Special handling for modals/popovers (higher opacity for readability)

---

## 09 - Hide Scrollbar
![09 - Hide Scrollbar](gifs/09%20-%20hide-scrollbar.gif)
**File:** `09 - hide-scrollbar.css`  

### Description
Completely hides all scrollbars across the entire app (always invisible).

### Features
- Uses webkit pseudo-elements for Obsidian/Electron
- Hides track, thumb, and corner
- Sets width and height to 0
- Forces transparent background
- Overrides body scrollbar variables

---

## 10 - Solid Black Background
![10 - Solid Black Background](gifs/10%20-%20solid-black-bg.gif|)
**File:** `10 - solid-black-bg.css`  

### Description
Pure black backgrounds for Hyprland compositor takeover - "Let the compositor handle all transparency."

### Features
- Forces everything to pure black (`#000000`)
- Overrides all background CSS variables
- Affects app container, workspace, sidebars, editor, modals
- Fullscreen mode compatible


