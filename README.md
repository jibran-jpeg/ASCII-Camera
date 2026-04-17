# Cyberpunk ASCII Art Camera

A real-time, browser-based ASCII Art Camera with a premium Cyberpunk/Hacker aesthetic. It uses your device's web camera, converts the live feed into stylized ASCII characters, and provides multiple rendering options and export tools.

## Features
- **Real-Time Rendering:** Converts video feed to ASCII text on the fly.
- **Glassmorphism UI:** Clean, modern, responsive left-sidebar layout.
- **Multiple Resolutions:** Choose from 80-column minimal up to 260-column ultra-dense text.
- **Custom Character Sets:** Detailed, Simple, or Block-based characters for different stylings.
- **Color Themes:** Switch between Neon Green, Minimal White, Retro Amber, or Aggressive Red.
- **Export Options:** 
  - Save as PNG
  - Save as TXT
  - Copy to Clipboard
- **Mobile Responsive:** Sidebar transforms into an overlay menu on smaller screens. 

## Run Locally
You can run this simply by serving the `index.html` file using a local web server (to allow camera permissions).

```bash
python3 -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.
