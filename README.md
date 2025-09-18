# PersonalAI Website

A modern, responsive website for PersonalAI - the first truly private, offline AI assistant hardware.

## Key Features

- **🔒 Complete Privacy**: Your data never leaves your device
- **📡 Works Offline**: No internet dependency required  
- **💰 Buy Once, Own Forever**: No monthly subscriptions

## Tech Stack

- Pure HTML5, CSS3, and JavaScript
- Mobile-first responsive design
- Formspree integration for form handling
- Modern gradient design with smooth animations

## Pages

- **Homepage** (`index.html`) - Hero section, three pillars, signup
- **Features** (`features.html`) - Detailed AI capabilities and use cases
- **Privacy** (`privacy.html`) - Privacy benefits and comparisons
- **About** (`about.html`) - Company mission, values, and contact

## Setup

1. Clone this repository
2. Create a [Formspree](https://formspree.io) account
3. Replace `YOUR_FORM_ID` in HTML files with your Formspree endpoint
4. Deploy to your hosting platform (Render, Netlify, Vercel, etc.)

## Local Development

Simply open `index.html` in your browser to view locally.

For a local server:
```bash
# Python 3
python -m http.server 8000

# Python 2  
python -m SimpleHTTPServer 8000

# Node.js (if you have it)
npx serve .
```

Then visit `http://localhost:8000`

## Deployment

This is a static website that can be deployed to:
- [Render](https://render.com) (recommended)
- [Netlify](https://netlify.com)
- [Vercel](https://vercel.com)
- [GitHub Pages](https://pages.github.com)

## Form Setup

1. Go to [formspree.io](https://formspree.io)
2. Create a free account
3. Create a new form
4. Copy the form endpoint (looks like `https://formspree.io/f/YOUR_FORM_ID`)
5. Replace `YOUR_FORM_ID` in the following files:
   - `index.html` (signup form)
   - `about.html` (contact form)

## Customization

- **Colors**: Edit CSS custom properties in `style.css`
- **Content**: Update HTML files with your specific information
- **Logo**: Replace the text logo in navigation with your image
- **Analytics**: Add your tracking code before closing `</body>` tag

## Contact

For questions about this website template, please open an issue.

---

**PersonalAI** - AI that's truly personal