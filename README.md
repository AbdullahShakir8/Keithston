# 🍰 Keithston - Bakery Website

A modern, responsive bakery e-commerce website built with HTML5, CSS3, and Bootstrap 5.

## 🌐 Live Website
**https://keithston.web.app/**

---

## 📋 Project Overview

Keithston is a professional bakery website showcasing delicious treats and products. The site features a responsive design that works seamlessly across all devices - from mobile phones to desktop computers.

**Tagline:** *"Sweet Treats, Perfect Eats"*

---

## ✨ Features

- 🎨 **Modern & Elegant Design** - Beautiful UI with warm color scheme
- 📱 **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- 🎯 **Multiple Sections:**
  - Hero Header with Call-to-Action
  - Top Products Showcase
  - Explore More Categories (Cakes, Muffins, Croissants, Bread, Tarts)
  - Featured Treats
  - Special Offers (20% Off First Order)
  - About Us Section
  - Responsive Footer with Social Links
- 🔗 **Social Media Integration** - Facebook, Pinterest, WhatsApp, Instagram
- 💳 **Product Cards** - Price, product info, and "Add to Cart" buttons
- 🎭 **Custom Fonts** - Inter & Sansita Swashed from Google Fonts
- 🎨 **Bootstrap Icons** - Professional icon set

---

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **Bootstrap 5.3.8** - Responsive grid system
- **Bootstrap Icons 1.13.1** - Icon library
- **Google Fonts** - Custom typography
- **Firebase Hosting** - Cloud deployment

---

## 📁 Project Structure

```
website_Keithston/
├── public/
│   ├── index.html
│   └── assets/
│       ├── css/
│       │   └── style.css
│       └── images/
│           ├── header.png
│           ├── logo.png
│           ├── products/
│           ├── featuredTreats/
│           ├── exploreMore/
│           ├── footer/
│           └── AboutUs.png
├── firebase.json
├── .firebaserc
└── README.md
```

---

## 🎨 Color Scheme

- **Primary Button:** `#933C24` (Rust Brown)
- **Accent Color:** `#E9BD8C` (Warm Gold)
- **Text Color:** `#5D5D5D` to `#F5F5F5` (Dark Gray to White)
- **Copy Color:** `#737373` (Light Gray)

---

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|-----------|--------|
| Mobile | < 576px | Single column, stacked |
| Tablet | 576px - 768px | 2-3 columns |
| Desktop | > 768px | 4 columns grid |

---

## 🚀 Deployment

The website is deployed on **Firebase Hosting**.

**Deploy Command:**
```bash
firebase deploy
```

**Hosting URL:** https://keithston.web.app/

---

## 💻 Setup Instructions

### Prerequisites
- Node.js & npm (for Firebase CLI)
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AbdullahShakir8/Keithston.git
   cd Keithston
   ```

2. **Install Firebase CLI (if not already installed):**
   ```bash
   npm install -g firebase-tools
   ```

3. **Login to Firebase:**
   ```bash
   firebase login
   ```

4. **Deploy to Firebase:**
   ```bash
   firebase deploy
   ```

---

## 📝 Key Sections

### 1. Header Section
- Navigation bar with mobile toggle
- Hero banner with tagline
- Call-to-action buttons ("Shop Now", "Learn More")

### 2. Top Products
- 8 featured products
- Price display
- Add to cart functionality

### 3. Explore More
- 6 product categories
- Responsive image gallery
- Active category filtering

### 4. Featured Treats
- 4 specialty items
- Product names and pricing
- Beautiful cards with hover effects

### 5. Footer (Responsive)
- Logo and social media links
- About Us information
- Explore links
- Recent news section
- Copyright information

---

## 🔧 Recent Updates

### Responsive Footer Implementation
- Changed from fixed height (100vh) to responsive `min-height`
- Implemented Bootstrap grid system for footer layout
- Added media queries for mobile/tablet screens
- Fixed background image coverage with `background-size: cover` and `background-attachment: scroll`
- Footer now properly stacks on mobile devices

---

## 📞 Contact Information

**Address:** South 13th Street, New York, America  
**Phone:** (456) 789-12301  
**Email:** info@modrino.co.uk

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Developer

Created with ❤️ by Abdullah Shakir

---

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

---

## 📌 Notes

- The website is optimized for all browsers (Chrome, Firefox, Safari, Edge)
- Cache-busting can be added to assets for fresh updates: `href="assets/css/style.css?v=1.0"`
- All images are optimized for web performance
- Responsive design tested on multiple devices

---

**Last Updated:** April 25, 2026  
**Version:** 1.0.0

