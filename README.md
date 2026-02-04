# 🎲 AA Farkle Scorer

A mobile-friendly Farkle score keeper app with automatic turn tracking, running totals, and proper tournament-style ending rules.

## 🚀 Quick Start

1. Visit: **https://alanagee.github.io/Farkle-Score-AA/**
2. Add players (minimum 2)
3. Click "Start Game"
4. Start scoring!

### 📱 Add to Home Screen (iPhone)

1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. Launch from your home screen like any app!

## 🎮 How to Play

### Game Setup

- Add at least 2 players to start the game
- Each player takes turns rolling dice and scoring points
- First to 10,000+ points triggers the final round

### Scoring Your Turn

**As you roll and score:**
- Enter each scoring combination as you go: `50 100 150`
- The running total shows your turn score in real-time
- Separate scores with spaces or commas
- Press Enter or click "Add" when your turn is complete
- Cursor automatically jumps to the next player

**Example:**
```
First roll: 50 points → Type: 50
Second roll: 100 points → Type: 50 100
Third roll: 150 points → Type: 50 100 150
Running total shows: 300
Press Enter → Score saved as Round 1: 300
```

### 🎯 Farkle Rules

**If you Farkle (can't score on a roll):**
- Add `0` anywhere in your entries: `50 100 0`
- Display will show "FARKLE!" in red
- You lose ALL points from that turn
- Examples:
  - Just a Farkle: `0`
  - Farkle after scoring: `50 250 300 0` (lose all 600 points)

### 📊 Getting on the Board

- Your **first scoring turn** must total at least **500 points**
- You can Farkle as many times as you want before reaching 500
- Once you score 500+, any amount is valid on future turns

### 🏆 Winning the Game

**Final Round Rules:**

1. **First player to reach 10,000+** triggers the final round
2. **Orange warning banner** appears with notification
3. **All other players** get ONE more turn to try to beat that score
4. **Highest score wins** - not just first to 10,000!

**Example:**
- Alice reaches 10,500 → Final round triggered
- Bob scores 3,000 → Total: 11,000
- Carol Farkles → Total: 7,500
- **Bob wins with 11,000!**

## ✨ Features

- ✅ **Running Total Display** - See your turn total as you type
- ✅ **Auto-Focus Next Player** - Cursor jumps automatically after scoring
- ✅ **Farkle Detection** - Instant visual feedback when you add a 0
- ✅ **Round Tracking** - Each turn labeled (R1, R2, R3...)
- ✅ **Score History** - See all past scores and Farkles
- ✅ **Undo Function** - Fix mistakes easily
- ✅ **Final Round Logic** - Proper tournament-style ending
- ✅ **Leader Indicator** - Gold ring around current leader
- ✅ **Winner Celebration** - Trophy and celebration when game ends
- ✅ **Mobile Optimized** - Works perfectly on iPhone
- ✅ **Offline Capable** - Add to home screen for offline play

## 🎨 Visual Indicators

| Indicator | Meaning |
|-----------|---------|
| 🟣 Purple chips | Regular scores |
| 🔴 Red chips | Farkles |
| 🟡 Gold ring | Current leader |
| 🟢 Green "✓ Done" | Finished final turn |
| 🟠 Orange banner | Final round active |
| 🏆 Trophy icon | Winner! |

## 📝 Quick Tips

1. **Fast Entry**: Type all scores from your turn, then press Enter
2. **Undo Mistakes**: Use the Undo button to remove the last score
3. **Mobile Keyboard**: App works great with iPhone number keyboard
4. **No Clicking**: Just type and press Enter to keep the game flowing
5. **Visual Feedback**: Watch the running total to verify your math
6. **Farkle Warning**: See "FARKLE!" in red before you commit

## 🎲 Farkle Scoring Reference

Common Farkle scoring combinations:
- Single 1 = 100 points
- Single 5 = 50 points
- Three 1s = 300 points
- Three of any other number = Number × 100
- Four of a kind = 1,000 points
- Five of a kind = 2,000 points
- Six of a kind = 3,000 points
- Straight (1-2-3-4-5-6) = 1,500 points
- Three pairs = 1,500 points
- Four of a kind + One Pair = 1500 points
- 2 Triplets = 2500 points

*Note: This app tracks totals - you calculate combinations yourself!*

## 🛠️ Technical Details

- **100% Standalone** - Single HTML file, no dependencies
- **No Installation** - Works in any modern browser
- **No Server** - All data stored locally in your browser
- **Privacy** - No data collection, no analytics, no tracking
- **Open Source** - Feel free to modify and improve!

## 📄 License

Free to use and modify. Created for Farkle enthusiasts! 🎲

---

**Made with ❤️ for game night!**

Have fun and roll big! 🎲🏆
