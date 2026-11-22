# film-camera

A 35mm-film-style camera for the phone, built as a single web page and wrapped in Hermit.

- Live 3:2 viewfinder at the top of the phone (left or right side when turned sideways); taking a photo plays a shutter sound and blacks out the viewfinder. No preview, no gallery.
- Camera-body controls on black tolex: a chrome shutter release and a knurled film dial (spin or tap to change film).
- The film look is shown live in the viewfinder and applied to the saved photo by the same WebGL shader.
- Fujifilm-inspired film looks: Classic Neg, Classic Chrome, Nostalgic Neg, Provia, Velvia, Astia, Eterna, Acros.
- Subtle grain, halation, vignette, occasional scratches and dust.
- Photos are saved as JPEGs to the device's Downloads folder.

Host `index.html` anywhere with HTTPS (camera access requires it) and open it as a Hermit Lite App.
