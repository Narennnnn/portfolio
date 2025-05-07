# Minimalist Portfolio Website

A clean, minimalist portfolio website inspired by [ritvik.io](https://ritvik.io/), with improved typography and spacing.

## Features

- Simple, text-focused design
- Minimalist aesthetic with subtle hover effects
- Mobile-responsive layout
- Modal for detailed "my story" content
- Project links to GitHub, demos, and live versions
- Clean typography with IBM Plex Mono font
- Dedicated sections for experience and achievements

## How to Use

1. Clone or download this template
2. Customize the content in `index.html` to match your information
3. Add your image file named "narendra.jpg" to the root directory
4. Customize the colors in `styles.css` if desired
5. Deploy to your preferred hosting service

## Customization Guide

### Updating Your Information

1. **Header**: Change "narendra" to your name
2. **Social links**: Update the links to your social profiles
3. **Intro section**: Change the description and current position
4. **Highlights**: Update the bullet points with your background
5. **Projects**: Update with your own projects and descriptions, including GitHub/demo links
6. **Experience**: Update with your work experience and company links
7. **Quick Facts**: Add accomplishments and achievements
8. **My Story Modal**: Edit the detailed biography to match your journey
9. **Image**: Replace "narendra.jpg" with your own image

### Changing Colors

The main colors are defined as CSS variables at the top of `styles.css`:

```css
:root {
    --bg-color: #f6f5f1;
    --text-color: #333;
    --link-color: #333;
    --link-hover-color: #0070f3;
    --modal-bg: rgba(0, 0, 0, 0.6);
    --modal-content-bg: #f6f5f1;
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 3rem;
}
```

Modify these values to change the color scheme and spacing.

### Adding Sections

To add new sections, follow this pattern:

```html
<section class="your-section-name">
    <h2>section title:</h2>
    <ul>
        <li><a href="#">link text</a> - description</li>
        <li>non-linked text</li>
    </ul>
</section>
```

## Deployment Options

- **GitHub Pages**: Free and easy, perfect for personal portfolios
- **Netlify**: Offers free hosting with automated deployments from GitHub
- **Vercel**: Great for frontend projects with simple deployment
- **Digital Ocean**: Affordable VPS options for more control

## Credits

- Design inspired by [ritvik.io](https://ritvik.io/)
- Font: IBM Plex Mono from Google Fonts # portfolio
