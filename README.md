# LinkBox 3000 - Universe Edition 🚀

**LinkBox** is a massive, high-performance resource hub containing over **100,000+ Verified Links** across 137 categories. It features a modern, glassmorphic UI with realistic 3D icons.

![UI Preview](https://via.placeholder.com/800x400?text=LinkBox+Next-Gen+UI)

## ✨ Features
- **150k+ Links**: Curated resources for Movies, Anime, Music, AI, Learning, and more.
- **Glassmorphism UI**: Beautiful, transparent, and responsive design.
- **3D Smart Icons**: Realistic 3D emojis representing each category uniquely.
- **Search & Modal**: Instant search and fast modal-based browsing.
- **Performance**: Optimized to load thousands of links instantly.

## 📁 File Structure
- `index.html`: The main entry point.
- `custom_links.js`: The **Database**. Contains all 100,000+ links in a structured JSON format.
- `script.js`: Core logic for Modal, Search, and Rendering.
- `style.css`: Supplemental styles (Tailwind is loaded via CDN).

## 🚀 How to Run
1. **Clone the Repo**:
   ```bash
   git clone https://github.com/yourusername/linkbox.git
   ```
2. **Open**: Just double-click `index.html` in your browser. No server needed!

## 🛠️ Customization
To add your own links, open `custom_links.js` and add a new block:
```javascript
linkData.unshift({
    "title": "My New Category",
    "icon": "🚀", // Use any Emoji
    "description": "My awesome links",
    "links": [
        { "name": "Google", "url": "https://google.com" }
    ]
});
```

## 📜 License
Free to use for educational and personal purposes.
