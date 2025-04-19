# Sign Up Page

A clean, responsive sign-up page with app download links for Google Play Store and App Store.

## Overview

This project implements a modern sign-up modal with the following features:
- User registration form with validation
- Terms and conditions agreement checkbox
- App download links with store badges
- Responsive design with gradient button styling

## Project Structure

```
sign-up-page/
├── index.html
├── styles.css
├── images/
│   ├── Download Background.jpg
│   ├── Google Play Store.png
│   └── App Store.png
└── README.md
```

## Installation

1. Clone or download this repository
2. Ensure all files maintain the structure shown above
3. Open `index.html` in your web browser

## Key Features

- **Responsive Design**: Works on mobile and desktop devices
- **Modern UI**: Clean interface with gradient buttons and subtle animations
- **Form Validation**: Basic validation for required fields
- **Download Section**: Prominently displays app download options

## Usage

The sign-up form can be integrated into any website by including the HTML structure and CSS. The form submission action needs to be configured in the `<form action="">` attribute to connect with your backend services.

## Image Size Recommendations

For optimal display:
- Store badges (Google Play/App Store): 150px width, auto height
- Background image: High-resolution image that covers the viewport

## Customization

- Change the gradient colors by modifying the `background: linear-gradient()` property in the CSS
- Adjust form width by changing the `.auth-modal` width value
- Customize fonts by replacing the Google Fonts import

## Browser Compatibility

Tested and working in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Free to use for personal and commercial projects.

## Credits

- Fonts: Google Fonts (Readex Pro)
- Background image by Merlin Lightpainting https://www.pexels.com/photo/a-blue-face-glowing-11167645/
