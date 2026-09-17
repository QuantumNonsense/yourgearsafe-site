# yourgearsafe.com

Static marketing site for GearSafe. No build step, no JavaScript, no third-party requests.

- `index.html`: landing page
- `privacy/index.html`: privacy commitments
- `assets/styles.css`: styles; tokens mirror the `Gear Safe` Figma file (Design System v2, Prototype 2.0),
  as implemented in the app at `src/constants/gear-vault-theme.ts`
- `assets/fonts/`: self-hosted Inter (SIL Open Font License, see `OFL-LICENSE.txt`)
- `assets/mark.svg`: interim brand mark; replace with the official mark from the Figma "Brand Icons" page

Local preview:

```bash
python3 -m http.server 8787 --directory .
```
