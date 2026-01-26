# Digital Album

A digital photo gallery built with Tailwind CSS.

## Setup Instructions

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Build CSS:**
   ```bash
   npm run build
   ```

3. **Watch for changes (development):**
   ```bash
   npm run build-css
   ```

4. **Open `index.html` in your browser** to see the result.

## Vercel Deployment

This project is configured for easy deployment on Vercel:

### Automatic Deployment
1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Connect your repository to Vercel
3. Vercel will automatically detect the project configuration and deploy it

### Manual Deployment
1. Install the Vercel CLI:
   ```bash
   npm i -g vercel
   ```
2. Run the deployment command:
   ```bash
   vercel
   ```
3. Follow the prompts to deploy your project

### Deployment Configuration
- **Build Command**: `npm run vercel-build`
- **Output Directory**: `dist`
- **Install Command**: `npm install`

The project includes a `vercel.json` configuration file that handles:
- Build process automation
- Static file caching
- Proper routing for single-page application behavior

## Project Structure

```
digital-album/
├── src/
│   └── input.css          # Tailwind CSS input file
├── dist/
│   └── output.css         # Compiled CSS file
├── index.html             # Main HTML file
├── package.json           # Dependencies and scripts
├── tailwind.config.js     # Tailwind configuration
├── postcss.config.js      # PostCSS configuration
└── README.md             # This file
```

## Available Scripts

- `npm run build` - Build CSS once
- `npm run build-css` - Build CSS and watch for changes

## Tailwind CSS Features Used

- Responsive grid layout
- Flexbox utilities
- Color gradients
- Shadow effects
- Typography utilities
- Spacing utilities
