# Reign 2e Character Sheet Artwork

**Game of Thrones inspired medieval theme** for Reign 2e Foundry VTT system.

![Theme Preview](https://img.shields.io/badge/Style-Medieval_Fantasy-8b0000?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-2d5016?style=for-the-badge)

## 🏰 Theme Overview

This artwork collection transforms the Reign 2e character sheet into an elegant medieval fantasy experience inspired by Game of Thrones aesthetics while maintaining excellent readability and functionality.

### Design Philosophy

- **Medieval Elegance**: Dark leather headers, parchment backgrounds, gold accents
- **Readability First**: Clean typography, high contrast, organized layout
- **Functional Beauty**: Art enhances usability, never distracts
- **Simplified Complexity**: Rich visual language without overwhelming detail

## 🎨 Visual Elements

### Color Palette

```css
Parchment:      #f4e9d8  /* Main background */
Dark Brown:     #2c1810  /* Borders and text */
Gold:           #d4af37  /* Accents and highlights */
Blood Red:      #8b0000  /* Primary accent */
Steel Gray:     #5a6169  /* Secondary elements */
Dark Green:     #2d5016  /* Success states */
Leather:        #3d2817  /* Header background */
```

### Typography

- **Headers**: [Cinzel](https://fonts.google.com/specimen/Cinzel) - Elegant serif with medieval feel
- **Body Text**: [Crimson Text](https://fonts.google.com/specimen/Crimson+Text) - Readable serif
- **Loaded via Google Fonts** (no local files needed)

## 📁 Assets

### Body Silhouette (`body-silhouette.svg`)

Human figure for hit location reference with labeled zones:

- **10**: Head
- **7-9**: Torso  
- **5-6**: Right Arm
- **3-4**: Left Arm
- **2**: Right Leg
- **1**: Left Leg

**Usage**: Appears as watermark behind hit locations in Combat tab.

### Decorative Elements

- `border-ornament.svg` - Celtic knots and crown motifs for headers
- `divider-sword.svg` - Elegant section dividers
- `icon-damage.svg` - Blood drop icon for damage tracking

### Theme Stylesheet

`theme.css` - Complete standalone theme (can be used independently)

## ⚙️ Integration

This theme is **already integrated** into the [Reign 2e system](https://github.com/roleplayers/reign2e). No manual installation required!

### What's Applied

✅ Parchment texture background  
✅ Leather header with gold borders  
✅ Medieval scroll-style tabs  
✅ Illuminated manuscript stats  
✅ Body silhouette in hit locations  
✅ Steel button styling  
✅ Custom scrollbars  
✅ Gold highlight effects  

## 🖼️ Features

### Character Sheet Header

- Dark leather gradient background
- Gold border accent lines
- Cinzel font for character name
- Profile image with ornate gold frame
- XP tracker with medieval styling

### Stats & Skills

- Illuminated manuscript style stat groups
- Gold decorative lines
- Blood red stat names in Cinzel font
- Large, readable stat values
- Skills with hover effects (gold highlight)
- Custom skills highlighted in green
- Expert/Master dice badges (purple/orange)

### Hit Locations

- Body silhouette watermark (8% opacity)
- Medieval card layout for each location
- Damage boxes:
  - **Empty**: Parchment background
  - **Shock**: Gold gradient
  - **Killing**: Blood red gradient
- Hover effects with red glow
- AR/HAR armor inputs

### Interactive Elements

- Clickable stat names roll dice
- Clickable skill names roll dice
- Damage boxes cycle: empty → shock → killing → empty
- Selected dice glow with gold shadow

## 🎯 Design Inspirations

### Lord of the Rings RPG

- Clean, uncluttered layout
- Parchment aesthetic
- Readable fonts
- Functional organization

### Original Reign Character Sheet

- Body silhouette for hit locations
- Grid-based skill layout
- Clear damage tracking

### Game of Thrones

- Dark, dramatic color scheme
- Medieval heraldry elements
- Blood red accents
- Steel and leather textures

## 🔧 Customization

To modify the theme, edit `reign2e/css/reign2e.css`:

### Change Primary Color

```css
:root {
  --reign-accent: #8b0000; /* Change to your preferred color */
}
```

### Adjust Background

```css
.reign2e.sheet .window-content {
  background-color: #f4e9d8; /* Lighter or darker parchment */
}
```

### Modify Fonts

```css
@import url('https://fonts.googleapis.com/css2?family=YourFont&display=swap');

.stat-name {
  font-family: 'YourFont', serif;
}
```

## 📋 Technical Details

- **SVG Format**: Scalable, crisp at any resolution
- **CSS Variables**: Easy theme customization
- **Google Fonts**: No local font files needed
- **Semantic Classes**: Maintainable, logical structure
- **Z-index Layers**: Proper stacking context
- **Responsive**: Adapts to different sheet sizes

## 🚀 Future Enhancements

- [ ] Animated hit location highlights
- [ ] Seasonal theme variants (winter, summer)
- [ ] House sigil placeholders
- [ ] Ornamental stat borders
- [ ] Illuminated capital letters for sections
- [ ] Wax seal graphics for tabs

## 📜 Credits

- **System**: Reign 2nd Edition by Greg Stolze
- **Artwork**: Custom SVG assets for Foundry VTT
- **Fonts**: [Cinzel](https://fonts.google.com/specimen/Cinzel) by Natanael Gama, [Crimson Text](https://fonts.google.com/specimen/Crimson+Text) by Sebastian Kosch
- **Inspiration**: Lord of the Rings RPG (Free League), Game of Thrones, Original Reign character sheet

## 📄 License

These assets are provided for use with the Reign 2e Foundry VTT system.

- SVG assets: Free to use and modify
- Theme CSS: Free to use and modify
- Please credit if reusing in other projects

## 🔗 Links

- [Reign 2e System Repository](https://github.com/roleplayers/reign2e)
- [Foundry VTT](https://foundryvtt.com/)
- [Original Reign RPG](http://www.gregstolze.com/reign/)

---

*Made with ⚔️ for Reign 2e players*
