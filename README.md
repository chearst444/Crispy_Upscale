Pixel Sprite Upscaler
A lightweight, browser-based utility designed for indie game developers to upscale pixel art sprites and tilemaps instantly without losing sharpness. Built to run entirely on the client side using HTML5 Canvas and JavaScript, deployable directly via GitHub Pages.
Core Features
 Integer Scaling: Locks multipliers to clean whole numbers (2x, 3x, 4x, 5x) using nearest neighbor interpolation to keep pixel art razor sharp.
 Transparent Alpha Preservation: Protects alpha channels so backgrounds remain cleanly transparent without edge halos.
 Bounding Box Normalization: Automatically trims excess transparent boundary pixels to standardize individual sprite frame dimensions.
 Edge Bleed Protection: Adds optional padding options to eliminate tilemap seam lines and rendering artifacts in engines like Construct 3 and RPG Maker.
 Batch File Processing: Drop multiple images at once to scale and download them sequentially.
How to Use
1. Drag and drop your sprite image files into the upload box or click to select files from your computer.
2. Choose your desired scale factor and toggle any optional settings like bounding box trimming or edge bleed.
3. Click the process button to automatically upscale and download your batch of sprites.
Local Development
Clone the repository and open ⁠index.html⁠ directly in any modern web browser. No local server, build steps, or installation dependencies required.
