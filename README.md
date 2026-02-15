# Reign 2e Character Sheet Artwork

Custom artwork and visual assets for the Reign 2e Foundry VTT system, inspired by Game of Thrones medieval aesthetic with clean, simple design principles.

## Theme

**Medieval Fantasy** - Dark, elegant, and functional. Think Game of Thrones meets simplified RPG design.

### Design Principles

- **Simplicity**: Clean lines, readable fonts, minimal clutter
- **Medieval Elements**: Celtic knots, crowns, swords, heraldic designs
- **Muted Colors**: Parchment backgrounds, dark borders, metallic accents
- **Functionality**: Art supports readability, doesn't distract

## Assets

### Body Silhouette (`body-silhouette.svg`)

- Human figure for hit location reference
- Front-facing male silhouette
- Clearly marked hit zones:
  - **10**: Head
  - **7-9**: Torso
  - **5-6**: Right Arm
  - **3-4**: Left Arm
  - **2**: Right Leg
  - **1**: Left Leg

### Border Ornaments

- `border-top.svg` - Top decorative border with crown motif
- `border-corner.svg` - Corner ornaments (Celtic knots)
- `divider-horizontal.svg` - Section dividers

### Backgrounds

- `parchment-texture.png` - Subtle parchment background
- `leather-texture.png` - Dark leather texture for headers

### Icons

- `sword-icon.svg` - Combat section
- `shield-icon.svg` - Defense/armor
- `scroll-icon.svg` - Skills/abilities
- `crown-icon.svg` - Character identity

## Usage in Foundry VTT

```css
/* Apply parchment background to character sheet */
.reign2e.sheet {
  background-image: url('systems/reign2e/assets/parchment-texture.png');
  background-size: cover;
}

/* Add border ornaments to header */
.reign2e.sheet .sheet-header {
  border-image: url('systems/reign2e/assets/border-top.svg') 30 round;
}
```

## Color Palette

```
Parchment:    #f4e9d8
Dark Brown:   #2c1810
Gold:         #d4af37
Blood Red:    #8b0000
Steel Gray:   #5a6169
Dark Green:   #2d5016
```

## License

These assets are provided for use with the Reign 2e Foundry VTT system.

## Credits

- Original Reign 2e by Greg Stolze
- Artwork created for Foundry VTT implementation
- Inspired by medieval heraldry and Game of Thrones aesthetics
