# Text Editor

A web-based text editor application built with HTML, CSS, and JavaScript, offering essential text modification features similar to popular applications like Word or OpenOffice.
</br>
</br>

<div align="center">
  <img src="https://github.com/flowdevloping/text-editor/blob/master/TextEditor.png" width="500">
</div>
</br>

## Features

- **Text Formatting**: Bold, italic, superscript, subscript, and various alignment options (left, center, right, justify).
- **List Management**: Ability to create numbered and bulleted lists.
- **Undo/Redo**: Easily undo and redo actions.
- **Link Creation**: Add or remove hyperlinks.
- **Indentation**: Indent and outdent text sections.
- **Custom Fonts and Sizes**: Choose from multiple fonts and font sizes.
- **Color Customization**: Select font color and highlight color with adjustable transparency.
- **Active State Indicators**: Highlights active options for intuitive user experience.

## Project Structure

```plaintext
.
├── index.html         # HTML file defining the structure of the text editor
├── style.css          # CSS file for styling the editor layout and components
└── script.js          # JavaScript file to manage text formatting and interactive functionalities
```
## Installation and Usage
1. Clone the Repository:

```bash
  git clone https://github.com/your-username/online-text-editor.git
  cd online-text-editor
```

2. Open in Browser: Open index.html in your browser to start using the text editor.

## Code Overview
- HTML: Sets up the editor's structure, including buttons and a content-editable text area.
- CSS: Defines the editor's dark-themed design and organizes components into a responsive, user-friendly layout.
- JavaScript:
  - Initializes available fonts and sizes.
  - Handles text modification commands using execCommand.
  - Enables color customization with adjustable alpha values.
  - Toggles active button states to visually indicate selected formatting options.

## Key Functions
```initializer()```

- Populates the font and size dropdowns, sets default values, and highlights active button states.

```modifyText(command, defaultUi, value)```
- Executes a text-editing command based on the clicked button or selected option.

```changeColor(init, alpha)```
- Applies the selected color and alpha transparency to text or background.

#### Helper Functions
  ```hexToRgb```
  - Converts hex color codes to RGB format.
    
  ```rgbToString```
  - Formats RGB values with alpha transparency for CSS use.
    
  ```highlighter```
  - Manages the active state of buttons for consistent user feedback.

## Dependencies
- Google Material Symbols
- Poppins Font

## License
This project is licensed under the MIT License.
