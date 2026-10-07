# GLP-1 Companion

A simple iPhone-style, local-first GLP-1 medication tracker designed for GitHub Pages.

## Run on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Open the published URL on iPhone and choose **Share → Add to Home Screen**.

## Included

- Medication-first workflow
- Zepbound, Mounjaro, Wegovy, Ozempic, Rybelsus, Saxenda, Victoza, Trulicity, semaglutide, tirzepatide, liraglutide, dulaglutide and custom medication
- Weight tracking and interactive SVG chart
- Medication history and injection-site tracking
- Check-ins for hunger, food noise, energy, sleep and side effects
- Food/nutrition area
- Supply tracking
- Local data storage
- JSON backup/export and import
- Offline PWA shell
- iPhone-style bottom navigation and sheets

## Important limitation

A GitHub Pages PWA cannot honestly provide native Face ID, HealthKit, background notification scheduling, or Keychain encryption. The UI includes the Face ID/app-lock concept, but true Face ID requires a native iOS build using Apple's LocalAuthentication and Keychain APIs.

This app is a tracking/education prototype, not medical advice and does not recommend medication doses.
