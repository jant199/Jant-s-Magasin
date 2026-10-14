TUFT & CREATE — ORIGINAL UI INTERACTIVE VERSION

Files:
- index.html
- style.css
- app.js
- assets/original-ui.png (your supplied original 1470 x 1070 UI image)

IMPORTANT VISUAL NOTE
The supplied image is kept as a single artwork layer. This is the most reliable way to preserve the original hand-drawn fabrics, flowers, tulips, cake, bunny, icons, stitching, colours and layout without duplicated overlays. Invisible click targets sit above the artwork; they do not draw duplicate icons.

LANGUAGE
Click the FR label in the top-right of the artwork to cycle FR -> EN -> AR. Because the original French words are baked into the picture, translated text is overlaid only over selected text regions in English/Arabic. This keeps the French/default view pixel-faithful, but translation overlays cannot be perfectly pixel-identical to the textured paper. True perfect translations require rebuilding the artwork with all text separated from the illustration.

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
2. Upload index.html, style.css and app.js to the repository root (same folder as the existing index.html), and commit.
3. Upload assets/original-ui.png to the assets folder, preserving that exact path and lowercase filename.
4. Create assets/products/ and upload product images when ready. GitHub web upload cannot upload an empty folder, so upload the image files directly into that folder or use Add file > Create new file with products/.gitkeep first.
5. Pages settings should publish main / (root), if that is where index.html lives.
6. Wait for Actions to finish, then hard refresh the website.

No build tools or server are required; this is a static GitHub Pages site.
