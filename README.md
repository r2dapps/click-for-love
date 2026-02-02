# 💘 Valentine Alert! 💘

![Made with 💖](https://img.shields.io/badge/Made%20with-%F0%9F%92%96-pink)
![Demo Online](https://img.shields.io/badge/Demo-Online-brightgreen)
![Love Level](https://img.shields.io/badge/Love%20Level-Infinite-ff69b4)

**Steal hearts, spread love, and maybe catch the impossible "No 🙄" button!**  

Try clicking **No 🙄**… if you can! Click **Yes 💖** to unlock hearts, confetti, and a sweet Valentine message at the end.  

---

## 🚀 Live Demo
[🌐 Open in Browser](https://r2dapps.github.io/click-for-love/?name=Alex)

---

## ✨ Features

- 💫 **Neon Edge Glow** – pulsing glowing border with moving light effects
- 💖 **Floating Heart Icons** – animated hearts drift across the screen  
- ❤️ **Smart "No" Button** – moves away and changes text when clicked
- 💌 **Interactive Questions** – 17+ question sets with psychological prompts
- 🎭 **Card Animations** – shake, pulse, bounce, spin, wiggle, flip  
- 🎊 **Confetti Finale** – heart-shaped confetti celebrates your love  
- 🌈 **Dynamic Backgrounds** – 35+ beautiful gradient themes  
- 🖋 **Custom Name** – add `?name=YourName` in the URL  
- 📱 **Responsive Design** – works beautifully on mobile & desktop  
- 🎯 **Click Tracking** – dynamic messages based on No button clicks
- 🔒 **Input Sanitization** – safe name handling with character filtering

---

## 🛠 Built With

- **HTML5 & CSS3** – Modern web standards with advanced animations
- **Vanilla JavaScript** – No frameworks, pure performance  
- **[Canvas Confetti](https://www.npmjs.com/package/canvas-confetti)** – Heart-shaped confetti magic
- **CSS Keyframes** – Smooth animations & visual effects
- **Responsive Design** – Mobile-first approach with clamp() sizing

---

## 🎨 Customization

### Quick Edits
- **Messages**: Edit `questionSets`, `notes`, `noTexts`, and `finaleSets` arrays
- **Colors**: Update the `backgrounds` array with your gradients
- **Animations**: Modify CSS keyframes for different effects
- **Timing**: Adjust intervals for hearts and background changes

### Advanced Features
```javascript
// Custom question sets
questionSets.push([
  "Your custom question?",
  "Follow up question", 
  "Final question"
]);

// Dynamic No button responses
const noTexts = ["Yes 😇", "Maybe 🤔", "Free Candy 🍬"];
```

---

## 🎯 How It Works

1. **User visits** → Random background & question set loads
2. **Clicks No** → Button moves, changes text, shows click counter messages
3. **Hovers No** → Button text changes to troll messages
4. **Clicks Yes** → Card animates, hearts burst, new question appears
5. **Reaches finale** → Confetti explosion & personalized message
6. **Background effects** → Continuous neon glow and floating hearts

---

## 🎮 Interactive Elements

- **No Button Panic Animation** – scales and rotates when clicked
- **Dynamic Click Messages** – 20+ responses based on click count
- **Hover Trolling** – button text changes on mouse hover
- **Heart Bursts** – triggered by both Yes and No clicks
- **Background Transitions** – smooth gradient changes between questions

---

## 📄 License

Free to use, share, and spread love ❤️  
No attribution required, but appreciated!

---

**💡 Pro Tip:** Share it with friends and watch them chase the No button! 😈💖

**🎭 Easter Egg:** Try different names in the URL for personalized messages!
