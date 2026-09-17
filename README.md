# yourgearsafe.com

Static marketing site for GearSafe. No build step, no JavaScript, no third-party requests.

- `index.html`: landing page
- `privacy/index.html`: privacy commitments
- `assets/styles.css`: styles; tokens mirror the `Gear Safe` Figma file (Design System v2, Prototype 2.0),
  as implemented in the app at `src/constants/gear-vault-theme.ts`
- `assets/fonts/`: self-hosted Inter (SIL Open Font License, see `OFL-LICENSE.txt`)
- `assets/brand-mark.png`, `favicon.png`, `apple-touch-icon.png`: the approved brand mark
  ("Brand Icon / Music Gear + Vinyl", Figma `Gear Safe` › Brand Icons), taken from the app's
  transparent `android-icon-foreground.png` and cropped to the artwork
- Wordmark type follows the Figma "GearSafe Logo Text" spec: Inter 800, #FFF, #040507 stroke

Local preview:

```bash
python3 -m http.server 8787 --directory .
```
