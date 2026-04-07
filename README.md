# Stellar

A real-time Discord status page that displays your online presence, custom status, and Spotify activity with a stunning animated space background and music player.

![Preview](https://imgur.com/phXdzyF)

## Features

-  **Multi-track music player** with shuffle functionality  
-  Animated shooting stars background  
-  Spotify integration with real-time progress bar  
-  Background music toggle with volume control  
-  Responsive design  
-  Real-time updates via Lanyard API  
-  Local storage caching for offline viewing  
-  Now playing display for background music   

## Technologies Used

- HTML5, CSS3, JavaScript  
- [Lanyard API](https://github.com/Phineas/lanyard) for Discord presence data  
- WebSocket for real-time updates  
- Font Awesome for icons  

## Setup

1. Clone the repository:  
   ```bash
   git clone https://github.com/exophs/Stellar.git
   ```

2. Join the Lanyard [Discord server](https://discord.gg/8NTS7FRFgu) to enable presence tracking.

3. Configure your Discord ID in `index.html`:  
   ```javascript
   const DISCORD_USER_ID = "YOUR_DISCORD_ID_HERE";
   ```

4. Customize the music playlist (lines 315-344 in `index.html`).

5. Deploy to any static hosting service (GitHub Pages, Vercel, Netlify, etc.).

## Customization
- Edit `playlist` array in JavaScript to change music tracks  
- Modify CSS variables in `style` tag for color schemes  
- Adjust animation parameters for stars in JavaScript  
