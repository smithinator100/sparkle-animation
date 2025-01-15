
https://github.com/user-attachments/assets/7e13c70f-ac39-4395-8f76-99750fb8a0a2


# Pictogram Animation

A lightweight, customizable CSS animation system for pictograms with sparkle and dot effects. This project provides smooth, scalable animations for pictogram elements with configurable sparkles and dots positioned around the main image.

## Features

- Scalable pictogram animations
- Configurable sparkle and dot effects
- Smooth pulse and spin animations
- Two preset sparkle patterns
- Customizable animation timing and scaling
- Responsive design

## Usage

### Basic Setup

1. Include the CSS file in your HTML:
```html
<link rel="stylesheet" href="anim.css">
```

2. Structure your HTML:
```html
<div class="pictogram sparkles-1 anim">
    <img src="your-pictogram.png" alt="Pictogram">
    <div class="sparkle"></div>
    <div class="sparkle"></div>
    <div class="sparkle"></div>
    <div class="dot"></div>
    <div class="dot"></div>
    <div class="dot"></div>
</div>
```

### Customization

The animation system uses CSS custom properties for easy customization:

```css
.pictogram {
    --pictogram-scale: 1;          /* Adjust overall size */
    --spin-duration: 6s;           /* Rotation animation duration */
    --pulse-duration: 2.5s;        /* Pulse animation duration */
    --pulse-scale-min: 0;          /* Minimum pulse scale */
    --pulse-scale-max: 1.75;       /* Maximum pulse scale */
    --sparkle-size: 8px;           /* Size of sparkle elements */
    --dot-size: 3px;              /* Size of dot elements */
}
```

### Animation Classes

- `.anim`: Enables the animations
- `.sparkles-1`: First sparkle pattern preset
- `.sparkles-2`: Second sparkle pattern preset

## Technical Details

- Base pictogram dimensions: 128px × 96px
- Sparkle positions are calculated using percentage-based positioning
- Animations use CSS transforms for optimal performance
- Automatic animation delays for sequential effects

## Browser Support

This animation system uses modern CSS features including:
- CSS Custom Properties (CSS Variables)
- CSS Transforms
- CSS Animations
- Flexbox
