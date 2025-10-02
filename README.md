# 🚀 Beta Testing Signup Page

A professional and user-friendly beta testing signup page for **Alif Play** and **Hajj & Umrah Guide** mobile applications.

![Beta Testing](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📱 Featured Apps

### Alif Play
Educational learning app focusing on Arabic alphabet and language fundamentals.
- **Status**: iOS 2.0 - Pending Developer Release
- **Platform**: iOS (iPhone/iPad)

### Hajj & Umrah Guide
Comprehensive spiritual journey companion for pilgrims.
- **Status**: iOS 1.0 - Waiting for Review
- **Platform**: iOS (iPhone/iPad)

## 🌟 Features

- ✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- ✅ **User-Friendly Form** - Easy signup process with validation
- ✅ **Professional UI** - Modern gradient design with smooth animations
- ✅ **App Selection** - Dropdown to choose which app(s) to test
- ✅ **Platform Selection** - Support for iOS and Android testers
- ✅ **Success Feedback** - Instant confirmation message after signup
- ✅ **Fallback Icons** - SVG placeholders if images fail to load

## 🚀 Quick Start

### Option 1: Deploy to GitHub Pages (Recommended)

1. **Create a new repository**
   ```bash
   # On GitHub.com:
   # - Click "+" → "New repository"
   # - Name: app-testers (or your choice)
   # - Public repository
   # - Initialize with README
   ```

2. **Upload files**
   - Upload `index.html` to the root directory
   - Create an `images` folder
   - Upload your app icon images to the `images` folder

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Deploy from branch
   - Branch: main / (root)
   - Save

4. **Access your site**
   ```
   https://[your-username].github.io/app-testers/
   ```

### Option 2: Local Testing

```bash
# Clone or download the repository
git clone https://github.com/your-username/app-testers.git

# Open the file in your browser
open index.html
# or
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

## 📁 Project Structure

```
app-testers/
├── index.html          # Main HTML file
├── README.md          # This file
└── images/            # App icons folder
    ├── alifplay-icon.png
    └── hajj-umrah-icon.png
```

## 🎨 Adding Your App Icons

1. **Prepare your icons**
   - Recommended size: 512x512px or 1024x1024px
   - Format: PNG with transparency
   - File names:
     - `alifplay-icon.png`
     - `hajj-umrah-icon.png`

2. **Upload to GitHub**
   - In your repository, click "Add file" → "Upload files"
   - Create an `images` folder (type `images/` before filename)
   - Upload both icon files
   - Commit changes

3. **Icons are automatically loaded**
   - The page will display your icons
   - SVG fallbacks show if images fail to load

## 📊 Form Data Collection

The current form displays a success message but doesn't store data. Choose one of these options to collect submissions:

### Option A: Google Forms Integration

1. Create a Google Form with matching fields
2. Get the form action URL
3. Update the form in `index.html`

### Option B: Formspree (Easiest)

1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Get your form endpoint
4. Update the JavaScript in `index.html`:

```javascript
fetch('https://formspree.io/f/YOUR_FORM_ID', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(formData)
});
```

### Option C: Google Sheets (Advanced)

1. Create a Google Sheet
2. Use Google Apps Script to create a web app
3. Update the form action URL

## 🔧 Customization

### Change Colors

Edit the CSS variables in `index.html`:

```css
/* Purple gradient (current) */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Blue gradient */
background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);

/* Orange gradient */
background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
```

### Update Contact Email

Find and replace in `index.html`:

```html
<a href="mailto:support@example.com">support@example.com</a>
```

### Modify App Information

Update the app cards section:

```html
<div class="app-name">Your App Name</div>
<div class="app-status">
    <span class="status-badge"></span>
    iOS 1.0 - Status Text
</div>
```

## 📱 Testing Checklist

- [ ] Test on desktop browsers (Chrome, Safari, Firefox)
- [ ] Test on mobile devices (iOS Safari, Android Chrome)
- [ ] Verify form validation works
- [ ] Check that success message displays
- [ ] Confirm email addresses are validated
- [ ] Test dropdown selections
- [ ] Verify app icons display correctly
- [ ] Check responsive design on different screen sizes

## 🔗 Links

- **Live Demo**: `https://[your-username].github.io/app-testers/`
- **Repository**: `https://github.com/[your-username]/app-testers`
- **Issues**: Report bugs or request features

## 📝 TODO

- [ ] Integrate with TestFlight for automatic invitations
- [ ] Add Google Play Beta program integration
- [ ] Set up email notifications for new testers
- [ ] Add analytics to track signup conversion
- [ ] Create admin dashboard to view tester list
- [ ] Add multi-language support (Arabic/English)

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💬 Support

For questions or issues:
- Email: support@example.com
- Create an issue in this repository

## 🙏 Acknowledgments

- Icons created using actual app assets
- Design inspired by modern app landing pages
- Built with vanilla HTML, CSS, and JavaScript

---

**Made with ❤️ for Beta Testers**

*Last Updated: October 2025*