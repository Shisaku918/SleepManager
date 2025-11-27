# 🌙 SleepManager

A smart sleep management app focused on damage control and sleep debt tracking. Helps you optimize sleep timing based on 90-minute cycles, even when you're already sleep-deprived.

## ✨ Features

### 🎯 Smart Planning Modes
- **Normal Mode**: Calculate ideal bedtime for your wake-up time
- **Damage Control**: Emergency guidance when already late (e.g., it's 3 AM and you wake at 6 AM)
- Accounts for sleep debt when recommending bedtimes

### 📊 Sleep Debt Tracking
- Real-time debt calculation over 14-day periods
- Color-coded alerts (Green → Yellow → Orange → Red)
- Personalized recovery plans (progressive & intensive strategies)
- Chronic fatigue detection with weekly check-ins

### 🛠️ Personalization
- Customizable cycle duration (70-120 minutes, default 90)
- Adjustable fall-asleep time
- Age-based sleep requirements
- 12h/24h time format toggle
- Dark/Light theme

### 💤 Sleep Logging
- Quick morning check-ins with quality ratings (1-5)
- Interactive nap tracking (20-min power naps & 90-min cycle naps)
- Historical visualization with 30-day graphs
- Automatic pattern detection and insights

## 🚀 Tech Stack

- **Framework**: Next.js 16 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Storage**: localStorage with PWA support
- **Deployment**: Vercel

## 🏃 Getting Started
```bash
# Clone the repository
git clone https://github.com/Shisaku918/SleepManager.git

# Install dependencies
cd SleepManager
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📱 PWA Installation

### iPhone (Safari):
1. Open the app in Safari
2. Tap the Share button
3. Select "Add to Home Screen"

### Android (Chrome):
1. Open the app in Chrome
2. Tap the menu (3 dots)
3. Select "Add to Home screen"

## 🎨 What Makes This Unique

Unlike other sleep apps that just track or analyze:
- **Proactive debt management**: Shows how to recover accumulated sleep debt
- **Damage control mode**: Practical guidance when already sleep-deprived
- **Non-judgmental approach**: Focuses on solutions, not guilt
- **Cycle-based optimization**: Ensures you wake between cycles, not during them

## 📝 Usage Flow

1. **Setup**: Enter age, fall-asleep time, and cycle duration
2. **Plan**: Each evening, input tomorrow's wake time → get ideal bedtime
3. **Log**: Each morning, record actual sleep and quality rating
4. **Track**: Monitor debt accumulation and follow recovery plans
5. **Check-in**: Weekly questionnaire for chronic fatigue detection

## 🛠️ Development
```bash
# Run linter
npm run lint

# Build for production
npm run build

# Start production server
npm start
```

## 📄 License

MIT

## 👤 Author

**Shisaku918**
- GitHub: [@Shigeru3e7](https://github.com/Shhigeru3e7)

---

Built with focus on practical sleep management, not judgment. Sleep debt happens—let's manage it smartly. 💤

