# Islamic Digital World

**Your Complete Islamic Companion** - A modern, feature-rich Progressive Web Application (PWA) for Muslims worldwide.

![Islamic Digital World](assets/homescreen-bg.png)

![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-10b981)
![Version](https://img.shields.io/badge/Version-2.4.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Languages](https://img.shields.io/badge/Languages-9+-orange)

---

## Table of Contents

| | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|
| [Overview](#overview) | [Live Demo](#live-demo) | [Features](#features) | [Screenshots](#screenshots) | [Tech Stack](#technology-stack) | [Structure](#project-structure) |
| [Installation](#installation) | [Configuration](#configuration) | [API Reference](#api-references) | [Usage Guide](#usage-guide) | [Localization](#localization) | [Browser Support](#browser-support) |
| [Offline](#offline-capabilities) | [Admin Panel](#admin-panel) | [Firebase Setup](#firebase-setup) | [Updates](#recent-updates) | [Contributing](#contributing) | [License](#license) |

---

## Overview

**Islamic Digital World** is a comprehensive Islamic web application that provides essential tools and resources for practicing Muslims. Built with modern web technologies, it offers offline support, multi-language translations, and a beautiful user interface optimized for both desktop and mobile devices.

### Key Highlights

- **Complete Quran** with 9 language translations and audio recitation
- **Authentic Hadith** from 6 major collections
- **Dua Collection** from Hisn Al-Muslim (Fortress of the Muslim)
- **Accurate Prayer Times** based on your location
- **Qibla Direction** with compass functionality
- **Interactive Islamic Quiz** with gamification for adults and children
- **Progress Tracking** with streaks, badges, and achievements
- **Push Notifications** for real-time updates to online users
- **Admin Panel** for content management and analytics
- **Offline Support** for uninterrupted access
- **PWA Ready** - Install on any device

---

## Live Demo

| Version | URL |
|---------|-----|
| **Web Version** | [Launch Web App](https://islamicworld.netlify.app) |


---

## Features

### Al-Quran Suite

| Feature | Description |
|---------|-------------|
| **Complete Quran** | All 114 Surahs with Arabic text and verse numbering |
| **Audio Recitation** | Verse-by-verse audio playback with professional reciters |
| **9+ Translations** | English, Bangla, Hindi, Urdu, Indonesian, Spanish, French, Russian, Chinese |
| **Professional Audio Player** | Play/pause, progress bar, playback speed control (0.5x - 2x) |
| **Bookmarking** | Save favorite verses for quick access |
| **Night Mode** | Comfortable reading in low light |
| **Fullscreen Mode** | Distraction-free reading experience |

### Hadith Library

| Feature | Description |
|---------|-------------|
| **6 Major Collections** | Sahih Bukhari, Sahih Muslim, Sunan Abu Dawud, Jami at-Tirmidhi, Sunan an-Nasai, Ibn Majah |
| **Smart Search** | Search by hadith number or keyword |
| **Real-time Translation** | Translate to 9 languages on-the-fly |
| **Random Hadith** | Discover new hadiths with one click |
| **Bookmarking** | Save and organize favorite hadiths |
| **Memory Caching** | Fast loading with intelligent caching |

### Islamic Quiz Pro

| Feature | Description |
|---------|-------------|
| **Dual Age Modes** | Adult Mode (professional UI) & Kids Mode (fun animations, emojis) |
| **Multiple Game Modes** | Quick (5), Standard (10), Marathon (25), Survival (3 lives), Daily Challenge (2x XP) |
| **10 Categories** | Quran, Hadith, Seerah, Pillars, Prophets, Fiqh, History, and more |
| **Gamification** | XP system, levels, streaks, badges, achievements |
| **Real-time Translation** | Questions and answers translate to selected language |
| **Progress Tracking** | Category completion, accuracy stats, leaderboard |
| **Animations** | Confetti effects, bouncy cards, pulse animations |

### Prayer Tools

| Feature | Description |
|---------|-------------|
| **Accurate Prayer Times** | Location-based calculation with multiple methods |
| **Next Prayer Countdown** | Real-time countdown to next prayer |
| **Prayer Logging** | Track daily prayers with visual indicators |
| **Streak System** | Maintain your prayer consistency |
| **Multiple Calculation Methods** | ISNA, MWL, Egyptian, Karachi, Umm Al-Qura |

### Qibla Finder

| Feature | Description |
|---------|-------------|
| **Compass Navigation** | Accurate Qibla direction using device sensors |
| **Distance to Mecca** | Real-time distance calculation |
| **Visual Indicators** | Clear direction with green alignment zone |
| **Calibration Support** | Instructions for compass calibration |

### Dua Collection

| Feature | Description |
|---------|-------------|
| **Categorized Duas** | Morning, Evening, Daily, Travel, Food, Sleep, etc. |
| **Complete Text** | Arabic, transliteration, and translation |
| **Real-time Translation** | Translate to 9 languages |
| **Random Dua** | Discover new duas |
| **Bookmarking** | Save favorite duas |

### Push Notifications

| Feature | Description |
|---------|-------------|
| **Real-time Notifications** | Instant delivery to online users |
| **Admin Panel Control** | Send notifications from dashboard |
| **Quick Templates** | Pre-built templates for common notifications |
| **Notification History** | View and manage sent notifications |
| **Delete Management** | Delete single, selected, or all notifications |

### Additional Features

| Feature | Description |
|---------|-------------|
| **99 Names of Allah** | Arabic names with meanings and audio |
| **Tasbih Counter** | Digital dhikr counter with presets |
| **Islamic Calendar** | Hijri calendar with important dates |
| **Streak System** | Daily engagement tracking with badges |
| **Progress Dashboard** | Visual analytics of all activities |
| **Bookmarks Manager** | Organize saved content by type |
| **Theme Toggle** | Light and Dark modes |
| **Customizable Settings** | Font size, playback speed, notifications |

---

## Admin Panel

A comprehensive dashboard for managing the Islamic Digital World application.

### Admin Features

| Section | Description |
|---------|-------------|
| **Overview** | Dashboard with key stats, service status, and quick actions |
| **App Settings** | Configure app name, version, theme, and features |
| **Ad Management** | Control ad placements and configurations |
| **Push Notifications** | Send real-time notifications with templates |
| **Analytics** | User tracking, page views, device stats, world map |
| **Theme Customization** | Colors, fonts, and visual settings |
| **Backup & Restore** | Export/import all configurations |
| **Maintenance Mode** | Global maintenance page with countdown timer and platform targeting |
| **Event Notifications** | Scheduled event broadcasts for holidays and special occasions |
| **Quiz & Leaderboard** | Manage quiz settings and reset leaderboard data |
| **User Feedback** | View, manage, and resolve user-submitted feedback |

### Maintenance Mode

A powerful feature to display a maintenance page across your web and/or mobile applications.

| Setting | Description |
|---------|-------------|
| **Enable/Disable** | Toggle maintenance mode on or off |
| **Title & Message** | Customize the maintenance page content |
| **Time Mode** | Choose between text description or live countdown timer |
| **End Time** | Set specific date/time for countdown mode |
| **Image URL** | Add a custom image (supports JPG, PNG, GIF) |
| **Platform Target** | Apply to Web only, Mobile only, or Both |

**How it works:**
1. Settings are stored in Firestore (`admin_settings/maintenance`)
2. Web and mobile clients check this on page load
3. If enabled for their platform, users see the maintenance page instead of normal content
4. Countdown timer updates in real-time

### Event Notifications

Schedule and broadcast event notifications for Islamic holidays and special occasions.

| Feature | Description |
|---------|-------------|
| **Preset Events** | Quick templates for Ramadan, Eid, Hajj, Islamic New Year, etc. |
| **Custom Events** | Create your own event notifications |
| **Scheduling** | Set events to broadcast at specific dates/times |
| **Platform Targeting** | Send to Web, Mobile, or Both |
| **Rich Content** | Include title, message, icon, and action buttons |

### Quiz & Leaderboard Management

| Action | Description |
|--------|-------------|
| **Reset Category** | Clear progress for a specific quiz category |
| **Reset All Progress** | Clear all quiz progress across all categories |
| **Reset Leaderboard** | Clear the global leaderboard rankings |

### Read-Only Admin Role

The admin panel supports a **Read-Only Admin** role with restricted permissions:

| Permission | Full Admin | Read-Only Admin |
|------------|:----------:|:---------------:|
| View all sections | ✅ | ✅ |
| Modify settings | ✅ | ❌ |
| Send notifications | ✅ | ❌ |
| Toggle maintenance | ✅ | ❌ |
| Delete data | ✅ | ❌ |
| Export data | ✅ | ✅ |

### Home Screen Card Themes

The admin panel provides **13 beautiful card themes** for customizing the home screen appearance:

| Theme Name | Description |
|------------|-------------|
| **Default** | Clean, minimal card design |
| **Cream Arch** | Elegant cream background with arch elements |
| **Midnight Gold** | Dark theme with golden accents |
| **Royal Purple** | Rich purple gradient design |
| **Ocean Blue** | Calm blue oceanic tones |
| **Forest Green** | Natural green aesthetic |
| **Sunset Orange** | Warm sunset gradient colors |
| **Slate Gray** | Professional slate gray look |
| **Rose Pink** | Soft pink feminine design |
| **Cobalt Blue** | Bold cobalt blue theme |
| **Charcoal** | Deep charcoal dark theme |
| **Emerald** | Vibrant emerald green |
| **Burgundy** | Classic burgundy red |

### Card Border Option

A global setting to **add borders to all cards** across all themes:

| Setting | Description |
|---------|-------------|
| **Show Card Borders** | Toggle to enable/disable card borders for all home screen cards |
| **Theme-Aware Borders** | Border colors automatically match each theme's color scheme |

To enable:
1. Go to Admin Panel → Theme Settings
2. Toggle **"Show Card Borders"** option
3. Save settings

---

## Firebase Setup

### Required Firebase Services

1. **Firebase Realtime Database** - For real-time data sync
2. **Firebase Analytics** - For user tracking (optional)

### Database Rules

```json
{
  "rules": {
    "pushNotifications": {
      ".read": true,
      ".write": true,
      "history": {
        ".indexOn": ["timestamp"]
      }
    },
    "appConfig": {
      ".read": true,
      ".write": true
    },
    "analytics": {
      ".read": true,
      ".write": true
    },
    "admin": {
      ".read": true,
      ".write": true
    },
    ".read": false,
    ".write": false
  }
}
```

### Database Paths Used

| Path | Purpose |
|------|---------|
| `pushNotifications/history` | Notification history and real-time delivery |
| `pushNotifications/stats` | Notification statistics |
| `pushNotifications/subscribers` | User subscription tokens |
| `analytics/users` | Visitor tracking |
| `analytics/pageViews` | Page view counts |
| `analytics/countries` | Country-wise statistics |
| `analytics/locations` | Map marker data |
| `analytics/devices` | Device type breakdown |
| `analytics/dailyViews` | Daily view statistics |
| `admin/contentUpdates` | Content update tracking |
| `appConfig` | Application configuration |

---

## Technology Stack

### Frontend
```
HTML5          - Semantic markup and structure
CSS3           - Modern styling with CSS Variables, Flexbox, Grid, Animations
JavaScript     - Vanilla ES6+ (No framework dependencies)
Phosphor Icons - Beautiful, consistent icon library
Chart.js       - Analytics charts and visualizations
```

### Backend Services
```
Firebase       - Realtime Database, Analytics, Cloud Messaging
Vercel         - Hosting and deployment
```

### APIs & Services
```
Quran API      - Custom CDN for Quran text and translations
Aladhan API    - Accurate prayer time calculations
Google Translate API - Real-time translation
MyMemory API   - Translation fallback service
Geolocation API - Browser-based location services
ipapi.co       - IP-based geolocation for analytics
```

### Storage & Caching
```
LocalStorage   - User preferences, bookmarks, progress data
Firebase RTDB  - Real-time data synchronization
Cache API      - Offline content caching (PWA)
```

---

## Installation

### Option 1: Direct Browser Use
Simply open `index.html` in any modern web browser.

### Option 2: Local Development Server

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000

# Using VS Code Live Server
# Right-click index.html → "Open with Live Server"
```

### Option 3: Deploy to Production

```bash
# Vercel (Recommended)
vercel --prod

# Netlify
netlify deploy --prod

# GitHub Pages
# Push to gh-pages branch

# Firebase Hosting
firebase deploy
```

### Option 4: Install as PWA

The app includes a **smart install banner** that automatically detects your device and provides appropriate installation instructions.

#### Android (Chrome/Edge)
1. Open the app in Chrome or Edge browser
2. Wait for the install banner to appear (or tap the install icon in address bar)
3. Tap **"Install"** button
4. Confirm by tapping **"Add to Home Screen"**

#### iOS (Safari)
1. Open the app in Safari browser
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"** in the top right corner

#### Desktop (Chrome/Edge/Firefox)
1. Open the app in your browser
2. Look for the install icon in the address bar (⊕ or ⬇)
3. Click **"Install"** or use Menu → **"Install Islamic Digital World"**

---

## Configuration

### API Endpoints

```javascript
const CONFIG = {
    // Quran Data
    API_BASE: 'https://islamicdata.netlify.app/AlQuran',
	
    // Hadith Collections
    HADITH_BASE: 'https://islamicdata.netlify.app/Hadiths/JSON',
    
    // Quiz Questions
    QUIZ_ADULT: 'https://islamicdata.netlify.app/Quiz/islamic_quiz.json',
    QUIZ_KIDS: 'https://islamicdata.netlify.app/Quiz/islamic_quiz_children.json',
    
    // Prayer Times
    PRAYER_API: 'https://api.aladhan.com/v1/timings',
    
    // Translation
    TRANSLATE_API: 'https://translate.googleapis.com/translate_a/single'
};
```

### Firebase Configuration

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    databaseURL: "https://YOUR_PROJECT-default-rtdb.firebaseio.com",
    projectId: "YOUR_PROJECT",
    storageBucket: "YOUR_PROJECT.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID",
    measurementId: "YOUR_MEASUREMENT_ID"
};
```

---

## API References

### Quran API

```http
# Get Surah Arabic Text
GET /surah/surah_{1-114}.json

# Get Translation
GET /translation/{lang}/{lang}_translation_{001-114}.json

# Supported Languages: en, bn, hi, ur, id, es, fr, ru, zh
```

### Prayer Times API (Aladhan)

```http
GET https://api.aladhan.com/v1/timings/{unix_timestamp}
    ?latitude={lat}
    &longitude={lng}
    &method={1-15}
    &school={0|1}
```

---

## Localization

### Supported Languages

| Code | Language | Quran | Hadith | Dua | Quiz |
|------|----------|-------|--------|-----|------|
| en | English | ✅ | ✅ | ✅ | ✅ |
| bn | Bangla | ✅ | ✅ | ✅ | ✅ |
| hi | Hindi | ✅ | ✅ | ✅ | ✅ |
| ur | Urdu | ✅ | ✅ | ✅ | ✅ |
| id | Indonesian | ✅ | ✅ | ✅ | ✅ |
| es | Spanish | ✅ | ✅ | ✅ | ✅ |
| fr | French | ✅ | ✅ | ✅ | ✅ |
| ru | Russian | ✅ | ✅ | ✅ | ✅ |
| zh | Chinese | ✅ | ✅ | ✅ | ✅ |

---

## Browser Support

| Browser | Minimum Version | Status |
|---------|-----------------|--------|
| Google Chrome | 80+ | ✅ Full Support |
| Mozilla Firefox | 75+ | ✅ Full Support |
| Safari | 13+ | ✅ Full Support |
| Microsoft Edge | 80+ | ✅ Full Support |
| Opera | 67+ | ✅ Full Support |
| Samsung Internet | 12+ | ✅ Full Support |

---

## Offline Capabilities

The app caches the following for offline use:

| Content | Cached |
|---------|--------|
| HTML, CSS, JS files | ✅ |
| Font files & icons | ✅ |
| Previously loaded Quran surahs | ✅ |
| Hadith collections (in memory) | ✅ |
| Quiz questions | ✅ |
| User preferences | ✅ |
| Bookmarks & progress | ✅ |

---

## Ad Integration

This app is fully prepared for ad monetization with pre-built ad placeholders and compliance pages.

### Ad Compliance Requirements

Before running ads, ensure you have:

| Requirement | Status | Location |
|-------------|--------|----------|
| Privacy Policy | ✅ Ready | `/privacy.html` |
| Terms of Service | ✅ Ready | `/terms.html` |
| Contact Page | ✅ Ready | `/contact.html` |
| Footer Links | ✅ Linked | Web & Mobile |

### Web Version Ad Placements

Ad templates are located in `assets/ads-web/`:

| Ad Type | Size | File Location | Placement |
|---------|------|---------------|-----------|
| **Header Banner** | 728x90 | `leaderboard/header.html` | Top of page |
| **Footer Banner** | 728x90 | `leaderboard/footer.html` | Bottom of page |
| **Left Sidebar** | 160x600 | `sidebar/left.html` | Left skyscraper |
| **Right Sidebar** | 160x600 | `sidebar/right.html` | Right skyscraper |
| **Content Rectangle** | 300x250 | `rectangle/content-top.html` | In-content ads |
| **Interstitial** | Fullscreen | `interstitial/popup.html` | Popup overlay |

#### Web Ad Integration Steps

1. **Get your AdSense code** from [Google AdSense](https://www.google.com/adsense/)

2. **Add AdSense script** to `index.html` head:
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```

3. **Replace demo ads** in `assets/ads-web/` files with your ad units:
```html
<!-- Example: Replace demo content with -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
     data-ad-slot="XXXXXXXXXX"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
```

### Mobile Version Ad Placements

Mobile ads are managed through placeholders in `mobile/index.html`:

| Ad Type | Element ID | Location |
|---------|------------|----------|
| **Top Banner** | `#topBannerAd` | Below header |
| **Bottom Banner** | `#bottomBannerAd` | Above navigation |
| **Interstitial** | `#interstitialAdOverlay` | Full-screen overlay |

#### Mobile Ad Integration Steps

1. **Enable banner ads** - Remove `style="display:none;"` from ad containers:
```html
<!-- Top Banner -->
<div class="mobile-ad-container top-banner-ad" id="topBannerAd">
    <!-- Your AdSense or ad network code here -->
</div>

<!-- Bottom Banner -->
<div class="mobile-ad-container bottom-banner-ad" id="bottomBannerAd">
    <!-- Your AdSense or ad network code here -->
</div>
```

2. **Add your ad code** inside the containers:
```html
<ins class="adsbygoogle"
     style="display:inline-block;width:320px;height:50px"
     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
     data-ad-slot="XXXXXXXXXX"></ins>
<script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
```

3. **Interstitial ads** - Show on specific actions:
```javascript
// Show interstitial (e.g., after quiz completion)
function showInterstitialAd() {
    document.getElementById('interstitialAdOverlay').style.display = 'flex';
    // Load your interstitial ad code here
}

// Close interstitial
function closeInterstitialAd() {
    document.getElementById('interstitialAdOverlay').style.display = 'none';
}
```

### Admin Panel Ad Controls

The admin panel includes ad management options:

| Setting | Description |
|---------|-------------|
| **Enable Ads** | Global toggle for all ads |
| **Ad Positions** | Select which positions to show |
| **Ad Frequency** | Control interstitial frequency |

Access via: Admin Panel → Ad Management

### Ad Network Alternatives

Besides Google AdSense, the app supports:

| Network | Type | Notes |
|---------|------|-------|
| **Google AdSense** | Display | Most popular, high fill rate |
| **Media.net** | Display | Yahoo/Bing contextual ads |
| **PropellerAds** | Push/Display | Good for mobile |
| **Ezoic** | AI-optimized | Requires traffic minimum |
| **AdMob** | Mobile | For PWA/App conversion |

### Best Practices

1. **Ad Placement**: Don't place ads near interactive elements
2. **User Experience**: Limit interstitials to avoid high bounce rates
3. **Compliance**: Keep privacy policy updated with ad networks used
4. **Testing**: Use test ad units during development
5. **Loading**: Use lazy loading for non-critical ads

---

## Legal Pages

Essential pages for compliance and monetization:

| Page | Purpose | URL |
|------|---------|-----|
| **Privacy Policy** | Data collection & usage disclosure | `/privacy.html` |
| **Terms of Service** | Usage rules & liability | `/terms.html` |
| **Contact** | User inquiries & support | `/contact.html` |

All pages are:
- Mobile responsive
- Styled to match app theme
- Linked from web footer and mobile settings
- Cached for offline access

---

## Recent Updates

### Version 2.4.0 (January 2025)
- ✅ **Maintenance Mode** - Global maintenance page with platform targeting (Web/Mobile/Both)
- ✅ **Countdown Timer** - Live countdown option for maintenance end time
- ✅ **Image Support** - Upload custom images via URL (JPG, PNG, GIF)
- ✅ **Event Notifications** - Scheduled broadcasts for Islamic holidays and custom events
- ✅ **Quiz & Leaderboard Management** - Reset categories, progress, and leaderboard from admin
- ✅ **User Feedback System** - View, manage, and resolve user feedback submissions
- ✅ **Read-Only Admin Role** - Restricted admin access for view-only permissions
- ✅ **Firestore Rules Update** - Public read access for maintenance settings

### Version 2.3.0 (December 2024)
- ✅ **Card Border Option** - New toggle to add borders to all home screen cards
- ✅ **Theme-Aware Borders** - Border colors automatically match each card theme
- ✅ **Legal Pages** - Added Privacy Policy, Terms of Service, and Contact pages for ad compliance
- ✅ **Ad Integration Guide** - Comprehensive documentation for web and mobile ad setup
- ✅ **Theme Optimization** - Refined to 13 high-quality card themes

### Version 2.2.0 (December 2024)
- ✅ **Push Notifications** - Real-time notifications for online users
- ✅ **Admin Panel** - Complete dashboard for app management
- ✅ **Analytics Dashboard** - User tracking with world map visualization
- ✅ **Notification Management** - Send, view, delete notifications
- ✅ **Quick Templates** - Pre-built notification templates
- ✅ **Firebase Integration** - Real-time database sync
- ✅ **Localhost Filtering** - Exclude development traffic from analytics
- ✅ **Service Status** - Real-time Firebase connection monitoring

### Version 2.1.0 (December 2024)
- ✅ **Smart Install Banner** - Device-aware PWA install prompts
- ✅ **iOS Support** - Step-by-step install instructions for Safari
- ✅ **Hifz Tracker Cards** - Beautiful animated surah cards
- ✅ **99 Names Audio** - Audio playback for each of Allah's names

### Version 2.0.0 (December 2024)
- ✅ Added Islamic Quiz Pro with Adult & Kids modes
- ✅ Gamification system (XP, levels, streaks, badges)
- ✅ Real-time translation for all content
- ✅ Enhanced mobile version with all features

---

## Contributing

We welcome contributions from the community!

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

---

## License

This project is open source and available under the **MIT License**.

```
MIT License

Copyright (c) 2024 Islamic Digital World

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## Credits

| Resource | Provider |
|----------|----------|
| **Quran Data** | [IslamicData](https://islamicdata.netlify.app/) |
| **Prayer Times** | [Aladhan API](https://aladhan.com/) |
| **Translation** | Google Translate, MyMemory |
| **Icons** | [Phosphor Icons](https://phosphoricons.com/) |
| **Charts** | [Chart.js](https://www.chartjs.org/) |
| **Backend** | [Firebase](https://firebase.google.com/) |
| **Hosting** | [netlify](https://netlify.com/) |

---

<div align="center">

**Developed with dedication for the Muslim Ummah**

*Bismillah - In the name of Allah, the Most Gracious, the Most Merciful*

بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ

</div>
