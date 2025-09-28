# TokSupply Website Clone

A modern, responsive website clone of TokSupply.site built with vanilla HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Mobile-first approach that works on all devices
- **Interactive Quantity Selector**: Increase/decrease buttons with keyboard support
- **Dynamic Price Calculation**: Real-time total updates based on quantity
- **Modern UI**: Clean, professional design matching the original
- **Payment Integration Ready**: Structure in place for Stripe integration
- **Accessibility**: Semantic HTML and keyboard navigation support

## Files Structure

```
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Key Features Implemented

### 1. HTML Structure
- Semantic HTML5 elements
- Proper meta tags for SEO
- Accessible form controls
- Google Fonts integration (Inter font family)

### 2. CSS Styling
- Modern, clean design
- Responsive breakpoints for mobile and tablet
- Smooth transitions and hover effects
- Professional color scheme
- Mobile-first responsive design

### 3. JavaScript Functionality
- Quantity selector with +/- buttons
- Real-time price calculation ($5 per account)
- Form validation (min: 1, max: 1000)
- Keyboard support (arrow keys)
- Purchase button with loading state
- Smooth user interactions

## Usage

1. Open `index.html` in a web browser
2. Use the quantity selector to choose number of accounts (1-1000)
3. See real-time price updates
4. Click "buy now" to simulate purchase process

## Customization

### Changing the Price
Edit the `PRICE_PER_ACCOUNT` constant in `script.js`:
```javascript
const PRICE_PER_ACCOUNT = 5; // Change this value
```

### Styling Modifications
All styling is contained in `styles.css`. Key sections:
- Colors and typography
- Layout and spacing
- Responsive breakpoints
- Interactive elements

### Adding Real Payment Processing
Replace the `handlePurchase()` function in `script.js` with actual Stripe integration:

```javascript
function handlePurchase() {
    // Integrate with Stripe API
    // Create payment intent
    // Process payment
    // Handle success/error responses
}
```

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## Legal Disclaimer

This is a clone/demo website. The original legal disclaimer from TokSupply is included in the footer. Ensure compliance with platform terms of service and local laws when selling social media accounts.

## License

This project is for educational/demonstration purposes. Please respect the original TokSupply brand and intellectual property.
