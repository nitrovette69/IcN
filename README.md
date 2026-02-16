# SAR Image Viewer PWA

A Progressive Web App for viewing Synthetic Aperture Radar (SAR) satellite images with pan, zoom, and offline capabilities.

## Features

- 🖼️ **Image Viewer**: Load and display SAR satellite imagery
- 🔍 **Zoom Controls**: Zoom in/out with mouse wheel or buttons
- 🖱️ **Pan Mode**: Click and drag to navigate large images
- 📱 **PWA Ready**: Install as a native app on Linux, Android, and desktop
- 🔌 **Offline Support**: Service Worker caches assets for offline viewing
- 🎨 **Dark Theme**: Professional dark interface optimized for satellite imagery
- 🔒 **Private Repository**: Secure, private access via GitHub

## Quick Start

### Local Development with Python

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nitrovette69/IcN.git
   cd IcN
   ```

2. **Start a local server**:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

3. **Open in browser**:
   ``
   http://localhost:8000
   ```

4. **Install as PWA**:
   - Click the "📱 Install App" button or use your browser's install prompt

## Usage

1. **Load an Image**: Click the file input to select a SAR image
2. **Pan**: Click "🖱️ Pan" button, then click and drag
3. **Zoom**: Click buttons or use mouse wheel
4. **Reset**: Click "↺ Reset" to return to original view

## Private Repository Access

This repo is private. Use a GitHub Personal Access Token:

```bash
git clone https://<TOKEN>@github.com/nitrovette69/IcN.git
```

## Browser Support

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 15+
- ✅ Samsung Internet