# Expand Sidebar On Hover

Expands the collapsed sidebar when hovering to reveal tab titles and workspace information.

## Background

The [original sidebar expand on hover mod](https://github.com/Uiniel/zen-mods/tree/main/sidebar-expand-on-hover) stopped working with recent Zen Browser updates. This is a rewritten version that works with the current browser release.

## Installation

### Method 1: Zen Mods System

1. Copy this folder to your Zen Browser mods directory
2. Enable the mod in Zen Browser settings

### Method 2: Manual Installation

1. Navigate to `about:support` in Zen Browser
2. Click "Open Profile Folder"
3. Create a `chrome` folder if it doesn't exist
4. Copy `userChrome.css` into the `chrome` folder
5. Restart Zen Browser

Note: You may need to enable custom CSS in Zen Browser settings for manual installation.

## Configuration

Edit the CSS variables in `userChrome.css` to customize behavior:

```css
:root {
    --hover-width: 230px;
    --hover-transition: 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}
```

- `--hover-width`: Width of the expanded sidebar
- `--hover-transition`: Animation duration and easing

## Requirements

- Zen Browser with collapsed sidebar layout enabled
- Custom CSS support enabled (for manual installation)

## License

MIT
