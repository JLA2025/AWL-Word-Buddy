# Word Buddy - Academic Word List for Beginners

A friendly, encouraging web app designed specifically for lower-level learners to build their academic vocabulary. Features simple words, positive reinforcement, and engaging game modes.

## ✨ Features

- 🎴 **Flashcards**: Learn words at your own pace with beautiful flip cards
- 🎯 **Pick the Right One**: Choose the correct meaning from multiple choices
- 🧩 **Match the Pairs**: Connect words with their definitions (easier than spelling!)
- 🌟 **Encouraging Design**: Positive feedback and motivational messages
- 📊 **Track Progress**: See your learning grow with saved statistics
- 💙 **Beginner-Friendly**: Simpler words and clearer explanations
- 📱 **Mobile-Ready**: Works perfectly on all devices

## 🎯 Why This Version?

This is specifically designed for **lower-level learners** who may find spelling challenges too difficult. Instead of typing words, students:
- Learn through recognition (flashcards and MCQ)
- Match words visually (matching game)
- Build confidence with positive, encouraging feedback
- Work with simpler AWL words and clearer definitions

## 🎮 Game Modes Explained

### Flashcards 🎴
- Click to flip cards and see definitions
- No pressure, learn at your own speed
- Perfect for first-time vocabulary building

### Pick the Right One 🎯
- See a word and choose its meaning
- 4 options to select from
- Get instant, encouraging feedback

### Match the Pairs 🧩
**This is the key difference for beginners!**
- See all words AND definitions at once
- Click a word, then click its meaning
- Easier than spelling because you can:
  - Compare options side-by-side
  - Eliminate matches as you go
  - Use recognition instead of recall

## 🚀 Quick Start

### Option 1: Local Use
Simply open `word-buddy.html` in any modern web browser!

### Option 2: GitHub Pages Hosting

1. **Create a new GitHub repository**
   ```bash
   git init
   git add word-buddy.html README.md
   git commit -m "Add Word Buddy learning app"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/word-buddy.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Select "main" branch as source
   - Save
   - Access at: `https://YOUR-USERNAME.github.io/word-buddy/word-buddy.html`

3. **Optional: Cleaner URL**
   - Rename to `index.html`
   - URL becomes: `https://YOUR-USERNAME.github.io/word-buddy/`

## 📖 Word List

Includes 40 carefully selected AWL words with simple, clear definitions suitable for beginner learners:
- Everyday academic vocabulary
- Clear, straightforward definitions
- Words students will encounter frequently

## 🎨 Design Philosophy

**Soft & Encouraging:**
- Friendly cyan/blue colour scheme (vs the advanced version's bold orange)
- Rounded, approachable design
- Positive reinforcement at every step
- "You're doing great!" messaging
- Success celebrated at all levels

## 🛠️ Customisation

### Add More Words
Edit the `wordList` array:
```javascript
const wordList = [
    { word: "area", definition: "A space or place" },
    { word: "your-word", definition: "Simple definition" },
    // Add more here
];
```

### Adjust Colours
Change CSS variables:
```css
:root {
    --primary: #06b6d4;    /* Cyan */
    --secondary: #0ea5e9;   /* Sky blue */
    --accent: #8b5cf6;      /* Purple */
}
```

### Change Quiz Length
Modify in the `startMode` function:
```javascript
quizWords = shuffled.slice(0, 8); // Change number here
```

## 👥 Who Is This For?

Perfect for:
- ESL/EFL learners at beginner/intermediate level
- Students building academic vocabulary
- Learners who find spelling challenges frustrating
- Anyone who prefers recognition over recall tasks
- Touch-device users (matching game is click-based, not drag-and-drop)

## 💡 Teaching Tips

1. **Start with Flashcards** - Let students familiarise themselves with words
2. **Move to Multiple Choice** - Test recognition in a low-pressure way
3. **Try Matching** - This is perfect for reinforcement and building confidence
4. **Celebrate Progress** - The app tracks learning - point this out to students!
5. **Repeat Often** - Short, frequent practice sessions work best

## 🔄 Differences from Advanced Version

| Feature | Word Buddy (Beginner) | AWL Quest (Advanced) |
|---------|----------------------|----------------------|
| Design | Soft, encouraging (cyan/blue) | Bold, energetic (orange/red) |
| Fonts | Outfit + DM Sans | Bricolage Grotesque + Crimson Pro |
| Word Difficulty | Simpler AWL words | More challenging AWL words |
| 3rd Game Mode | Matching (recognition) | Spelling (recall) |
| Tone | "You're doing great!" | "Challenge yourself!" |
| Target Level | Beginner/Intermediate | Intermediate/Advanced |

## 📱 Technical Details

- Pure HTML/CSS/JavaScript
- No frameworks required
- Responsive design
- LocalStorage for progress tracking
- Works offline after first load
- Touch-friendly interactions

## 🤝 Contributing Ideas

- Add audio pronunciation
- Include example sentences
- Create achievement badges
- Add difficulty levels
- Implement timed challenges (optional)

## 📧 Support

Open an issue on GitHub if you need help!

---

**Keep learning! You're amazing! 🌟**
