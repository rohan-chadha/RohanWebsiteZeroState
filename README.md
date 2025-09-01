# Rohan Website Zero State

A simple website based on a Figma design showing an "under construction" state.

## Features

- Responsive design using Tailwind CSS
- No scrolling - full height layout
- Top and bottom text anchored to their respective positions
- Centered image with descriptive text
- Uses the exact colors and typography from the Figma design

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Production

To run in production mode:
```bash
npm start
```

## Design Details

- **Top text**: "linkedin" (anchored to top)
- **Center**: Image with "under construction" text below
- **Bottom text**: "made with ❤️ by Rohan Chadha" (anchored to bottom)
- **Colors**: Uses the exact #888888 color from the design
- **Typography**: Roboto for regular text, Source Serif Pro for italic text
- **Layout**: Full height with no scrolling, responsive design

## Files

- `public/index.html` - Main HTML file with Tailwind CSS
- `server.js` - Node.js Express server
- `website-image.png` - The main image from the design
- `package.json` - Project dependencies and scripts
