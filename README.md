# 📚 RecoReads

A modern, interactive web application for discovering and searching books with a beautiful, responsive user interface.

## 🌟 Overview

**RecoReads** is a lightweight, single-page application that allows users to search and explore books instantly. Built with vanilla HTML, CSS, and JavaScript, it integrates with the Open Library API to provide real-time book data without requiring a backend server.

## ✨ Key Features

- 🔍 **Real-time Search** – Instantly search books by title, author, or keyword
- 📱 **Responsive Design** – Seamless experience across desktop, tablet, and mobile devices
- 🎨 **Modern UI** – Beautiful gradient design with smooth animations and transitions
- ⚡ **Fast Performance** – Lightweight and optimized for quick load times
- 🎯 **User-Friendly** – Intuitive interface with visual feedback for all interactions
- 📖 **Book Details** – Display cover images, titles, authors, and publication years
- 🚀 **No Backend Required** – Fully client-side application with API integration

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Modern styling with gradients and animations |
| **JavaScript (Vanilla)** | DOM manipulation and API integration |
| **Bootstrap 4** | Responsive grid layout |
| **Font Awesome 6** | Icon library |
| **Open Library API** | Book data source |

## 📂 Project Structure

```
book-finder/
├── index.html          # Main application page
├── style.css           # Application styling and animations
├── app.js              # Core application logic
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required

### Installation

1. **Clone or download the repository:**
   ```bash
   git clone https://github.com/your-username/book-finder.git
   cd book-finder
   ```

2. **Open the application:**
   - Simply double-click `index.html` or open it in your preferred browser
   - Or use a local server (recommended):
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

## 📖 Usage

1. **Search for Books:**
   - Enter a book title, author name, or keyword in the search box
   - Press Enter or click the "Search" button
   - Browse the results displayed as interactive cards

2. **View Book Details:**
   - Each book card displays:
     - Book cover image
     - Title
     - Author name
     - Publication year
     - "Learn More" action button

3. **Responsive Layout:**
   - Desktop: 4 books per row
   - Tablet: 3 books per row
   - Mobile: 1-2 books per row

## 🔌 API Integration

This application uses the **Open Library API** (free, no authentication required):

- **Endpoint:** `https://openlibrary.org/search.json`
- **Parameters:** `title`, `author`, `limit`
- **Rate Limit:** Generous for development purposes

**Example Request:**
```
https://openlibrary.org/search.json?title=Harry%20Potter&limit=12
```

## 🎨 Design Features

### Color Scheme
- Primary Gradient: `#667eea` to `#764ba2`
- Text: `#666` (dark gray)
- Accents: Purple and blue tones

### Animations
- Smooth fade-in and slide transitions
- Hover effects on cards and buttons
- Loading spinner animation
- Interactive form elements

### Responsive Breakpoints
- **Desktop:** ≥ 992px (lg)
- **Tablet:** 768px - 991px (md)
- **Mobile:** < 768px (sm)

## 💡 Key JavaScript Functions

| Function | Description |
|----------|-------------|
| `searchBooks()` | Handles search query and API call |
| `createBookCard()` | Generates book card DOM elements |
| `showLoading()` | Toggles loading spinner visibility |
| `showNoResults()` | Displays no results message |

## 🔄 How It Works

1. User enters search query and clicks search
2. Loading spinner displays
3. JavaScript fetches data from Open Library API
4. Response is parsed and book cards are generated
5. Cards are animated into view
6. No results message shows if search yields no books

## 🌐 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | Latest | ✅ Fully Supported |
| Firefox | Latest | ✅ Fully Supported |
| Safari | Latest | ✅ Fully Supported |
| Edge | Latest | ✅ Fully Supported |
| IE 11 | - | ❌ Not Supported |

## 🚀 Future Enhancements

- [ ] Add filters by genre, publication year, and rating
- [ ] Implement book favorites/wishlist feature
- [ ] Add local storage for search history
- [ ] Integrate Google Books API for additional data
- [ ] Create detailed book info modal
- [ ] Add dark mode toggle
- [ ] Implement pagination for results
- [ ] Add book rating and review system
- [ ] Deploy to GitHub Pages or Vercel

## 📸 Screenshots

*Add screenshots of your application here*

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

**Your Name**
- GitHub: (https://github.com/shruti0890)


--
