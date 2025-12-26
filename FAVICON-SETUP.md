# Favicon Setup

## Installation Complete! ✅

The favicon has been successfully installed using [RealFaviconGenerator](https://realfavicongenerator.net/).

## Files Installed

All favicon files have been downloaded and placed in the project root:

- ✅ `favicon.svg` (73 KB) - Modern SVG favicon
- ✅ `favicon-96x96.png` (5 KB) - PNG favicon for browsers
- ✅ `favicon.ico` (15 KB) - Legacy ICO format
- ✅ `apple-touch-icon.png` (11 KB) - Apple touch icon (180x180)
- ✅ `web-app-manifest-192x192.png` (12 KB) - PWA icon
- ✅ `web-app-manifest-512x512.png` (47 KB) - PWA icon
- ✅ `site.webmanifest` (437 bytes) - Web app manifest

## HTML Markup Added

The following markup has been added to `_includes/head.html` and is now included on all pages:

```html
<link rel="icon" type="image/png" href="/favicon-96x96.png" sizes="96x96" />
<link rel="icon" type="image/svg+xml" href="/favicon.svg" />
<link rel="shortcut icon" href="/favicon.ico" />
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
<meta name="apple-mobile-web-app-title" content="Grey Nax" />
<link rel="manifest" href="/site.webmanifest" />
```

## Customizations Made

1. **Paths updated** - All paths use Jekyll's `relative_url` filter for GitHub Pages compatibility
2. **Manifest updated** - `site.webmanifest` updated with:
   - App name: "Onyx Portal"
   - Correct baseurl paths for GitHub Pages
   - Theme colors preserved

## Browser Support

The favicon setup now supports:

- ✅ Modern browsers (Chrome, Firefox, Safari, Edge) - SVG favicon
- ✅ Older browsers - PNG and ICO fallbacks
- ✅ iOS/Apple devices - Apple touch icon
- ✅ Progressive Web Apps - Web app manifest with icons
- ✅ Dark mode - Automatic adaptation via SVG

## Testing

To verify the favicon is working:

1. Visit http://localhost:4000 in your browser
2. Check the browser tab - you should see your favicon
3. Add to home screen on mobile - should use the apple-touch-icon
4. Check PWA manifest - should show proper icons

## Files Modified

- `_includes/head.html` - Added favicon markup
- `site.webmanifest` - Updated app name and icon paths

## Notes

- All favicon files are automatically copied to `_site/` during Jekyll build
- The favicon will work on both local development and GitHub Pages
- The web manifest enables PWA features if needed in the future

