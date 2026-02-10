# 💖 Amar Valentine Hoba? - Interactive Valentine's Day Proposal

A playful and interactive Valentine's Day proposal web app with a twist - the "No" button runs away! Built with pure HTML, CSS, and JavaScript with beautiful animations and sound effects.

## ✨ Features

- 🎨 **Beautiful UI**: Pixel-art inspired design with gradient backgrounds and floating hearts
- 🏃 **Playful Interactions**: The "No" button moves around inside the box to avoid being clicked
- 😊 **Emotional Journey**: Boy emoji changes expressions based on user interactions (10 different emotions)
- 💬 **Bengali Messages**: Cute messages in Bengali that change with each "No" attempt
- 🔊 **Sound Effects**: 8-bit style sound effects for button clicks and envelope opening
- 📳 **Haptic Feedback**: Vibration support for mobile devices
- 💌 **Love Letter**: Beautiful handwritten-style letter reveals when "Yes" is clicked
- 🎊 **Confetti Animation**: Celebrates when the proposal is accepted
- 📱 **Fully Responsive**: Works perfectly on all devices - mobile, tablet, and desktop

## 🎭 How It Works

1. **Initial Screen**: Displays the question "Hey Priyo Bondhu, will you be my Valentine? ❤️"
2. **Clicking "No"**:
   - Attempt 1: Shows a message "Eki re? 🤨"
   - Attempt 2+: Button starts moving randomly inside the box
   - Attempt 3+: "No" button shrinks while "Yes" button grows
   - Each click shows a different Bengali message and changes the boy's emotion
3. **Clicking "Yes"**:
   - Confetti celebration
   - Shows envelope screen with animated envelope
   - Opening the envelope reveals a beautiful love letter

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - Flexbox & Grid
  - CSS Animations & Transitions
  - Backdrop filters for glassmorphism effect
  - Custom scrollbars
- **JavaScript (Vanilla)**:
  - Web Audio API for sound generation
  - DOM manipulation
  - Event handling
  - Vibration API
- **Google Fonts**: Press Start 2P (pixel font) & Caveat (handwritten font)

## 🚀 Live Demo

Visit the live app: [Amar Valentine Hoba?](https://sayan-sengupta.github.io/Valentines-app/)

## 💻 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/sayan-sengupta/Valentines-app.git
   cd Valentines-app
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js (with http-server)
     npx http-server
     ```

3. **Access the app**
   - Open `http://localhost:8000` in your browser

## 📁 Project Structure

```
Valentines-app/
│
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # Project documentation
└── favicon.ico         # Website icon (to be added)
```

## 🎨 Customization

You can easily customize the app:

1. **Change Messages**: Edit the `messages` array in JavaScript
2. **Change Colors**: Modify CSS gradient colors in `body` background
3. **Change Emojis**: Update the `boyEmotions` array
4. **Modify Letter Content**: Edit the text inside `letter-content` div
5. **Adjust Button Behavior**: Modify the `noBtn` click handler logic

## 📱 Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

**Note**: Audio features require user interaction to work (browser policy).

## 🎯 Features Breakdown

### Animations
- Floating hearts background
- Corner decorations with sparkle rotation
- Border hearts pulsing effect
- Envelope bounce animation
- Letter slide-in animation
- Confetti falling animation

### Sound Effects
- Error sound when clicking "No"
- Success melody when clicking "Yes"
- Paper rustling sound when opening envelope

### Responsive Design
- Mobile-first approach
- Adapts to different screen sizes
- Touch-friendly buttons
- Prevents accidental text selection

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 💝 Author

**Sayan Sengupta**

- GitHub: [@sayan-sengupta](https://github.com/sayan-sengupta)

## 📝 License

This project is open source and available for personal use. Feel free to use it for your own Valentine's proposal! ❤️

## 🎁 Acknowledgments

- Inspired by the classic "Will you be my Valentine?" meme format
- Built with love for that special someone 💕
- Thanks to Google Fonts for the beautiful typography

---

### 💌 Made with ❤️ for Valentine's Day

**Pro Tip**: Customize the letter content with your own message to make it extra special! 

---

*If this helped you win someone's heart, give it a ⭐ on GitHub!*