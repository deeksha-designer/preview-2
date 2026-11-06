# AISIN ASK Homepage Preview 2

Responsive static homepage redesign using the supplied AISIN ASK brand, product material and approved homepage information architecture.

## Run

```powershell
python -m http.server 4174 --bind 127.0.0.1
```

Open `http://127.0.0.1:4174/` from this folder.

## Files

- `index.html` — semantic homepage structure
- `styles.css` — responsive AISIN visual system
- `script.js` — mobile navigation, accessible product explorer and form validation
- `DESIGN_DIRECTION.md` — visual direction, reference translation and UX rationale
- `assets/` — supplied and source-derived AISIN imagery and downloadable PDFs

This is a static preview. The form deliberately does not transmit data.

The hero uses a locally hosted automotive-manufacturing MP4 with a static poster and reduced-motion support. Editorial visuals are saved in `assets/`; the supplied official AISIN ASK logo is used unchanged. Local font assets are bundled in `assets/fonts/`.
