# AllergyAlly Website

A modern, responsive GitHub Pages website for the AllergyAlly allergy tracking app.

## 🎯 Overview

AllergyAlly is an app that helps users track, monitor, and manage their allergies effortlessly. This website serves as the landing page and information hub for the application.

## 🚀 Features

- **Track Allergies** - Keep detailed records of all allergies and reactions
- **Alert System** - Receive notifications when encountering potential allergens
- **Analytics** - Visualize patterns and trends in allergy data
- **Doctor Sharing** - Share allergy information securely with healthcare providers
- **Privacy First** - Encrypted health data that stays under your control
- **Cross-Platform** - Access your allergies from any device

## 📁 Project Structure

```
allergyally-website/
├── index.html      # Main landing page
├── styles.css      # Styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # Project documentation
```

## 🛠️ Setup & Development

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/serk77/allergyally-website.git
   cd allergyally-website
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` to view the site

### GitHub Pages Deployment

1. Push your code to the `main` branch
2. Go to your repository settings on GitHub
3. Scroll to "GitHub Pages" section
4. Select `main` branch and click Save
5. Your site will be live at `https://serk77.github.io/allergyally-website/`

## 📝 Customization

### Update Contact Information

Edit `index.html` and update the contact links and social media URLs:
- Look for the `<!-- Contact Section -->` 
- Update email links and social profiles in the footer

### Modify Content

- Update app features in the Features section
- Customize the hero content with your messaging
- Add your app download links for iOS and Android

### Brand Colors

Edit `styles.css` and modify the CSS variables at the top:
```css
:root {
    --primary-color: #6366f1;      /* Change primary color */
    --secondary-color: #ec4899;    /* Change secondary color */
    /* ... other colors ... */
}
```

## 📱 Responsive Design

The website is fully responsive and works great on:
- Desktop (1200px and above)
- Tablet (768px to 1199px)
- Mobile (below 768px)

## 🔗 Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (no dependencies)
- Responsive Design

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 💬 Contact

For questions or feedback about the website or AllergyAlly app, please reach out through the contact form on the website.

---

**Happy tracking with AllergyAlly! 🏥**
