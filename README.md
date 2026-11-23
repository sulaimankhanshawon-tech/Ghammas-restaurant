# Ghammas Grill & Oven - online menu

Static website (index.html + intro.mp4). No build step.

## Deploy on GitHub Pages
1. Create a new repository on github.com (Public).
2. Upload ALL files from this folder (index.html, intro.mp4, .nojekyll, README.md).
3. Settings > Pages > Source: Deploy from a branch > Branch: main, folder: / (root) > Save.
4. After about a minute the site is at https://USERNAME.github.io/REPOSITORY/
5. Create a new QR code that points to that address.

## Editing
Edit index.html on GitHub (pencil icon). Menu data is the JSON block `<script id="d">`.
WhatsApp numbers: `const PHONE` near the top of the main script.
