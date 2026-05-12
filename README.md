🌈 **FARRISHUB** 🌈
===================

A stunning neon rainbow hub website featuring links to 9 popular apps with animated backgrounds and interactive effects.

## ✨ Features

- **Neon Rainbow Title**: Eye-catching "FARRISHUB" header with rainbow gradient and glowing effects
- **Animated Starry Background**: Moving stars that twinkle and create a cosmic atmosphere on a black background
- **9 App Cards**: Interactive cards linking to:
  - 🎥 YouTube
  - 🎵 TikTok
  - 🎮 Roblox
  - 💬 Discord
  - 👻 Snapchat
  - 📱 FaceTime
  - 📷 Instagram
  - 🐦 Twitter
  - 🎵 Spotify

- **Interactive Effects**:
  - Hover animations on app cards
  - Parallax effect on the title
  - Glowing shadows and rainbow borders
  - Smooth transitions and transforms
  - Responsive design for all devices

## 📁 File Structure

```
.
├── index.html    # Main HTML structure
├── style.css     # Styling and animations
├── script.js     # JavaScript for interactivity
└── README.md     # This file
```

## 🚀 How to Use

1. Clone or download this repository
2. Open `index.html` in a web browser
3. Hover over the app cards to see interactive effects
4. Move your mouse to see the parallax effect on the title
5. Click any app card to open the respective website

## 🎨 Customization

### Change Colors
Edit the gradient colors in `style.css`:
- Modify `.neon-title` for the title colors
- Update `.app-icon.youtube`, `.app-icon.discord`, etc. for individual app colors

### Add/Remove Apps
Edit `index.html` to add or remove app cards. Each card follows this structure:
```html
<a href="https://app-url.com" target="_blank" class="app-card">
    <div class="app-icon app-name">
        <svg><!-- SVG content --></svg>
    </div>
    <p class="app-name">App Name</p>
</a>
```

### Adjust Animations
- Star speed: Change `twinkle 5s ease-in-out` in `.stars-background::before`
- Glow intensity: Modify `text-shadow` values in `.neon-title`
- Hover effects: Update `transition` and `transform` in `.app-card:hover`

## 🌐 Browser Support

Works best on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📱 Responsive Design

- Desktop (1200px+): 9 cards in 3x3 grid
- Tablet (768px-1199px): Flexible grid layout
- Mobile (below 768px): 3 cards per row

## 🎯 Features Breakdown

### Neon Rainbow Effect
- Rainbow gradient text with drop shadow
- Animated glow that pulses
- Hue rotation animation

### Starry Background
- Fixed position animated stars
- Multiple layers with different animation speeds
- Twinkling effect for depth

### Interactive App Cards
- Hover lift and scale effect
- Glowing box-shadow on hover
- Icon rotation and border highlight
- App name color change to cyan

## 📝 License

Feel free to use and modify this project as needed!

## 🎉 Enjoy!

Your FARRISHUB is now ready to use! Share it with friends and customize it to your liking. 🌟

---

Created with 💜 for FARRISMAIDA10-PIXEL
