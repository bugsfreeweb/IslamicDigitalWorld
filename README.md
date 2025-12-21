# Islamic Digital World

**Your Complete Islamic Companion** - A modern, feature-rich Progressive Web Application (PWA) for Muslims worldwide.

![Islamic Digital World](assts/homescreen-bg.png)

---

## Overview

Islamic Digital World is a comprehensive Islamic web application that provides essential tools and resources for practicing Muslims. Built with modern web technologies, it offers offline support, multi-language translations, and a beautiful user interface.

---

## Features

### Quran Suite
- **Complete Quran** - All 114 Surahs with Arabic text
- **Audio Recitation** - Verse-by-verse audio playback
- **11 Translations** - Arabic, English, Bengali, Urdu, Spanish, French, Indonesian, Russian, Turkish, Chinese, Hindi
- **Tajweed Mode** - Enhanced reading with pronunciation rules
- **Bookmarking** - Save and organize favorite verses
- **Memorization Tracker** - Track your Quran memorization progress
- **Audio Visualizer** - Beautiful audio visualization during playback
- **Night Mode** - Comfortable reading in low light
- **Fullscreen Mode** - Distraction-free reading experience

### Hadith Library
- **6 Major Collections**:
  - Sahih Bukhari
  - Sahih Muslim
  - Sunan Abu Dawud
  - Jami' at-Tirmidhi
  - Sunan an-Nasa'i
  - Ibn Majah
- **Smart Search** - Search by number or keyword
- **Multi-language Translation** - Real-time translation support
- **Memory Caching** - Fast loading with intelligent caching

### Prayer Tools
- **Prayer Times** - Accurate prayer times based on location
- **Next Prayer Indicator** - Countdown to next prayer
- **Prayer Reminders** - Enable notifications for each prayer
- **Prayer Logging** - Track your daily prayers

### Qibla Finder
- **Compass Navigation** - Accurate Qibla direction
- **Distance to Mecca** - Real-time distance calculation
- **Calibration Support** - Compass calibration for accuracy
- **Visual Indicators** - Green zone for correct alignment

### Mosque Finder
- **Interactive Map** - Find nearby mosques using OpenStreetMap
- **Radius Search** - Customizable search radius (1-50 km)
- **Mosque Details** - View address, distance, and directions
- **Get Directions** - One-click navigation

### Islamic Calendar
- **Hijri Calendar** - Complete Islamic calendar
- **Islamic Events** - Important dates and occasions
- **Ramadan Tracker** - Track fasting days
- **Fasting Timer** - Suhoor and Iftar times

### Halal Food Finder
- **Restaurant Search** - Find halal restaurants nearby
- **Cuisine Filters** - Filter by cuisine type
- **Map Integration** - Visual restaurant locations

### Media & Tools
- **Quran Recitation Player** - Professional audio player with controls
- **Background Player** - Listen while using other features
- **Sleep Timer** - Auto-stop playback
- **Notes & Bookmarks** - Personal annotations

### Customization
- **Theme Toggle** - Light and Dark modes
- **34+ Islamic Wallpapers** - Beautiful background options
- **Wallpaper Rotation** - Auto-change on refresh or timed intervals (30/60 min)
- **Custom Wallpaper Upload** - Use your own images
- **Font Size Options** - Adjustable text sizes

---

## Technical Specifications

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (ES6+)** - Vanilla JS, no framework dependencies
- **Leaflet.js** - Interactive maps
- **Phosphor Icons** - Beautiful icon set

### Data Source
All Quran and Hadith data is served from:
- **IslamicData API** - `https://islamicdata.netlify.app`
  - Quran Arabic text
  - 11 language translations
  - Verse-by-verse audio
  - Tajweed data
  - Complete Hadith collections

### Other APIs & Services
- **Aladhan API** - Prayer times calculation
- **OpenStreetMap/Overpass API** - Mosque and location data

### PWA Features
- **Service Worker** - Offline functionality
- **Web App Manifest** - Installable on devices
- **Responsive Design** - Works on all screen sizes
- **Touch Optimized** - Mobile-friendly interactions

---

## Installation

### Option 1: Direct Use
Simply open `index.html` in a modern web browser.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

### Option 3: Deploy to Hosting
Upload all files to any static hosting service:
- Netlify
- Vercel
- GitHub Pages
- Firebase Hosting

---

## Browser Support

| Browser | Minimum Version |
|---------|-----------------|
| Chrome  | 80+ |
| Firefox | 75+ |
| Safari  | 13+ |
| Edge    | 80+ |
| Opera   | 67+ |

---

## Permissions Required

- **Location** - For prayer times, Qibla, and mosque finder
- **Device Orientation** - For Qibla compass
- **Notifications** - For prayer reminders (optional)
- **Storage** - For offline caching and preferences

---

## Configuration

### Theme Colors
The app uses CSS variables for theming:
```css
--primary: #10b981 (Emerald Green)
--primary-dark: #059669
--gold: #f59e0b
```

### API Configuration
Located in `js/app.js`:
```javascript
const CONFIG = {
    API_BASE: 'https://islamicdata.netlify.app/AlQuran',
    HADITH_BASE: 'https://islamicdata.netlify.app/Hadiths/JSON'
};
```

---

## Offline Capabilities

The app caches:
- All HTML, CSS, and JS files
- Font files
- Icon libraries
- Previously loaded Quran data
- Hadith collections (in memory)

---

## License

This project is open source and available under the MIT License.

---

## Credits

- **Quran & Hadith Data**: [IslamicData](https://islamicdata.netlify.app/)
- **Prayer Times**: [Aladhan API](https://aladhan.com/)
- **Maps**: [OpenStreetMap](https://www.openstreetmap.org/) & [Leaflet](https://leafletjs.com/)
- **Icons**: [Phosphor Icons](https://phosphoricons.com/)

---

**Developed with dedication for the Muslim Ummah**

*Bismillah - In the name of Allah, the Most Gracious, the Most Merciful*
