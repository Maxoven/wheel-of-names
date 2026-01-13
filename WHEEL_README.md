# 🎡 Wheel of Names

A beautiful, animated spinning wheel to randomly select names! Perfect for giveaways, classroom activities, team selections, and more.

## ✨ Features

- 🎨 **Beautiful retro-game aesthetic** with smooth animations
- 🎯 **Realistic spinning physics** with randomized results
- 💾 **Auto-saves names** using browser localStorage
- 📱 **Fully responsive** - works on desktop, tablet, and mobile
- 🎉 **Confetti celebration** when winner is selected
- 🔊 **Sound effects** (optional, using Web Audio API)
- 🌈 **Colorful segments** with automatic color distribution
- ⚡ **No database needed** - everything runs in the browser!

## 🚀 Quick Start

### Option 1: Just Open the File (Simplest!)

1. Download `wheel-index.html`
2. Double-click to open in your browser
3. Start adding names and spinning!

That's it! No installation, no server needed.

### Option 2: Deploy to the Web (Free!)

Deploy to **Vercel**, **Netlify**, or any static hosting:

#### Deploy to Vercel (Easiest):
1. Go to https://vercel.com
2. Sign up (free)
3. Drag and drop `wheel-index.html`
4. Get your free URL: `yourapp.vercel.app`

#### Deploy to Netlify:
1. Go to https://www.netlify.com
2. Drag and drop `wheel-index.html`
3. Get your free URL: `yourapp.netlify.app`

#### Deploy to Render (Static Site):
1. Create a GitHub repo with `wheel-index.html`
2. Go to https://render.com
3. New → Static Site
4. Connect your repo
5. Deploy!

## 📖 How to Use

### Adding Names
1. Type a name in the input field
2. Click "Add" or press Enter
3. The wheel updates automatically

### Spinning the Wheel
1. Click the big "SPIN THE WHEEL!" button
2. Watch it spin for 4 seconds
3. See the winner with confetti! 🎉

### Managing Names
- **Delete**: Click the ✕ button next to any name
- **Clear All**: Remove all names at once
- **Reset**: Go back to default sample names

## 💾 Data Storage

- Names are saved in your browser's localStorage
- Data persists even after closing the browser
- No accounts or sign-ups needed
- Privacy-friendly - everything stays on your device

## 🎨 Customization

Want to customize the wheel? Here are some easy changes:

### Change Colors
Find this section in the HTML and modify the colors array:
```javascript
const colors = [
    '#FF6B6B', '#4ECDC4', '#45B7D1', // Add your hex colors here
];
```

### Change Fonts
Replace the Google Fonts import at the top:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet">
```

### Adjust Spin Duration
Change the spin duration (in milliseconds):
```javascript
setTimeout(() => {
    // ... winner logic
}, 4000); // Change 4000 to your desired duration
```

## 🌐 Browser Compatibility

Works on all modern browsers:
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

**Note**: Requires JavaScript enabled

## 🎯 Use Cases

Perfect for:
- 🎁 **Giveaways** and contests
- 🏫 **Classroom activities** - picking students
- 👥 **Team selections** - random team assignments
- 🎲 **Decision making** - when you can't decide
- 🎉 **Party games** - who goes first?
- 💼 **Meetings** - random presenter selection

## 🔒 Privacy

- ✅ No data collection
- ✅ No tracking
- ✅ No external API calls
- ✅ Everything runs locally in your browser
- ✅ Names stored only on your device

## 📱 Mobile Experience

The wheel is fully responsive and works great on:
- 📱 Phones (portrait and landscape)
- 📱 Tablets
- 💻 Desktops
- 🖥️ Large screens

## 🎓 Technical Details

Built with:
- **HTML5 Canvas** for wheel rendering
- **Vanilla JavaScript** (no frameworks needed!)
- **CSS3 animations** for smooth effects
- **localStorage API** for data persistence
- **Web Audio API** for sound effects

## 🤝 Contributing

Want to improve the wheel? Some ideas:
- Add more animation effects
- Custom sound effects
- Export/import names feature
- Share results on social media
- Dark/light theme toggle
- Multiple wheel profiles

## 📝 License

Free to use for personal and commercial projects!

## 🆘 Troubleshooting

**Names not saving?**
- Check if your browser allows localStorage
- Try a different browser
- Clear cache and reload

**Wheel not spinning?**
- Make sure you have at least one name
- Check browser console for errors
- Refresh the page

**Animation choppy?**
- Close other browser tabs
- Update your browser
- Try on a different device

## 🎉 Credits

Created with ❤️ for making random selections fun!

Fonts: Righteous and Fredoka from Google Fonts

---

**Enjoy spinning! 🎡✨**
