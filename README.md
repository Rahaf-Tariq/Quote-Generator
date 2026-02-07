# Mood Quote Generator

> A web application that delivers personalized inspirational quotes based on your current emotional state.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

Mood Quote Generator is a single-page web application that helps users find inspiration through curated quotes. Select your current mood from seven emotional states, and receive relevant quotes with beautiful, matching visual themes. Save your favorite quotes for later reference with built-in local storage.

## What This Project Does

The Mood Quote Generator provides:

- Seven mood categories: Happy, Sad, Motivated, Calm, Creative, Love, and Hopeful
- Curated quote collections tailored to each emotional state
- Dynamic background gradients that adapt to selected moods
- Persistent favorites storage using browser local storage
- Fully responsive design for mobile and desktop
- Zero dependencies - runs entirely in the browser

## Installation

### Basic Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Rahaf-Tariq/mood-quote-generator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd mood-quote-generator
   ```

3. Open `index.html` in your web browser:
   ```bash
   open index.html
   ```

No build process or dependencies required. The application runs entirely client-side.

### Using a Local Server

For development or testing purposes, you can serve the application using:

**Python 3:**
```bash
python -m http.server 8000
```

**Node.js:**
```bash
npx http-server -p 8000
```

Then navigate to `http://localhost:8000` in your browser.

## Example Usage

### Basic Workflow

1. **Select Your Mood**: Choose from seven mood options on the main screen
2. **View Quote**: A relevant quote appears with a themed background
3. **Get New Quote**: Click "New Quote" for more quotes in the same mood
4. **Save Favorites**: Click "Save Quote" to store meaningful quotes
5. **Manage Favorites**: View and remove saved quotes from the sidebar
6. **Change Mood**: Click "Back" to select a different mood

### Code Example

The quote data structure:

```javascript
const quotes = {
  happy: [
    {
      text: "Happiness is not something ready made. It comes from your own actions.",
      author: "Dalai Lama"
    }
  ]
};
```

Adding new quotes:

```javascript
quotes.motivated.push({
  text: "Your new motivational quote here",
  author: "Author Name"
});
```

## Setting Up the Development Environment

### Prerequisites

- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, or Edge 90+)
- Text editor or IDE (VS Code, Sublime Text, etc.)
- Git for version control

### Development Setup

1. Fork and clone the repository:
   ```bash
   git clone https://github.com/yourusername/mood-quote-generator.git
   cd mood-quote-generator
   ```

2. Open the project in your preferred editor:
   ```bash
   code .
   ```

3. Start a local development server (optional but recommended):
   ```bash
   python -m http.server 8000
   ```

4. Make your changes to the HTML, CSS, or JavaScript

5. Test in multiple browsers to ensure compatibility

### Project Structure

```
mood-quote-generator/
├── index.html          # Main application file
└── README.md           # Documentation
```

The entire application is contained in a single HTML file with embedded CSS and JavaScript.

## How to Ship a Change

### Contributing Guidelines

1. **Fork the Repository**: Create your own fork on GitHub

2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**: 
   - Follow existing code style and conventions
   - Maintain single-file architecture
   - Test across multiple browsers
   - Ensure responsive design is maintained

4. **Commit Your Changes**:
   ```bash
   git add .
   git commit -m "Add: Brief description of your changes"
   ```

5. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Submit a Pull Request**:
   - Provide a clear description of changes
   - Reference any related issues
   - Include screenshots for UI changes

### Code Style Guidelines

- Use consistent indentation (2 spaces)
- Follow existing naming conventions
- Comment complex logic
- Maintain separation between HTML, CSS, and JavaScript sections
- Ensure accessibility standards are met

### Adding New Quotes

When contributing quotes:
- Verify accuracy and proper attribution
- Ensure quotes align with the mood category
- Keep quotes concise and impactful
- Add 6 quotes minimum per new mood category

## Change Log

### Version 1.0.0 (Current)

**Features:**
- Seven mood categories with curated quotes
- Dynamic background themes
- Local storage for favorite quotes
- Responsive mobile and desktop layouts
- Smooth animations and transitions

**Known Limitations:**
- Favorites do not sync across browsers or devices
- No search or filter functionality
- Limited to 6 quotes per mood category
- No export functionality for saved favorites

### Planned Features

**Version 1.1.0:**
- Expanded quote database (20+ quotes per category)
- Dark mode toggle
- Quote sharing functionality

**Version 2.0.0:**
- User authentication and cloud sync
- Custom mood creation
- Quote submission system
- Advanced search and filtering

## License and Author Info

### License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software for personal or commercial purposes.


### Author

**[Your Name]**
- GitHub: [@Rahaf-Tariq](https://github.com/Rahaf-Tariq)
- Email: rahafkhan510@gmail.com

### Acknowledgments

- Quote collections sourced from public domain and properly attributed authors
- Font families provided by Google Fonts (Poppins, Playfair Display)
- Gradient color schemes inspired by modern UI design trends

### Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

### Support

If you found this project helpful, please consider giving it a star on GitHub.
