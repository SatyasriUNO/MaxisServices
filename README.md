# Maxis Services Website

A modern, responsive website for Maxis Services - an electrical goods distribution company.

## 🌟 Features

- **5 Complete Pages**: Home, About Us, Projects, Channel Partners, Contact Us
- **Responsive Design**: Mobile-first approach, optimized for all devices
- **Blue & Purple Theme**: Professional color scheme matching brand guidelines
- **Smooth Animations**: Page transitions and scroll animations
- **Contact Form**: Fully functional contact form with validation
- **Partner Showcase**: Display and highlight partner companies
- **Project Gallery**: Portfolio of completed projects with filtering
- **Modern UI**: Clean, professional design with intuitive navigation

## 📁 Project Structure

```
maxis-website/
├── index.html           # Home page
├── about.html          # About Us page
├── projects.html       # Projects portfolio page
├── partners.html       # Channel Partners page
├── contact.html        # Contact Us page
├── css/
│   └── styles.css      # Main stylesheet (responsive, animations)
├── js/
│   └── script.js       # JavaScript for interactivity
├── .gitignore          # Git ignore file
├── README.md           # This file
└── vercel.json         # Vercel deployment configuration
```

## 🎨 Color Scheme

```
Primary Colors:
- Dark Blue: #003366
- Medium Blue: #0066CC
- Light Blue: #E6F0FF
- Purple (Accent): #6B46C1
- White: #FFFFFF
```

## 🚀 Quick Start

### Local Development

1. **Clone the repository** (if on GitHub):
   ```bash
   git clone https://github.com/yourusername/maxis-website.git
   cd maxis-website
   ```

2. **Open index.html** in your browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

3. **Or use a local server**:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

   Then open `http://localhost:8000` in your browser.

## 📤 Deployment to Vercel

### Option 1: Vercel Dashboard (Easiest)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "Import Project"
4. Select your GitHub repository
5. Click "Deploy"
6. Your site will be live instantly!

### Option 2: Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Run deployment command:
   ```bash
   vercel
   ```

3. Follow the prompts and your site will be deployed!

## 🔧 Customization

### Update Company Information

Edit these files to add your company details:

- **index.html**: Update hero section, stats, and featured projects
- **about.html**: Add founder bio, team members, timeline
- **projects.html**: Add your actual projects with descriptions
- **partners.html**: Replace partner logos with actual company names/links
- **contact.html**: Update office addresses, phone numbers, emails

### Change Colors

Edit `css/styles.css` and update the CSS variables:

```css
:root {
    --dark-blue: #003366;
    --medium-blue: #0066CC;
    --light-blue: #E6F0FF;
    --purple: #6B46C1;
    --white: #FFFFFF;
}
```

### Add Images

Replace placeholder text in project/partner cards with actual images:

```html
<div class="project-image">
    <img src="path/to/image.jpg" alt="Project Description">
</div>
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Optimization

- Minified CSS and JavaScript
- Responsive images for all screen sizes
- Smooth animations using CSS transitions
- Lazy loading support for images
- Mobile-optimized navigation

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Success feedback message
- All required fields marked with *
- Department-specific routing (on backend integration)

**Note**: Currently, the form displays a success message locally. To send actual emails, integrate with a backend service like:
- Formspree (simple, no backend needed)
- EmailJS (client-side email)
- Your own Node.js backend

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔐 Security Considerations

- No sensitive data stored in frontend
- Form inputs validated before submission
- No API keys exposed
- HTTPS ready for Vercel deployment

## 📝 SEO

Each page includes:
- Proper meta tags
- Semantic HTML structure
- Mobile viewport settings
- Descriptive page titles
- Page-specific descriptions

## 🎯 Next Steps

1. **Add Real Images**: Replace placeholder text with actual project photos
2. **Update Content**: Fill in real company information
3. **Integrate Backend**: Connect contact form to email service
4. **Add Analytics**: Implement Google Analytics tracking
5. **Domain Setup**: Connect custom domain to Vercel

## 📞 Support

For modifications or issues:
- Check the HTML/CSS/JS files for inline comments
- Verify file paths are correct
- Ensure all images are in the correct location
- Test on multiple devices before deployment

## 📄 License

This project is created for Maxis Services. All content and design are proprietary.

## 🔄 Deployment Checklist

- [ ] Update all company information
- [ ] Add real logos and images
- [ ] Test all links and forms
- [ ] Check mobile responsiveness
- [ ] Test contact form
- [ ] Update footer social links
- [ ] Verify all pages load correctly
- [ ] Push to GitHub
- [ ] Deploy to Vercel
- [ ] Test live website
- [ ] Setup custom domain (optional)

---

**Built with ❤️ for Maxis Services**
Modern, responsive, and ready to deploy!
