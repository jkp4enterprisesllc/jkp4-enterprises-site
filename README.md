# JKP4 Enterprises - Consulting Website

Expert Level Consulting in Risk Management, Security, Marketing, Team Building, and Leadership Development

## Overview

This is a professional website for JKP4 Enterprises, a consulting firm specializing in:
- 🛡️ Risk Management
- 🔒 Security
- 📈 Marketing, Sales & Brand Awareness
- 🤝 Team Building
- 👔 Leadership Development

## Features

### Client Inquiry Form
The website includes a comprehensive client inquiry form that collects:
- Full Name (required)
- Email Address (required)
- Phone Number (optional)
- Company Name (optional)
- Primary Service Interest (required dropdown)
- Questions and Needs (required text area)

When submitted, the form displays a success message and logs the data to the browser console for backend integration.

### Pricing & General Information
Three consulting packages are offered:
- **Starter** ($2,500) - Perfect for small businesses
- **Professional** ($7,500) - Most popular choice
- **Enterprise** (Custom) - For large organizations

General information includes payment terms, consultation process, turnaround time, travel availability, confidentiality, and satisfaction guarantee.

## How to Use

### Viewing the Website Locally

1. Open the `index.html` file in any modern web browser, or
2. Serve it with a local web server:
   ```bash
   python3 -m http.server 8080
   ```
   Then navigate to `http://localhost:8080/index.html`

### Navigation
- Click on the navigation menu items to jump to different sections
- The navigation bar is sticky and follows you as you scroll
- Active section is highlighted in the navigation

### Form Functionality
- Fill out the inquiry form with your information
- Required fields are marked with an asterisk (*)
- Upon submission, a success message appears
- Form data is logged to the browser console (ready for backend integration)
- Form automatically resets after successful submission

## Technical Details

- **Single-page application** - All content in one HTML file
- **Responsive design** - Works on desktop, tablet, and mobile devices
- **Modern CSS** - Uses CSS Grid and Flexbox for layout
- **Vanilla JavaScript** - No dependencies required
- **Smooth scrolling** - Enhanced user experience with smooth navigation
- **Form validation** - HTML5 form validation with required fields

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Future Enhancements

To integrate with a backend system:
1. Replace the console.log in the form submission handler with an API call
2. Add proper error handling for failed submissions
3. Consider adding reCAPTCHA for spam prevention
4. Store form submissions in a database
5. Send email notifications to administrators
