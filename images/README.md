# Images Folder

This folder contains images for the BIC-MAC Challenge website.

## Structure

- **`hero-banner.jpg`** - The main hero background image (recommended size: 1920x1080 or larger)
- **`organizations/`** - Organization logo images
  - Add organization logos here (recommended: PNG with transparent background, ~200x200px)
  - Name them descriptively (e.g., `organization1.png`, `university-logo.png`, etc.)

## Usage

### Hero Banner
To use your hero banner image, edit `index.html` around line 107:

Replace:
```html
<div class="absolute inset-0 bg-gradient-to-br from-blue-100 via-purple-100 to-pink-100">
```

With:
```html
<div class="absolute inset-0">
    <img src="images/hero-banner.jpg" alt="Hero background" class="w-full h-full object-cover">
</div>
```

### Organization Logos
To use organization logos, edit `index.html` around lines 154-173.

Replace the SVG placeholders with:
```html
<div class="bg-white/70 backdrop-blur-sm rounded-xl p-4 flex items-center justify-center w-32 h-32 shadow-sm">
    <img src="images/organizations/org1.png" alt="Organization 1" class="max-w-full max-h-full">
</div>
```

## Image Recommendations

- **Hero Banner**: High-quality, wide image (1920x1080 or higher). Medical imaging, research lab, or abstract scientific visuals work well.
- **Organization Logos**: Square or rectangular logos, PNG format with transparent background preferred.
- Optimize images for web (compress without losing quality) to ensure fast page loading.
