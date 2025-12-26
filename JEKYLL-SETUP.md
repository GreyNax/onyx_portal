# Jekyll Site Setup

This directory is a Jekyll site that can be hosted on GitHub Pages.

## Local Development

### Install Dependencies
```bash
bundle install
```

### Run Local Server
```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

### Live Reload (auto-refresh on changes)
```bash
bundle exec jekyll serve --livereload
```

## Deployment to GitHub Pages

### Option 1: GitHub Pages (Automatic)

1. **Update `_config.yml`:**
   - Set `url` to your GitHub Pages URL
   - Set `baseurl` to your repo name (if not root)

2. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial Jekyll site"
   git push origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo Settings → Pages
   - Source: Deploy from branch
   - Branch: `main` (or `gh-pages`)
   - Folder: `/ (root)`
   - Save

Site will be live at `https://GreyNax.github.io/onyx_portal/`

### Option 2: Custom Domain

1. Add `CNAME` file with your domain:
   ```
   onyxportal.org
   ```

2. Configure DNS:
   - Add A records pointing to GitHub Pages IPs
   - Or CNAME record pointing to `GreyNax.github.io`

3. Enable HTTPS in GitHub Pages settings

## File Structure

```
/
├── _config.yml           # Jekyll configuration
├── index.md             # Homepage
├── about.md             # About page
├── _posts/              # Blog posts (YYYY-MM-DD-title.md)
├── _research/           # Research documents (collection)
├── _decisions/          # Decision logs (collection)
├── _layouts/            # Custom layouts (optional)
├── white-paper/         # White paper sections (static pages)
├── research/            # Original research files (for reference)
├── decisions/           # Original decision files (for reference)
└── scale-model/         # 3D model files
```

## Writing Content

### Blog Posts
Create files in `_posts/` with format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Your Title"
date: 2024-12-25
categories: [category1, category2]
tags: [tag1, tag2]
---

Your content here...
```

### Research Pages
Create files in `_research/` with frontmatter:

```markdown
---
title: "Page Title"
layout: page
permalink: /research/page-name/
---

Content...
```

### Decision Logs
Create files in `_decisions/` with date in frontmatter:

```markdown
---
title: "Decision Title"
date: 2024-12-25
layout: page
permalink: /decisions/YYYY-MM-DD-title/
---

Content...
```

## Customization

### Change Theme
Edit `_config.yml`:
```yaml
theme: minima
# or
remote_theme: pages-themes/minimal@v0.2.0
```

Popular themes:
- `minima` (default, clean)
- `minimal` (very minimal)
- `cayman` (nice headers)
- `architect` (technical look)

### Custom CSS
Create `assets/css/style.scss`:
```scss
---
---

@import "minima";

// Your custom styles
```

### Custom Layouts
Create layouts in `_layouts/`:
- `default.html` - base layout
- `post.html` - blog post layout
- `page.html` - static page layout

## Maintenance

### Update Posts
Just edit the markdown file in `_posts/` and commit.

### Add Research
Create new file in `_research/` and commit.

### Update Technical Questions
Edit `_research/technical-questions.md` directly.

## Tips

### Images
Store images in `/assets/images/` and reference:
```markdown
![Alt text](/assets/images/photo.jpg)
```

### Internal Links
```markdown
[Link text](/about/)
[Blog post](/blog/2024/12/25/title/)
[Research page](/research/technical-questions/)
```

### Code Blocks
```markdown
```python
# Your code here
```
```

### Math (if needed)
Enable MathJax in `_config.yml` or use KaTeX plugin.

## Troubleshooting

**Site not updating?**
- Clear cache: `bundle exec jekyll clean`
- Rebuild: `bundle exec jekyll build`
- Check GitHub Actions tab for build errors

**Theme not working?**
- Ensure theme is in Gemfile
- Run `bundle install`
- Check GitHub Pages supports the theme

**Links broken?**
- Check `baseurl` in `_config.yml`
- Use `{{ site.baseurl }}` prefix if needed

---

**Ready to publish!** Just push to GitHub and enable Pages in settings.
