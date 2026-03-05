# Images & Assets

- Use `https://placehold.co/` for placeholder images during development.
- Placeholder format: `https://placehold.co/WIDTHxHEIGHT/BGCOLOR/TEXTCOLOR?text=TEXT`.
- Always specify image dimensions to prevent layout shift.
- Use `object-cover` for images that need to fill a container without distortion.
- Use `object-contain` when the full image must be visible.
- Use SVG for icons — inline SVGs are preferred for styling flexibility.
- For icon sets, use Heroicons (MIT license): https://heroicons.com/
- Optimize images before production: compress PNGs, use WebP where supported.
- Use `aspect-ratio` or padding-bottom trick for responsive image containers.
