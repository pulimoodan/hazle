# AI Monitor - Landing Page

A modern, animated landing page for an AI-powered communication monitoring tool that aggregates messages from multiple platforms into one place.

## Features

- **Animated Hero Section** - Eye-catching hero with dynamic text animations
- **Rotating Channel Display** - Automatically cycles through supported communication platforms (Slack, Email, Discord, Telegram, Teams, WhatsApp, Intercom)
- **Floating Social Icons** - Animated floating icons representing various communication platforms
- **Hand-drawn Wavy Lines** - Animated background elements with organic, hand-drawn aesthetic
- **Responsive Design** - Mobile-friendly layout with breakpoints for different screen sizes
- **Custom Color Palette** - Easily customizable color system using CSS variables
- **Waitlist Integration** - Integrated with Tally for collecting waitlist signups

## Supported Platforms

The landing page showcases support for:

- LinkedIn
- Slack
- Outlook
- Discord
- Microsoft Teams
- WhatsApp
- Reddit
- GitHub
- Telegram
- Zoom
- Intercom

## Color Palette

The project uses a flexible color system defined in CSS variables:

```css
--color-1: #7b3be9 (Purple)
--color-2: #b7c0ee (Light Purple)
--color-3: #ebf2fa (Very Light Blue)
--color-4: #000505 (Dark Navy)
--color-5: #32e875 (Green)
```

## Setup

1. Clone or download this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required - it's a single HTML file!

## Customization

### Changing Colors

Edit the CSS variables in the `:root` selector:

```css
:root {
  --color-1: #your-color;
  --color-2: #your-color;
  --color-3: #your-color;
  --color-4: #your-color;
  --color-5: #your-color;
}
```

### Adding/Removing Communication Channels

Edit the `channels` array in the JavaScript section:

```javascript
const channels = [
  "Slack",
  "Email",
  "Discord",
  // Add or remove channels here
];
```

### Modifying Floating Icons

Add or remove icons in the `.floating-icons` div and add corresponding CSS positioning in the `.floating-icon:nth-child()` selectors.

### Updating Waitlist Form

Replace the Tally form ID in the button's `data-tally-open` attribute:

```html
<button data-tally-open="YOUR_FORM_ID"></button>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3 (with animations and keyframes)
- Vanilla JavaScript
- SVG for animated graphics
- Tally.so for form integration

## File Structure

```
ai-monitor/
├── index.html    # Single-page application
└── README.md     # This file
```

## License

This project is open source and available for use.
