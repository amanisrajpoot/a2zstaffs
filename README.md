# A2Z Staffing Solutions

A modern, vibrant staffing agency website built with Astro and Tailwind CSS.

## Features

- ✅ Modern, tech-friendly design with vibrant indigo/purple/cyan color scheme
- ✅ Dark mode support
- ✅ Fully responsive design
- ✅ Professional SVG icons
- ✅ Form integration ready (Formspree/Web3Forms)
- ✅ SEO optimized
- ✅ Fast and lightweight

## Tech Stack

- **Framework**: Astro 5.15.4
- **Styling**: Tailwind CSS 4.1.17
- **Deployment**: Vercel-ready

## Development

```bash
npm install    # Install dependencies
npm run dev    # Start dev server
npm run build  # Build for production
npm run preview # Preview production build
```

## Deployment

### Vercel Deployment

This project is ready for direct deployment on Vercel:

1. **Connect Repository**:
   - Go to [Vercel](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository: `https://github.com/amanisrajpoot/a2zstaffs.git`

2. **Automatic Configuration**:
   - Vercel will automatically detect Astro
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Install Command: `npm install`

3. **Deploy**:
   - Click "Deploy"
   - Your site will be live in minutes!

### Manual Deployment

If you prefer manual deployment:

```bash
npm run build
# Deploy the 'dist' folder to your hosting provider
```

## Form Integration

Forms are configured for Formspree. To activate:

1. Sign up at [Formspree](https://formspree.io)
2. Get your form IDs
3. Replace `YOUR_FORM_ID` in:
   - `src/pages/contact.astro`
   - `src/pages/candidates.astro`
   - `src/pages/clients.astro`
   - `src/components/Footer.astro` (newsletter)

## Project Structure

```
src/
  components/    # Reusable components
  layouts/       # Page layouts
  pages/         # Route pages
  styles/        # Global styles
```

## Pages

- `/` - Homepage
- `/about` - About Us
- `/services` - Our Services
- `/jobs` - Job Openings
- `/candidates` - For Candidates
- `/clients` - For Clients
- `/contact` - Contact Us

## License

All rights reserved - A2Z Staffing Solutions
