TUFT & CREATE — MULTILINGUAL INTERACTIVE WEBSITE

Files:
- index.html — semantic page content and dialogs
- style.css — responsive layout and visual styling
- app.js — French, English and Arabic translations, shop interactions and editable products
- assets/original-ui.png — supplied visual reference
- assets/ui-parts/ — cropped illustration-only pieces from the reference, used as image assets without embedded interface text

LANGUAGES
Use the language control in the header to switch French → English → Arabic. All visible page copy, navigation, categories, dialogs and shop controls are rendered as real HTML text, so translated content does not cover baked-in copy. Arabic switches the document to right-to-left direction.

PRODUCT PHOTOS
Create assets/products/ in the repository and upload files named:
- tufting-gun.jpg
- trimmer.jpg
- yarn.jpg
- poster.jpg
- custom-design.jpg
If a photo is missing, a simple placeholder illustration appears. Update product names, descriptions and prices in the PRODUCTS array near the top of app.js.

WHATSAPP
At the top of app.js, replace WHATSAPP_NUMBER = "212600000000" with your own international phone number digits only, without +, spaces or dashes.

GITHUB PAGES UPLOAD
1. Keep a backup of your current files.
2. Upload index.html, style.css, app.js and README.txt to the repository root (same folder as the existing index.html), and commit.
3. Upload the complete assets/ui-parts/ folder, preserving its path; the page uses these clean illustration crops.
4. Create assets/products/ and upload product images when ready. GitHub web upload cannot upload an empty folder, so upload image files directly into that folder or use Add file > Create new file with products/.gitkeep first.
5. Pages settings should publish main / (root), if that is where index.html lives.
6. Wait for Actions to finish, then hard refresh the website.

No build tools or server are required; this is a static GitHub Pages site.
