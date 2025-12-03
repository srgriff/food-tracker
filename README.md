# food-tracker
This is my 2025 Capstone project to track protein and fiber food tracker using the USDA API


# Food Tracker - Protein & Fiber Nutrition Tracker

Track your daily protein and fiber intake using real food data from the USDA FoodData Central API.

## 🎯 Features

- **Food Search**: Search 300,000+ foods from USDA database
- **Daily Tracking**: Add foods and track protein/fiber intake
- **Data Visualization**: View weekly trends with Chart.js
- **Goal Progress**: See real-time progress toward daily goals
- **Data Persistence**: All data saved to localStorage
- **Responsive Design**: Works on mobile, tablet, and desktop

## 🚀 Setup Instructions

### 1. Get USDA API Key
1. Visit https://fdc.nal.usda.gov/api-key-signup.html
2. Sign up (free, no credit card)
3. Copy your API key from email

### 2. Install API Key
Open `app.js` and add your key on line 5:
```javascript
const USDA_API_KEY = 'your-api-key-here';
```

### 3. Run the Project
**Option A: VS Code Live Server**
- Install Live Server extension
- Right-click `index.html` → "Open with Live Server"

**Option B: Python**
```bash
python -m http.server 8000
# Open: http://localhost:8000
```

## 📊 Technologies Used

- HTML5, CSS3, JavaScript (ES6+)
- USDA FoodData Central API
- Chart.js for data visualization
- localStorage for data persistence
- CSS Grid & Flexbox for responsive layout

## 🎓 Capstone Requirements Met

- ✅ Responsive design with media queries (768px, 1024px breakpoints)
- ✅ API integration (USDA FoodData Central)
- ✅ 2+ pages (Food Search + Dashboard)
- ✅ Feature 1: Analyze data in arrays/objects
- ✅ Feature 2: Visualize data with Chart.js (3 chart types)
- ✅ Feature 3: Persist data to localStorage
- ✅ Backup: Calculate tracking streaks using Date object

## 📁 File Structure
```
food-tracker/
├── index.html       # Food search page
├── dashboard.html   # Analytics dashboard
├── style.css        # All styles
├── app.js          # Main app logic
├── charts.js       # Chart.js integration
└── README.md       # Documentation
```

## 🧪 Testing

1. Search for "chicken" - should see results
2. Add food - appears in "Today's Entries"
3. Check progress bars update
4. Refresh page - data persists
5. View dashboard - see charts

## 👤 Author

Your Name - Code Louisville 2025 Capstone Project