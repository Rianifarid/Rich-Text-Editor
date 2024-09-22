# Online Text Editor

This project is an **Online Text Editor** built using HTML, CSS, and JavaScript. It includes formatting options for text styling, font choices, and more. The project uses FontAwesome icons to enhance the user interface with buttons for various formatting functionalities.

## Features
- **Text Formatting**: 
  - Bold text
  - Superscript and subscript
  - Ordered and unordered lists
  - Text alignment (left, center, right, justify)
  - Text indent and outdent
- **Undo/Redo** actions
- **Linking Options**: 
  - Create and remove hyperlinks
- **Font Options**: 
  - Change font family, size, font color, and background color (highlight)
- **Custom HTML headings** (H1 to H6)

## Files
- `index.html`: The main HTML structure of the text editor.
- `styles.css`: Contains the styling for the text editor.
- `script.js`: JavaScript file that handles text formatting and user interactions.

## Usage
1. Clone or download the repository.
2. Open the `index.html` file in your web browser.
3. Use the buttons in the toolbar to format your text in the editable area.

## Libraries and Dependencies
- **FontAwesome**: Used for the icons in the toolbar.
  - Link: [FontAwesome CDN](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css)

## How it Works
- The text area is a `contenteditable` div, allowing the user to input and format text directly.
- JavaScript functions are tied to the buttons to apply different formatting commands such as bold, alignment, and lists using the `document.execCommand` API.
  
## Future Enhancements
- Add more text formatting options (like text underline, strikethrough, etc.).
- Save the content locally or export it as a text file.
- Improve mobile responsiveness.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
