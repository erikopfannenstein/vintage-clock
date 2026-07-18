# Vintage Clock

**Bring your favorite antique clock back to life.**

Turn your tablet, monitor, or computer into a beautiful vintage clock with authentic clock faces and customizable chimes.

Vintage Clock is a free, open-source web application that recreates the look and sound of antique clocks. Upload your own clock face, choose a hand style, customize colors and sizes, and enjoy realistic chimes directly in your browser.

## Features

### Clock Faces

- Upload your own clock face image
- 13 built-in vintage clock faces
- Drag, zoom, and reposition the dial
- Full-screen display
- Touch support

### Clock Hands

- Multiple SVG hand styles
- Adjustable hand size
- Custom hand colors
- Optional second hand
- Adjustable center cap color
- Adjustable center cap size

### Chimes

- Westminster chimes
- Grandfather clock strikes
- Temple bell chimes
- Cuckoo sounds
- Custom chime upload
- Preview and Stop controls
- Strike patterns:
  - Once
  - Twice
  - Four Times
  - Current Hour
- Adjustable strike spacing
- Adjustable sound tail for individual strikes
- Quiet Hours

Westminster recordings play once and continue to the end without being repeated or cut short.

### Display Options

- Hide controls
- Hide branding
- Responsive layout
- Works on desktop, tablet, and mobile browsers

## Built-in Clock Faces

- Default Roman
- Classic Cream
- Aged Brass
- Dark Victorian
- Railway Station
- Art Deco
- Tiffany
- French Enamel
- Black Forest
- Skeleton Clock
- Steampunk
- Pocket Watch
- Vienna Regulator

## Use Online

Open Vintage Clock in your browser:

https://erikopfannenstein.github.io/vintage-clock/

No installation is required.

## Local Installation

1. Download or clone this repository.

```bash
git clone https://github.com/erikopfannenstein/vintage-clock.git
```

2. Open `index.html` in a modern web browser.

## Project Structure

```text
vintage-clock/
├── index.html
├── README.md
├── faces/
│   ├── classic-cream.png
│   ├── aged-brass.png
│   ├── dark-victorian.png
│   ├── railway-station.png
│   ├── art-deco.png
│   ├── tiffany.png
│   ├── french-enamel.png
│   ├── black-forest.png
│   ├── skeleton-clock.png
│   ├── steampunk.png
│   ├── pocket-watch.png
│   └── vienna-regulator.png
└── chimes/
    ├── cuckoo01.mp3
    ├── cuckoo02.mp3
    ├── grandfather01.mp3
    ├── grandfather02.mp3
    ├── grandfather03.mp3
    ├── temple01.mp3
    ├── temple02.mp3
    ├── temple03.mp3
    ├── temple04.mp3
    ├── westminster01.mp3
    ├── westminster02.mp3
    ├── westminster03.mp3
    └── westminster04.mp3
```

## Custom Clock Faces

You can upload your own clock face image from the control panel.

For best results:

- Use a square image
- Use a high-resolution image, preferably 1500 × 1500 pixels or larger
- Center the dial in the image
- Leave enough space around the numerals for the clock hands

The uploaded image can be moved and resized inside the clock.

## Custom Chimes

You can upload your own chime recording and use it with the same strike controls as the built-in sounds.

Supported browser-compatible audio formats may include:

- MP3
- WAV
- OGG

Custom recordings must be no longer than 15 seconds.

## Browser Compatibility

Vintage Clock is designed for current versions of:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Apple Safari

Browser audio restrictions may require you to interact with the page before scheduled chimes can play.

## GitHub Pages

To publish your own copy:

1. Upload the project files to a GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Choose the `main` branch as the publishing source.
5. Save the settings.
6. Wait for GitHub Pages to finish publishing.

After updating files, refresh the published page. A hard refresh may be needed:

- Windows: `Ctrl + F5`
- Mac: `Command + Shift + R`

## License

This project is open source. Add the license file of your choice before distributing modified versions.

## About

Vintage Clock was created for people who want to preserve and enjoy the beauty of antique clocks using modern displays.

A tablet placed inside an old clock case can become a working dial again—complete with adjustable hands, authentic clock faces, and traditional chimes.
