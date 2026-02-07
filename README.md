# Python Wizard Academy

A magical, Harry Potter-themed Python learning app for young witches and wizards (ages 10-12). Learn programming through casting spells, brewing potions, and drawing with your wand!

**[Try it live](https://peter8zero.github.io/python-wizard-academy/)** 

## Features

### Magical Lessons
10 progressive lessons themed around the wizarding world:
1. **Your First Spell** - `print()` statements (Lumos!)
2. **Naming Your Owl** - Variables
3. **Potions Class** - Maths operations
4. **The Sorting Ceremony** - If/Else decisions
5. **Quidditch Practice** - Loops
6. **Care of Magical Creatures** - Lists
7. **Creating Your Own Spells** - Functions
8. **Spells with Ingredients** - Function parameters
9. **The Marauder's Map** - Combining concepts
10. **Wand Movements** - Turtle graphics drawing

### Real Python in the Browser
- Runs actual Python code using Pyodide (WebAssembly)
- No installation required - works entirely in the browser
- Immediate feedback on code execution

### Turtle Graphics
- Draw magical shapes and patterns with code
- Visual, creative way to learn programming concepts
- Commands: `forward()`, `right()`, `left()`, `color()`, and more

### Progress System
- **House Points** - Earn points for completing lessons
- **Achievements** - Unlock badges like "Apprentice Wizard" and "House Champion"
- **Progress Tracking** - Saved automatically in the browser
- **Export/Import** - Download progress to transfer between devices

### Kid-Friendly Design
- Magical purple and gold theme with twinkling stars
- Harry Potter-inspired terminology throughout
- Encouraging feedback and hints
- Large, readable fonts

## Usage

### Option 1: Open Locally
Open `index.html` in any modern web browser. The first load takes a few seconds to download the Python runtime (~10MB, cached after).

### Option 2: Host on GitHub Pages
1. Push to a GitHub repository
2. Go to Settings → Pages
3. Deploy from the `main` branch
4. Share the link with your young wizard!

## Technical Details

- **Single HTML file** - No build step, no dependencies to install
- **Pyodide** - Python interpreter compiled to WebAssembly
- **localStorage** - Progress persists between sessions
- **Vanilla JavaScript** - No frameworks required

## Lesson Structure

Each lesson includes:
- Story-themed introduction
- Code examples with magical context
- Starter code to modify
- Automatic validation of solutions
- Points reward on completion

## The Spellbook

A reference section covering:
- Basic incantations (print, input)
- Magical containers (variables)
- Arithmancy (maths)
- The Sorting Hat (if/else)
- Time-Turner (loops)
- Magical lists
- Creating spells (functions)

## Browser Support

Works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

**Note:** First visit downloads ~10MB for the Python runtime. This is cached for future visits.

## For Parents

This app teaches real Python programming through:
- Guided, progressive lessons
- Immediate visual feedback
- Creative expression through Turtle graphics
- Achievement system for motivation

No account required. All progress is stored locally on the device.

## License

MIT License - feel free to use and modify!
