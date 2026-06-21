# VV AUTO SALES - Premium Certified Pre-Owned Vehicles Platform

## Overview

VV AUTO SALES is a modern, responsive web application for showcasing and managing certified pre-owned vehicles. Built with HTML5, Tailwind CSS, and vanilla JavaScript, it features a luxury dark theme with gold accents and comprehensive vehicle inventory management.

## Features

### 🚗 Vehicle Inventory Management
- **Multi-category Support**: 2-wheelers, 3-wheelers, 4-wheelers, and 6-wheelers
- **Dynamic Filtering**: Filter vehicles by category
- **Real-time Search**: Quick vehicle lookup by specifications
- **Image Upload**: Base64 image encoding for vehicle photos
- **Price Display**: Formatted pricing in Indian Rupees (INR)

### 🔐 Admin Dashboard
- **Secure Authentication**: Email and password protected access
- **CRUD Operations**: Create, Read, Update, and Delete vehicles
- **Image Management**: Upload and preview vehicle images
- **LocalStorage Persistence**: All data saved locally in browser

### 📱 Responsive Design
- Mobile-first approach
- Optimized for all screen sizes
- Smooth animations and transitions
- Premium dark theme with gold accents (#d4af37)

### 💬 Customer Communication
- **WhatsApp Integration**: Direct messaging with 1-click contact
- **Contact Form**: Comprehensive inquiry submission
- **Phone & Email**: Multiple contact channels

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **Vanilla JavaScript** - No dependencies
- **FontAwesome Icons** - Premium icon library
- **LocalStorage API** - Client-side data persistence

## Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- No backend server required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/VVSALES/vv-auto-sales.git
cd vv-auto-sales
```

2. Open `index.html` in your browser:
```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js
npx http-server
```

3. Visit `http://localhost:8000`

## Admin Access

### Admin Features
Once logged in, admins can:
- Add new vehicles to inventory
- Edit existing vehicle details
- Delete vehicles from catalog
- Upload vehicle images
- Manage all inventory data

## Data Management

### Default Inventory
The application comes pre-loaded with 4 sample vehicles:
1. Mahindra Bolero Neo N10 (4 Wheeler) - ₹7,45,000
2. Maruti Suzuki Swift VXI (4 Wheeler) - ₹4,95,000
3. Bajaj Auto Maxima Cargo (3 Wheeler) - ₹1,85,000
4. Tata T.11 Ultra Commercial (6 Wheeler) - ₹13,50,000

### LocalStorage Keys
- `vv_premium_stock_store` - Vehicle inventory data
- `vv_admin_session_token` - Admin session state

## Features in Detail

### Vehicle Catalog
- Browse all vehicles or filter by wheel type
- Each vehicle card displays:
  - High-quality image
  - Vehicle name and year
  - Category badge
  - Specifications/condition details
  - Price in Indian Rupees
  - WhatsApp direct chat button
  - Inquiry form shortcut

### Contact Integration
- **Phone**: +91 8918531668
- **WhatsApp**: Direct integration with 1-click messaging
- **Email**: vishnuverma@zohomail.in
- **Contact Form**: Detailed inquiry submission

## Customization

### Change Contact Information
Edit the following in `index.html`:
```html
<!-- Phone number -->
+91 8918531668

<!-- Email -->
vishnuverma@zohomail.in

<!-- WhatsApp number -->
https://wa.me/918918531668
```

### Change Admin Credentials
Edit the login validation in the `handleLoginSubmit()` function:
```javascript
if (email === "your-email@example.com" && pass === "your-password") {
    // Login successful
}
```

### Customize Theme Colors
The primary gold color (#d4af37) is used throughout. Replace with your brand color in the CSS.

## Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Website will be live at `https://username.github.io/vv-auto-sales/`

### Other Platforms
- Netlify
- Vercel
- Firebase Hosting
- Any static hosting service

## Performance Optimizations

- Minimal dependencies
- Lightweight CSS framework (Tailwind)
- Optimized image loading
- Smooth scroll behavior
- CSS animations and transitions

## Security Notes

⚠️ **Important**: 
- This is a client-side application - all data is stored locally in browser
- Admin credentials are hardcoded - suitable only for demonstration
- For production, implement proper backend authentication
- Do not use this setup with sensitive data

## Future Enhancements

- [ ] Backend API integration
- [ ] Database storage (MongoDB, Firebase)
- [ ] User authentication system
- [ ] Payment gateway integration
- [ ] Email notifications
- [ ] Analytics dashboard
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Advanced search filters
- [ ] Vehicle comparison tool

## Project Structure

```
vv-auto-sales/
├── index.html          # Main application file
├── README.md           # This file
└── .gitignore          # Git configuration
```

## License

© 2026 VV AUTO SALES. All Rights Reserved.

## Support

For inquiries and support:
- **Phone**: +91 8918531668
- **Email**: vishnuverma@zohomail.in
- **WhatsApp**: Chat directly through the website

## Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

**Built with ❤️ for VV AUTO SALES**
