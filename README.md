🌟 Highlights & Philosophy
100% Client-Side: All image processing algorithms run locally on the client's CPU via direct pixel-buffer manipulation (ImageData).
Zero Dependencies: No React, Vue, jQuery, Tailwind, Bootstrap, FontAwesome, or external CDNs.
Privacy & Offline First: Your images are never transmitted over the internet or uploaded to any server. Open the HTML file anywhere—even with no internet connection.
Desktop-Inspired UI: Features standard workspace layouts including multi-document tabs, toolbars, options bars, layer stacks, adjustment sliders, and history states.
🚀 Features
1. File Management & Multi-Document Tabs
Drag & Drop: Drop any image onto the workspace to open it instantly.
File Dialog: Open files via File > Open Image... or upload multiple images at once.
Multiple Tabs: Edit multiple images concurrently using the tab bar.
Supported Formats: PNG, JPEG/JPG, WebP, BMP, and SVG.
Non-Destructive Originals: The pristine version of each uploaded image is cached in memory for comparison and resetting.
2. Workspace & Navigation
Infinite Canvas & Viewport: Smooth panning and zooming from 10% up to 500%.
Mouse & Trackpad Support: Smooth scroll-wheel zoom centered on cursor.
Pan Tool (H or Spacebar): Click and drag to pan across large canvases.
Checkerboard Background: Clear visual representation of transparency and alpha channels.
Dark & Light Mode: Toggle themes anytime via the File menu.
3. Professional Adjustment Engine (ImageData API)
PixelCraft processes pixel buffers directly with mathematically accurate algorithms:

Lighting: Brightness, Contrast, Exposure (EV stops), Highlights, Shadows, and Gamma correction (
γ
 curve).
Color Balance: Saturation, Vibrance, Color Temperature (Warm/Cool), Tint, Hue Rotation (
0
∘
–
360
∘
), and individual RGB channel mixers.
Detail & Quality:
Sharpness: Authentic 
3
×
3
 Laplacian kernel convolution matrix.
Effects: Vignette radial gradient, synthetic film grain generator, pixelation downsampling, posterization quantization, and color inversion.
Bake Adjustments: Commit non-destructive real-time adjustments directly into the active layer pixel data.
4. 15 Algorithmic Filter Presets
One-click presets with an adjustable Intensity Slider (0–100%) and live canvas-rendered thumbnails:

Original
Grayscale
Sepia
Vintage
Black & White
Warm
Cool
Cinematic (Teal & Orange)
Dramatic
Faded
High Contrast
Soft Portrait
Retro
Monochrome
Vivid
