# Productivity & Mindfulness Apps 🚀

A collection of three powerful, browser-based apps designed to help you make better decisions, face your fears, and live intentionally. No installation required—all apps run directly in your browser.

## 🎯 Apps Included

### 1. **Life in Weeks** 📅
Visualize your entire life compressed into weeks. Enter your birth date to instantly see:
- Total weeks you've lived
- Total weeks remaining (based on life expectancy slider)
- Visual grid of your life phases with color-coded banners
- Average life expectancy context

**Use it to:** Gain perspective on time scarcity and inspire intentional decision-making inspired by the Stoic practice of memento mori.

### 2. **Memento Mori: One Year Visualization** 💀
Focus on a single year through 52 weeks. Mark weeks as you live them and reflect on what matters most. Includes:
- 52-week grid visualization
- Interactive week marking system
- Stoic meditation context and philosophy
- Reflective practice prompts
- Data persistence with browser localStorage

**Use it to:** Daily meditation on mortality, gratitude for time, and clarity on priorities. Based on Stoic philosophy.

### 3. **Fear Setting Workshop** 😰
The Tim Ferriss fear-setting exercise structured in three phases:
- **Define & Prevent**: Articulate worst-case scenarios and prevention strategies
- **Repair & Cost**: Plan recovery actions and calculate the cost of inaction
- **Benefits of Success**: Identify gains from taking action

**Use it to:** Transform paralyzing anxiety into actionable plans. Define what you actually fear, realize scenarios are survivable, and convert vague worries into concrete strategies.

---

## 🚀 Quick Deployment

### Deploy to Netlify (Recommended)
1. Push this folder to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click **"New site from Git"**
4. Select your repository
5. Netlify auto-deploys (no build step needed)

### Deploy to Vercel
1. Push this folder to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click **"New Project"** and select your repo
4. Vercel auto-detects static site
5. Click **"Deploy"**

### Local Development
```bash
# Python 3.x (built-in)
python -m http.server 8000

# Or Node.js
npx http-server
```
Then open http://localhost:8000

---

## ✨ Features

- **Zero Dependencies**: Pure HTML/CSS/JavaScript—no frameworks or build tools
- **5 Color Themes**: Switch between Rose, Midnight, Sage, Ocean, and Steel color schemes
- **Data Persistence**: Browser localStorage saves your preferences and data automatically
- **Fully Responsive**: Works on desktop, tablet, and mobile
- **No Backend Required**: All processing happens in your browser
- **Export/Download**: Save your fear-setting work as JSON for backup
- **Cross-App Navigation**: Easy switching between all three apps

---

## 📁 Files

```
.
├── index.html              # Life in Weeks app
├── fear+death.html         # Memento Mori app
├── fearsetting.html        # Fear Setting Workshop
├── netlify.toml            # Netlify configuration
├── vercel.json             # Vercel configuration
├── package.json            # Project metadata
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

---

## 🎨 Customization

### Change Color Themes
Edit the CSS custom properties in the `<style>` section of each HTML file:
```css
:root {
  --primary: #your-color;
  --accent: #your-color;
  --background: #your-color;
  /* etc... */
}
```

### Modify Content
Each app's text content is clearly labeled in HTML. Edit the headings, paragraphs, and prompts directly in the HTML files.

### Adjust Life Expectancy Ranges
In `index.html`, find the life expectancy slider and change the `min` and `max` attributes.

---

## 📖 Philosophy

These apps are inspired by:
- **Memento Mori**: Ancient Stoic and Roman practice of meditating on mortality to clarify priorities
- **Tim Ferriss's Fear Setting**: Methodology from "Tribe of Mentors" and "The 4-Hour Workweek"
- **Time Awareness**: Visual representation of finite time to inspire intentional living

---

## 🔒 Privacy

- **No Tracking**: No analytics or tracking code
- **No Backend**: All data stays in your browser
- **No Accounts Needed**: Everything works offline (after initial load)
- **Data is Yours**: Use browser DevTools to export localStorage data

---

## 🛠️ Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Requires ES6 JavaScript support.

---

## 📝 License

Free to use, modify, and deploy. No restrictions.

---

**Use these tools to build clarity, face your fears, and live with intention.** ✨
