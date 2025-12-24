# Python IDE - Progressive Web App

## Installation Instructions

### For iPhone/iPad (iOS):

1. Open Safari browser (must use Safari, not Chrome)
2. Navigate to where you've hosted these files (or open index.html)
3. Tap the Share button (square with arrow pointing up)
4. Scroll down and tap "Add to Home Screen"
5. Name it "Python IDE" and tap "Add"
6. The app icon will appear on your home screen!

### For Android:

1. Open Chrome browser
2. Navigate to where you've hosted these files (or open index.html)
3. Tap the three-dot menu (⋮) in the top right
4. Tap "Install app" or "Add to Home screen"
5. Confirm by tapping "Install"
6. The app icon will appear on your home screen!

### Desktop (Chrome, Edge, etc.):

1. Open the browser and navigate to the hosted files
2. Look for the install icon (+) in the address bar
3. Click it and select "Install"
4. The app will open in its own window!

## Features:

✅ Works offline for code editing
✅ Auto-saves your code to device storage
✅ Real-time error detection and debugging
✅ Line-by-line error highlighting
✅ Mobile-optimized interface
✅ Tap errors to jump to problem lines
✅ Download your code as .py files

## Hosting Options:

To use this PWA, you need to host these files. Options:

1. **GitHub Pages** (Free & Easy):
   - Create a GitHub repository
   - Upload all files
   - Enable GitHub Pages in settings
   - Access via: `https://yourusername.github.io/repo-name`

2. **Netlify Drop** (Free):
   - Go to app.netlify.com/drop
   - Drag the entire folder
   - Get instant URL

3. **Vercel** (Free):
   - Install Vercel CLI: `npm i -g vercel`
   - Run: `vercel` in the folder
   - Get deployment URL

4. **Local Testing**:
   - Use Python: `python3 -m http.server 8000`
   - Open: `http://localhost:8000`

## Files Included:

- `index.html` - Main app file
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline support
- `icon-192.png` - App icon (small)
- `icon-512.png` - App icon (large)
- `README.md` - This file

## Notes:

- The app needs internet to execute Python code (uses Claude AI)
- Code editing works fully offline
- Your code is saved locally on your device
- Clear browser data will erase saved code

Enjoy your Python IDE!
