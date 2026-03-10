# Headcount – Digital Recruitment Advertising

A modern, responsive website for Headcount, a digital recruitment advertising platform that reaches passive candidates across Google, Meta, and TikTok.

## 🚀 Features

- **Responsive Design** – Mobile-first approach, fully responsive across all devices
- **Modern Stack** – Built with Tailwind CSS and Iconify icons
- **Form Integration** – Contact form powered by Formspree for email notifications
- **SEO Optimized** – Proper meta tags and semantic HTML
- **Performance** – Fast-loading with CDN-hosted dependencies
- **Accessibility** – Semantic HTML and ARIA labels for screen readers

## 📁 Project Structure

```
headcount/
├── index.html          # Home page
├── contact.html        # Contact/signup form page
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── LICENSE             # MIT License
```

## 📋 Pages

### index.html – Home Page
The main landing page featuring:
- Hero section with clear value proposition
- Why digital recruitment works (statistics)
- Platform overview (Google, Meta, TikTok)
- 6 key benefits
- Transparent pricing section
- White label hosting info
- Customer testimonials
- Call-to-action sections

### contact.html – Contact Form
A dedicated contact page with:
- Branded header matching home page
- Multi-field contact form
- Form validation
- Formspree integration for email delivery
- Success message on submission
- Navigation back to home

## 🔧 Setup & Deployment

### Local Development

Simply open `index.html` in your browser. No build tools or dependencies needed – the site uses CDN-hosted libraries.

```bash
# Open in browser (macOS)
open index.html

# Or use a local server
python -m http.server 8000
# Visit http://localhost:8000
```

### GitHub Pages Deployment

1. Create a new GitHub repository named `headcount` (or your preferred name)
2. Initialize git in the project directory:

```bash
git init
git add .
git commit -m "Initial commit: Production-ready Headcount website"
git branch -M main
git remote add origin https://github.com/thomasjstone-create/headcount.git
git push -u origin main
```

3. Enable GitHub Pages in repository settings:
   - Settings → Pages
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
   - Save

4. Your site will be available at: `https://thomasjstone-create.github.io/headcount/`

## 📧 Form Configuration

The contact form uses **Formspree** for email handling. Currently configured to send to: `thoms.j.stone@gmail.com`

To change the email:
1. Visit [Formspree.io](https://formspree.io)
2. Create a new form and get your form ID
3. Update the `action` attribute in `contact.html`:

```html
<form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## 🎨 Customization

### Colors
The site uses a purple color scheme. Primary color: `#7c3aed` (purple-600)

To change, search and replace:
- `#7c3aed` (primary purple)
- `#4f46e5` (secondary purple)
- Or modify Tailwind color classes (e.g., `bg-purple-600`)

### Content
All text content can be easily edited directly in the HTML files. Key sections to customize:

- **Company name**: Replace "Headcount" throughout
- **Pricing**: Update £249 amount in both pages
- **Features**: Edit the 6 benefits section
- **Testimonials**: Update company names and quotes
- **Footer**: Update company info and social links

### Fonts
Currently uses **Satoshi** font from Fontshare and **Lucide** icons. Both are loaded from CDN.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## ✨ Performance

- **CSS**: Tailwind CSS via CDN (production build)
- **Icons**: Iconify icon library (on-demand loading)
- **Font**: Fontshare API (Google Fonts alternative)
- **Size**: ~50KB total assets (before compression)

## 🔒 Privacy & Security

- Form submissions use HTTPS via Formspree
- No sensitive data stored in cookies
- No tracking tools or analytics included
- Privacy policy link should be updated in footer with your own policy

## 📝 License

MIT License – Feel free to use this as a template for your own projects.

## 🤝 Support

For Formspree issues, visit: https://formspree.io/help

For Tailwind CSS questions, see: https://tailwindcss.com/docs

## 📞 Contact

Add your actual contact information here when ready for production.

---

**Ready to go live?**
1. Verify all links and content are correct
2. Test the contact form
3. Push to GitHub
4. Enable GitHub Pages
5. Share your deployment link!

```

## 🎯 Next Steps

- [ ] Customize company branding and colors
- [ ] Update footer contact information
- [ ] Add real company logo (replace SVG icon)
- [ ] Create proper privacy policy
- [ ] Set up analytics (GA4 optional)
- [ ] Configure custom domain (optional)
- [ ] Test form submissions
- [ ] Submit sitemap to Google Search Console