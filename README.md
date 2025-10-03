# AutophaShield™ Frontend

Modern, responsive website for AutophaShield supplement - featuring React, Vite, TypeScript, and Tailwind CSS v4.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🔧 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_FORMSPREE_ENDPOINT=https://formspree.io/f/YOUR_FORM_ID
VITE_GA_MEASUREMENT_ID=G-XXXXXXXXXX
```

### Get Formspree Endpoint:
1. Go to https://formspree.io/
2. Sign up (free)
3. Create new form
4. Copy form endpoint URL

### Get Google Analytics ID:
1. Go to https://analytics.google.com/
2. Create property
3. Copy Measurement ID (G-XXXXXXXXXX)

## 📦 Deployment

### Vercel (Recommended)

1. **Push to GitHub:**
```bash
git add .
git commit -m "Deploy to Vercel"
git push
```

2. **Deploy on Vercel:**
- Go to https://vercel.com/
- Import your GitHub repository
- Add environment variables in Vercel dashboard
- Deploy automatically!

### Alternative Hosting:
- **Netlify:** Drag & drop `dist` folder after build
- **GitHub Pages:** Use `gh-pages` package
- **AWS S3 + CloudFront:** Upload `dist` folder

## 🛠️ Tech Stack

- **Frontend:** React 19 + TypeScript
- **Build Tool:** Vite 7
- **Styling:** Tailwind CSS v4
- **Routing:** React Router v7
- **Form Handling:** Formspree
- **Analytics:** Google Analytics

## 📁 Project Structure

```
AutophaShield/
├── public/
│   └── images/          # All product images
├── src/
│   ├── components/      # Reusable components
│   ├── pages/           # Page components
│   │   ├── Home.tsx
│   │   ├── Science.tsx
│   │   ├── Ingredients.tsx
│   │   ├── Contact.tsx
│   │   └── ThankYou.tsx
│   ├── lib/            # Utilities
│   ├── App.tsx         # Main app component
│   ├── main.tsx        # Entry point
│   └── styles.css      # Global styles
├── vercel.json         # Vercel configuration
└── package.json        # Dependencies

```

## 🎨 Color Scheme

- **Primary Green:** `#004d26`
- **Accent Orange:** `#ff9a2f`
- **Light Gray:** `#f8f8f8`

## 📄 License

© 2025 AutophaShield™ - Trademarked and patent-pending. Formulated in the United States.



