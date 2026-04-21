# ✓ Checklist Creator

A simple, elegant web application that converts comma-separated lists into interactive checklists. Built with vanilla HTML, CSS, and JavaScript - no dependencies required!

## Features

- ✨ **Simple Interface** - Clean, modern UI with intuitive controls
- 🌓 **Dark/Light Mode** - Toggle between dark and light themes
- 🗂️ **Named Sessions** - Save multiple checklist sessions, each with its own title and items
- 💾 **Persistent Progress** - Saved sessions keep checked/unchecked state until you manually delete them
- 📊 **Progress Tracking** - Visual progress bar showing completion percentage
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices
- 🎯 **No Dependencies** - Pure vanilla JavaScript, no frameworks or libraries needed
- 🔒 **Privacy-Focused** - All data stored locally in your browser

## How to Use

1. **Paste your list** - Enter a comma-separated list in the text area
   - Example: `Q1, Q2, Q3, Q4, Q5`
   - ⚠️ **Note:** Do not include commas within list items, as each comma will split the list

2. **Create checklist** - Click the "Turn into Checklist" button

3. **Track progress** - Check off items as you complete them and watch your progress bar update

4. **Save session** - Enter a session title and click "Save Session" to keep the list and current checked state

5. **Switch or delete sessions** - Use the session selector to load another saved checklist, or "Delete Session" when it is no longer needed

6. **Reset current work** - Use "Reset Current" to clear the active working checklist without deleting saved sessions

## Installation

Simply clone this repository and open `index.html` in your web browser:

```bash
git clone https://github.com/Wazed-H/checklist-creator.git
cd checklist-creator
open index.html
```

Or use any local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables and flexbox
- **Vanilla JavaScript** - No frameworks, pure JavaScript
- **localStorage API** - Client-side data persistence

## Browser Support

Works on all modern browsers that support:
- ES6 JavaScript
- CSS Variables
- localStorage API

## Privacy & Data Storage

- All data is stored locally in your browser's localStorage
- No data is sent to any external servers
- Saved sessions persist until you manually delete them
- You can decline localStorage usage; in that mode, data is not persisted

## License

This project is open source and available for personal and commercial use.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Wazed-H/checklist-creator/issues).

## Author

- GitHub: [@Wazed-H](https://github.com/Wazed-H)

---

Made with ❤️ using vanilla web technologies
