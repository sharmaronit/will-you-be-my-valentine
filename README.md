# Will You Be My Valentine? 💕

An interactive hand gesture recognition Valentine's Day web application built with **Google MediaPipe Hands** and vanilla JavaScript.

## Features

✨ **Hand Gesture Detection**: Use hand gestures to unlock a romantic surprise
- Make a heart shape with both hands (bring thumbs and index fingers together)
- Counter shows real-time holding progress (0-100%)
- Celebrate with confetti animation when gesture completes

🎨 **Beautiful UI**
- Responsive design for desktop and mobile
- Pinkish gradient background with glassmorphism effects
- Smooth animations and floating hearts
- 6-image slideshow gallery with navigation

🎥 **Camera Integration**
- Real-time hand skeleton visualization
- Smooth 60fps animations
- Single camera permission request

## How to Use

1. **Allow Camera Access**: Grant permission for webcam access
2. **Make a Heart Shape**: Touch your thumbs and index fingers together on both hands (form a heart shape)
3. **Hold for 2 Seconds**: Keep the gesture steady until the counter reaches 100%
4. **See the Surprise**: View the celebration with floating hearts and cat gallery
5. **Close & Repeat**: Use the ✕ button to close and try again

## Technologies Used

- **Hand Detection**: Google MediaPipe Hands
- **Animation**: CSS3 Keyframes & Canvas Confetti
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Fonts**: Google Fonts (Pacifico, Fredoka One, Patrick Hand)

## Project Structure

```
Will You Be My Valentine/
├── index.html              # Desktop version
├── index.mobile.html       # Mobile-optimized version
├── cat images/            # Gallery images (6 cat photos)
└── README.md
```

## Desktop vs Mobile

- **Desktop Version**: Full-featured with larger images and text
- **Mobile Version**: Optimized dimensions and touch-friendly controls

## Customization

### Adjust Detection Sensitivity
Edit `DISTANCE_THRESHOLD` (default: 120px)

### Change Gesture Duration
Edit `HOLD_DURATION` (default: 2000ms)

### Modify Slideshow Speed
Edit slideshow interval (default: 1500ms)

### Replace Gallery Images
Replace cat images in `cat images/` folder

## Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari (iOS 14.5+)

## Credits

Made with ❤️ by [@sharmaronit](https://github.com/sharmaronit)

## License

MIT License - Feel free to use this project for your own Valentine's creation!

---

**Note**: This project requires a working webcam and internet connection for MediaPipe hand detection models.
