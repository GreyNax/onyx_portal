# Long Haul Theme Setup

## What Was Done

The Long Haul Jekyll theme has been successfully applied to the Onyx Portal project.

### Files Added/Modified

1. **Theme Files Copied:**
   - `_includes/` - Header, footer, navigation, and other partials
   - `_layouts/` - Default and post layouts
   - `_sass/` - SASS stylesheets for the theme
   - `assets/` - CSS, JavaScript, and other static assets

2. **Layouts Created:**
   - `_layouts/page.html` - Custom page layout for static pages

3. **Configuration Updated:**
   - `_config.yml` - Updated with Long Haul theme settings
   - `Gemfile` - Added `jekyll-paginate` plugin

4. **New Pages Created:**
   - `index.html` - Home page with paginated blog posts
   - `blog.md` - Archive page listing all blog posts
   - `research/index.md` - Index page for research collection
   - `decisions/index.md` - Index page for decisions collection

5. **Backup:**
   - `index-old.md` - Original index.md file (can be deleted)

### Configuration Changes

The `_config.yml` now includes:
- Long Haul theme settings
- Pagination (5 posts per page)
- Navigation menu with links to Home, About, Research, Decisions, and Blog
- Social media links (GitHub and email)
- SASS compression settings

### Navigation Structure

- **Home** (`/`) - Shows recent posts with pagination
- **About** (`/about`) - Project information
- **Research** (`/research`) - Research documentation
- **Decisions** (`/decisions`) - Design decisions
- **Blog** (`/blog`) - All blog posts archive

### Running the Site

**Local Development:**
```bash
bundle exec jekyll serve --baseurl ""
```

Then visit: http://localhost:4000

**Build for Production:**
```bash
bundle exec jekyll build
```

### Theme Features

The Long Haul theme provides:
- Minimal, type-focused design
- Responsive navigation menu
- Dark mode support (via prefers-color-scheme)
- Pagination for blog posts
- Clean typography
- Mobile-friendly layout

### Next Steps

1. **Customize the theme:**
   - Update social media links in `_config.yml`
   - Add Google Analytics ID if desired
   - Enable Disqus comments if desired
   - Adjust colors in `_sass/_config.scss`

2. **Content:**
   - Add more blog posts to `_posts/`
   - Update the About page with your information
   - Add more research documents to `_research/`

3. **Optional:**
   - Delete `index-old.md` if you don't need it
   - Customize the header size by uncommenting `header: large` in `_config.yml`

### Attribution

The Long Haul theme is properly attributed in:
- **Footer:** "Powered by Jekyll with Long Haul theme" (links to theme repo)
- **ATTRIBUTION.md:** Full attribution and license information

All copyright notices and template-specific references have been removed while maintaining proper credit to the theme author, Brian Maier Jr.

### Troubleshooting

If you see SASS deprecation warnings, they're harmless and can be ignored. They're from the theme's SASS files and don't affect functionality.

If port 4000 is already in use:
```bash
lsof -ti:4000 | xargs kill -9
```

Then restart the Jekyll server.

