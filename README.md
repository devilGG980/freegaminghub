# Free Gaming Hub Website

A modern, responsive gaming website template for hosting and distributing free games. This template includes features for game downloads, advertisements, and SEO optimization.

## Features

- 🎮 Modern and responsive design
- 📱 Mobile-friendly interface
- 🎨 Colorful and engaging theme
- 💰 Google AdSense integration
- 🔍 SEO optimized
- 🚀 Fast loading times
- 📥 Game download functionality
- 🖼️ Game screenshots gallery
- ⭐ Rating system
- 🔖 Game categories
- 🔍 Search functionality
- 📱 Mobile menu
- 💾 System requirements display
- 🎯 Similar games recommendations

## Setup Instructions

1. Clone or download this repository
2. Replace the placeholder images in the `images` folder with your game images
3. Update the Google AdSense ID in all HTML files:
   - Replace `YOUR-ADSENSE-ID` with your actual AdSense client ID
   - Replace `YOUR-AD-SLOT-ID` with your actual ad slot IDs

## File Structure

```
gaming-website/
├── index.html              # Main homepage
├── game-template.html      # Template for individual game pages
├── css/
│   └── style.css           # Main stylesheet
├── js/
│   └── main.js             # Main JavaScript file
└── images/                 # Directory for all images
    ├── games/              # Game cover images
    └── screenshots/        # Game screenshots
```

## Customization

### Colors
The website uses CSS variables for easy color customization. Edit the `:root` section in `style.css` to change the color scheme:

```css
:root {
    --primary-color: #6c5ce7;
    --secondary-color: #a29bfe;
    --accent-color: #fd79a8;
    --background-color: #f5f6fa;
    --text-color: #2d3436;
    --card-bg: #ffffff;
}
```

### Adding New Games
1. Copy the `game-template.html` file
2. Rename it to match your game (e.g., `game-name.html`)
3. Update the following sections:
   - Game title and description
   - Game images and screenshots
   - System requirements
   - Features list
   - Meta tags for SEO

## SEO Optimization

The template includes:
- Meta descriptions
- Meta keywords
- Semantic HTML structure
- Alt tags for images
- Proper heading hierarchy
- Mobile-friendly design

## Ad Integration

The website includes designated spaces for advertisements:
1. Header ad space
2. Between featured games
3. In-game pages
4. Footer ad space

To add your ads:
1. Replace the AdSense script with your own
2. Update the ad container divs with your ad code
3. Customize ad sizes and formats as needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This template is free to use for personal and commercial projects.

## Support

For support or questions, please contact: contact@freegaminghub.com 