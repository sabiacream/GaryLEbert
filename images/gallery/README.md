# Gallery before / after images

Add **paired** photos (same job, before and after). Recommended: **WebP** or **JPEG**, **long edge ~1600px**, compressed for web (~150–400 KB each).

## Suggested filenames (match `index.html` when you insert `<img>` tags)

| Card (section order) | Before | After |
|----------------------|--------|-------|
| Living rooms & foyers | `living-foyer-before.webp` | `living-foyer-after.webp` |
| Whole-home refresh | `whole-home-before.webp` | `whole-home-after.webp` |
| Offices & suites | `office-before.webp` | `office-after.webp` |
| Decorative / faux | `decorative-before.webp` | `decorative-after.webp` |
| Cabinet refinishing | `cabinets-before.webp` | `cabinets-after.webp` |
| Churches / institutional | `institutional-before.webp` | `institutional-after.webp` |

Paths in HTML: `images/gallery/your-file.webp`

## Performance

- Use `loading="lazy"` and `decoding="async"` on gallery images (hero stays `loading="eager"`).
- Keep aspect ratio similar to the frame (wide rectangle) so `object-fit: cover` crops predictably.
