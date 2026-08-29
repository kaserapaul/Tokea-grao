# Tokea Grao

App used to check friendly matches within ones location or gps

## 🎯 Features

- **Find Nearby Matches** - Discover friendly football matches in your area
- **GPS Integration** - Use your device's location to find matches near you
- **Smart Filtering** - Filter matches by distance, skill level, and availability
- **Match Details** - View comprehensive information about each match
- **User Profiles** - Manage your profile and match history
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices

## 📁 Project Structure

```
Tokea-grao/
├── index.html      # Main HTML structure
├── styles.css      # Comprehensive styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/kaserapaul/Tokea-grao.git
   cd Tokea-grao
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - No build process or dependencies required!

3. **Start exploring matches**
   - Click "Explore Matches" to see available friendly matches
   - Use "Use My Location" to find matches near you
   - Filter by distance and search criteria

## 🎨 UI/UX Components

### Hero Section
- Eye-catching gradient background
- Clear call-to-action buttons
- Mobile-responsive layout

### Match Cards
- Beautiful card-based design
- Shows match details (location, time, skill level)
- One-click join functionality
- Real-time player count

### Search & Filter
- Keyword search across match titles and locations
- Distance-based filtering
- Responsive filter controls

### User Profile
- Profile picture with bio
- Match statistics
- Edit and view match options

### Navigation
- Sticky header for easy navigation
- Responsive mobile menu
- Active link highlighting

## 💻 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables
- **JavaScript (Vanilla)** - No dependencies, pure JavaScript
- **Font Awesome** - Icons library

## 🔧 How to Customize

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e40af;
    --secondary-color: #06b6d4;
    /* ... more colors */
}
```

### Add Real Data
Replace `mockMatches` in `script.js` with API calls:
```javascript
async function fetchMatches() {
    const response = await fetch('/api/matches');
    return response.json();
}
```

### Enable Backend Integration
1. Update API endpoints in `script.js`
2. Connect to your backend server
3. Implement user authentication
4. Add database for persistent storage

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## ✨ Features Explained

### Geolocation
The app requests user permission to access GPS coordinates and uses them to calculate distance to matches.

### Real-time Filtering
Matches update instantly as you type in the search box or change the distance filter.

### Notifications
Visual feedback when joining matches or performing actions.

### Mobile Menu
Automatic hamburger menu on smaller screens for better navigation.

## 🐛 Known Limitations

- Currently uses mock data (mockMatches array)
- Geolocation requires HTTPS in production
- No user authentication yet
- No persistent storage

## 🚧 Future Enhancements

- [ ] Backend API integration
- [ ] User authentication & profiles
- [ ] Real-time match updates
- [ ] In-app messaging
- [ ] Payment integration
- [ ] Rating & review system
- [ ] Admin dashboard
- [ ] Push notifications
- [ ] Calendar view
- [ ] Team management

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 License

This project is open source and available under the MIT License.

## 📞 Contact

For questions or suggestions, please reach out to [kaserapaul](https://github.com/kaserapaul)

---

**Happy matching! ⚽**
