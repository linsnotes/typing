# Chinese Typing Exercise - 手疾眼快

**字随指落** is a browser-based Chinese typing exercise application. It provides users with an interactive platform to practice Chinese typing by importing text data from either a CSV file or a Google Sheets document. The application displays Chinese text along with its pinyin, supports dark mode, and includes a dynamic scrollbar for navigation.

## Features

- **Dual Data Import Options:**
  - **Google Sheets Integration:** Import directly from a publicly shared Google Sheets URL.
  - **CSV/Excel Upload:** Import exercise data from a CSV file (expects two columns: Title and Chinese text).

- **Interactive Typing Interface:**  
  - Displays Chinese characters with corresponding pinyin.
  - Real-time feedback on typing accuracy.
  - Option to skip characters using the space bar.
  - Dynamic scrollbar to navigate through the exercise content.

- **Dark Mode:**  
  - Toggle between light and dark themes for an optimized user experience.

- **Responsive Design:**  
  - Designed to work seamlessly on both desktop and mobile devices.

- **Visitor Counter:**  
  - Integrated visitor counter powered by GoatCounter to display the number of visitors.

## How It Works

1. **Importing Exercise Data:**
   - **CSV File:** Click the "Choose CSV File" button to upload a CSV file with your exercise data.
   - **Google Sheets:** Paste your Google Sheets URL into the provided input and click the "Import from Google Sheets" button. Ensure your sheet is public or shared with anyone who has the link.
   
2. **Starting the Exercise:**
   - Once data is imported, the application displays the exercise title and progress.
   - Chinese text is shown with pinyin above each character.
   - The current character to be typed is highlighted.
   
3. **Typing and Navigation:**
   - Type the Chinese characters into the input box. Correct entries are highlighted, and incorrect entries prompt feedback.
   - Use the space bar to skip a character if needed.
   - Utilize the scrollbar to quickly navigate through longer exercises.
   
4. **Exercise Completion:**
   - Upon finishing the exercise, you will receive feedback and options to restart the exercise or move on to the next one.

## Setup & Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/chinese-typing-exercise.git
   cd chinese-typing-exercise
   ```

2. **Open the Application:**
   - Simply open the `index.html` file in your preferred web browser.
   - Alternatively, you can host the file on a web server for public access.

3. **Dependencies:**
   - The application is self-contained and uses the [pinyin-pro](https://github.com/mozillazg/pinyin-pro) library via a CDN.
   - It also fetches visitor count data from GoatCounter.

## File Structure

```
chinese-typing-exercise/
├── index.html        # Main HTML file containing the structure, styles, and scripts.
├── README.md         # This README file.
└── (Optional assets) # Additional files (if any) for images, custom scripts, or styles.
```

## Customization & Development

- **Styling:**  
  The styles are embedded within the HTML file. Feel free to modify the CSS to better suit your branding or design preferences.

- **Functionality:**  
  The JavaScript code handles CSV parsing, Google Sheets data import, dynamic UI updates, and event listeners for user interactions. You can enhance or modify the functionality as needed.

- **Contributions:**  
  Contributions, improvements, and bug fixes are welcome. Please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
