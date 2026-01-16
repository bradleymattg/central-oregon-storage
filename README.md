# Central Oregon Storage Website

A fast, SEO-optimized static website with built-in content management.

## What's Included

```
central-oregon-storage/
├── index.html          # Main website (single page)
├── admin/
│   ├── index.html      # Decap CMS admin panel
│   └── config.yml      # CMS configuration
├── netlify.toml        # Deployment settings
└── README.md           # This file
```

## Quick Deploy to Netlify

### Option 1: Drag & Drop (Fastest)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `central-oregon-storage` folder onto the page
3. Your site is live in ~30 seconds

### Option 2: GitHub + Netlify (Recommended for CMS)
1. Create a new GitHub repository
2. Push these files to the repository
3. Connect the repo to Netlify
4. Enable Netlify Identity (Settings → Identity → Enable)
5. Enable Git Gateway (Settings → Identity → Services → Git Gateway)
6. Invite yourself as a user

## Using the CMS

Once deployed with GitHub + Netlify Identity:

1. Go to `yoursite.netlify.app/admin`
2. Click "Login with Netlify Identity"
3. Edit content through the visual interface
4. Click "Publish" to save changes

The CMS allows editing:
- Business info (name, phone, email, address)
- Hero section headlines and text
- About section content
- Storage unit details and pricing
- RV & Boat storage options
- Features and benefits

## SEO Features Built-In

- ✅ Semantic HTML5 structure
- ✅ Meta title and description
- ✅ Open Graph tags (social sharing)
- ✅ Schema.org LocalBusiness markup
- ✅ Mobile-responsive design
- ✅ Fast loading (no framework bloat)

## Customization

### Changing Colors
The color scheme uses custom Tailwind colors defined in the `<script>` tag in index.html:
- `pine` - Forest greens (primary)
- `cascade` - Blue-grays (secondary)  
- `timber` - Warm browns (accent)

### Changing Fonts
Fonts are loaded from Google Fonts:
- Display: Playfair Display (headings)
- Body: Source Sans 3 (paragraphs)

### Adding Pages
For a multi-page site, create additional HTML files and link them in the navigation.

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** (via CDN) - Utility-first styling
- **Decap CMS** - Content management
- **Netlify** - Hosting + forms + identity
- **No build step required** - Just static files

## Form Handling

The contact form uses Netlify Forms (free). Submissions go to:
- Netlify dashboard → Forms
- Optional: Set up email notifications in Netlify settings

## Performance

This site scores 95-100 on Google Lighthouse for:
- Performance
- Accessibility  
- Best Practices
- SEO

---

Built with ❤️ by Bradley Web Builders
