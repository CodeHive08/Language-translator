# Language Translator

A simple and elegant web-based language translator app built with HTML, CSS, and JavaScript. Instantly translate text between dozens of languages using the [MyMemory Translation API](https://mymemory.translated.net/).

## Features

- Translate text between 90+ languages
- Copy text to clipboard with one click
- Listen to the original and translated text using text-to-speech
- Swap source and target languages instantly
- Responsive and modern UI

## Demo

![Screenshot](screenshot.png)

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection (for translation API and text-to-speech)

### Running Locally
1. Clone or download this repository.
2. Open `index.html` in your web browser.

No build steps or dependencies required!

## How It Works
- The app uses the [MyMemory Translation API](https://mymemory.translated.net/) to fetch translations.
- Language options are populated from a local `countries.js` file.
- All logic is handled client-side in `script.js`.
- Text-to-speech and clipboard features use built-in browser APIs.

## File Structure

- `index.html` — Main HTML file
- `style.css` — App styling and responsive design
- `script.js` — App logic and API integration
- `countries.js` — List of supported languages

## Credits
- [MyMemory Translation API](https://mymemory.translated.net/)
- [Font Awesome](https://fontawesome.com/) for icons
- Google Fonts (Poppins)

## License

This project is open source and free to use for educational and personal projects. 