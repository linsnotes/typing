# 弹指之间 - Chinese Typing Exercise

A browser-based application for practicing Chinese typing with real-time feedback, pinyin support, and performance tracking.

## Features

- **Dual Input Modes**:
  - **Character Mode**: Type Chinese characters directly
  - **Pinyin Mode**: Type pinyin (without tones) to match characters

- **Exercise Data Import**:
  - Import from Google Sheets (publicly shared)
  - Upload Excel (.xlsx) files
  - Default sample sheet included for immediate practice

- **Interactive UI**:
  - Real-time feedback on typing accuracy
  - Pinyin display above characters
  - Progress bar and exercise navigation
  - Skip characters with spacebar
  - Backspace to correct previous input
  - Dynamic scrollbar for text navigation

- **Performance Tracking**:
  - Characters per minute (current and average)
  - Accuracy percentage
  - Detailed results with performance grade (A+ to E)
  - Time tracking

- **Additional Features**:
  - Dark/Light mode toggle
  - Mobile-responsive design
  - Screenshot and share results
  - Copy results as text
  - Visitor counter

## How It Works

1. **Import Data**:
   - Use the default Google Sheet URL or paste your own
   - Or upload an Excel file with two columns: Title and Chinese text

2. **Practice Typing**:
   - Select an exercise from the dropdown
   - Type the characters as they appear (or their pinyin in Pinyin Mode)
   - Get instant feedback on correct/incorrect inputs
   - Use spacebar to skip difficult characters
   - Use backspace to correct previous inputs

3. **Review Performance**:
   - After completing an exercise, view detailed statistics
   - See your typing speed, accuracy, and grade
   - Save a screenshot or copy results to share

## Sheet Format

For Google Sheets or Excel files, use the following format:
- First column: Exercise title
- Second column: Chinese text
- First row can optionally be headers ("Title" and "Text")

## Keyboard Shortcuts

- **Space**: Skip current character
- **Backspace**: Go back to previous character

## Browser Compatibility

Tested and works on:
- Chrome
- Firefox
- Safari
- Edge

## Mobile Support

The application is fully responsive with special optimizations for mobile devices:
- Adjusted layout for smaller screens
- Touch-friendly scrollbar
- Input field positioning to accommodate mobile keyboards

## Development

This application uses:
- **pinyin-pro**: For Chinese pinyin conversion
- **XLSX**: For Excel file parsing
- **html2canvas**: For screenshot functionality
- Pure vanilla JavaScript (no framework dependencies)

## License

This project is licensed under the [MIT License](LICENSE).
