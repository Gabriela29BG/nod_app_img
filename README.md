Technologies Used:

Node.js:
Utilized Node.js for server-side JavaScript execution.
Libraries:
fs-extra: Employed for extended file system operations, making file handling more convenient.
sharp: Used for image processing, including resizing.
imagemin: Utilized for image optimization, integrating plugins for various formats (JPEG, PNG, SVG, WebP, GIF).
Image Optimization Process:

Resizing:

Implemented image resizing using the sharp library to ensure uniformity in width (1920 pixels).
Compression:

Applied compression techniques to different image formats:
JPEG compression with a quality of 80%.
PNG compression using imageminPngquant.
SVG compression using imageminSvgo.
WebP compression with a quality of 80%.
GIF compression with imageminGifsicle.
Error Handling:

Implemented error handling using try-catch blocks to gracefully handle any potential issues during the optimization process.
Logging and Feedback:

Integrated console logs to provide informative messages about the optimization progress, including the name of the optimized image.
Conclusion:
This development experience highlights proficiency in Node.js, image processing, and optimization techniques. The code demonstrates a systematic approach to handling image files, applying resizing and compression methods, and ensuring robust error handling. The inclusion of informative logs enhances the transparency of the optimization process.
