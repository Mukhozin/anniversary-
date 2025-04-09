# Anniversary Website

This is a static version of our anniversary celebration website. It's designed to be easily hosted on GitHub Pages or any web hosting service.

## How to Use

1. **Prepare Your Files**: 
   - Make sure you have the `static-export` folder and the `uploads` folder with all your images.
   - The `uploads` folder should be placed at the same level as the `static-export` folder.

2. **Image Handling Options**:
   - **Option A**: Run the included `prepare-images.js` script with Node.js to either embed all images as base64 (self-contained single file) or update paths for GitHub Pages.
   - **Option B**: Manually ensure the `uploads` folder is in the right location on your hosting.

3. **Audio Files**:
   - The music player supports audio playback via URLs. Make sure your audio files are hosted somewhere accessible.
   - Audio URLs can be from your own hosting or from services like SoundCloud, Google Drive (with sharing enabled), etc.

4. **Push to GitHub**: 
   - Upload these files to your GitHub repository.
   - For GitHub Pages, use the index.html.github.html file (rename it to index.html).

5. **Enable GitHub Pages**: 
   - In your repository settings, enable GitHub Pages from the main branch.

## Features

- Responsive design that works on mobile and desktop
- Countdown timer to your next anniversary
- Timeline of important relationship events
- Photo gallery with 3:4 aspect ratio images
- Memories section with detailed descriptions
- Love letters display
- Music playlist with audio playback

## Customizing

Feel free to customize the colors, fonts, and layout by editing the CSS in the `<style>` section of the HTML file.

## About Audio Playback

The music section has been enhanced to support actual audio playback:
- Add audio URLs in the admin interface when running the full application
- The static version will play audio from the URLs you've provided
- The player includes play/pause, skip forward/backward, and time tracking
- For the best experience, host your audio files on a reliable service

## Credits

Created with love for our special anniversary.