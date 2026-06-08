# Simple Calculator

A sleek, modern web-based calculator with a responsive design and full keyboard support.

## Features

### 🎨 Clean Dark Theme
Modern UI with a dark navy color palette and vibrant accents.

### ➕ Full Arithmetic Support
Supports:
- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`×`)
- Division (`÷`)

### 🔢 Decimal Precision
Handles floating-point calculations with smart rounding.

### ⌨️ Keyboard Support

Use your keyboard for quick calculations:

| Key | Action |
|------|---------|
| `0-9` | Number input |
| `+ - * /` | Arithmetic operators |
| `Enter` or `=` | Calculate result |
| `Escape` or `C` | Clear display |
| `Backspace` | Delete last character |

### ⚠️ Error Handling
- Gracefully handles division by zero
- Detects invalid expressions
- Prevents calculation crashes

### 📱 Responsive Design
Works seamlessly on:
- Desktop
- Tablet
- Mobile devices

---

## Usage

Simply open **`index.html`** in any modern web browser.

No installation, build process, or dependencies required.

---

## Button Layout

| C | ÷ | × | ⌫ |
|---|---|---|---|
| 7 | 8 | 9 | − |
| 4 | 5 | 6 | + |
| 1 | 2 | 3 | . |
| 0 |   | = |   |

---

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Grid layout, custom styling, animations, transitions
- **Vanilla JavaScript** — Pure JavaScript with no external libraries

---

## File Structure

```text
.
├── index.html      # Main application file (HTML + CSS + JS)
└── README.md       # Project documentation
```

> **Note:** This is a single-file application. All styles and scripts are embedded directly within the HTML file for simplicity and portability.

---

## How It Works

The calculator evaluates mathematical expressions using JavaScript's `Function` constructor in a controlled manner.

### Input Processing

- Sanitizes user input
- Prevents multiple consecutive operators
- Removes trailing operators before evaluation
- Supports decimal calculations

### Result Formatting

- Rounds results to 10 decimal places
- Reduces floating-point precision errors
- Displays clean and readable output

---

## Safety Features

✅ Prevents consecutive operators (`++`, `+*`, etc.)

✅ Removes trailing operators before evaluation

✅ Detects and handles `Infinity`

✅ Detects and handles `NaN`

✅ Uses JavaScript `"use strict"` mode

---

## Browser Compatibility

Supported on all modern browsers:

- Google Chrome (latest)
- Microsoft Edge (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Chrome Mobile
- iOS Safari
- Android Browsers

---

## Customization

You can easily customize the color scheme by modifying the CSS values:

```css
body {
    background: #1a1a2e;        /* Page background */
}

.calculator {
    background: #16213e;        /* Calculator body */
}

.display {
    background: #0f3460;        /* Screen background */
}

.num {
    background: #e94560;        /* Number buttons */
}

.operator {
    background: #0f3460;        /* Operator buttons */
}

.clear {
    background: #533483;        /* Clear button */
}
```

---

## License

MIT License

Feel free to use, modify, and distribute this project for personal or commercial purposes.

---

### Author

**Masud Ibn Musa**

- GitHub: https://github.com/masudibnmusa
- Email: masudibnmusa10@gmail.com

Built with HTML, CSS, and Vanilla JavaScript.