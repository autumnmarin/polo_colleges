# Anthony Smernes Jr., Esq. - Attorney Profile Website

Professional website for Anthony Smernes Jr., an AV Preeminent® rated attorney with 60+ years of legal experience.

## About

This website showcases the professional credentials, practice areas, and contact information for Anthony Smernes Jr., Esq., a distinguished California attorney specializing in:
- Real Estate Law
- Business Law
- Civil Litigation
- Construction Law
- Chapter 11 Bankruptcy
- Probate Law

## Serving the Website Locally

### Option 1: Python Simple HTTP Server

**Python 3:**
```bash
python3 -m http.server 8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

Then open your browser to: `http://localhost:8000`

### Option 2: Node.js HTTP Server

Install http-server globally:
```bash
npm install -g http-server
```

Run the server:
```bash
http-server -p 8000
```

Then open your browser to: `http://localhost:8000`

### Option 3: PHP Built-in Server

```bash
php -S localhost:8000
```

Then open your browser to: `http://localhost:8000`

## Deployment Options

### GitHub Pages
1. Push the repository to GitHub
2. Go to repository Settings > Pages
3. Select the branch (main or master)
4. Select root directory
5. Click Save
6. Your site will be available at `https://username.github.io/repo-name`

### Netlify
1. Sign up at [netlify.com](https://www.netlify.com)
2. Drag and drop the project folder
3. Site will be live instantly with a custom URL
4. Can connect to GitHub for automatic deployments

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts
4. Site will be deployed instantly

### Traditional Web Hosting
1. Upload files via FTP/SFTP to your web host
2. Ensure `index.html` is in the root directory
3. Access via your domain name

## File Structure

```
.
├── index.html          # Main website file (self-contained)
├── README.md          # This file
├── robots.txt         # Search engine directives
└── sitemap.xml        # Site structure for search engines
```

## Features

- **Fully Responsive Design** - Works on desktop, tablet, and mobile
- **Single Page Application** - All content in one HTML file
- **No Dependencies** - Uses Google Fonts CDN only
- **Fast Loading** - Minimal file size, optimized CSS
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Smooth Scrolling** - Enhanced navigation experience
- **Professional Design** - Clean, trustworthy aesthetic

## Customization

All content and styling is contained within `index.html`. To customize:

1. **Colors**: Edit CSS variables in the `:root` section (lines 19-26)
2. **Content**: Update text in the HTML sections
3. **Contact Info**: Modify the contact section (lines 553-582)
4. **Practice Areas**: Edit the areas-grid section (lines 473-510)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact Information

**Anthony Smernes Jr., Esq.**
- **Phone**: (916) 786-1700
- **Email**: asmernes@realestatelawcorp.com
- **Address**: 1390 Lead Hill Boulevard, Roseville, CA 95661
- **California Bar**: #37265

## License

This website is for professional use by Anthony Smernes Jr., Esq.
