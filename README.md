# DailyBuiltAI

A growing collection of websites built with AI assistance. Each project is crafted as part of a daily build challenge, showcasing what's possible when combining human creativity with AI tools like [Cursor](https://cursor.com).

## What is this?

**DailyBuiltAI** is a portfolio of small web projects, each built in a single day with the help of AI. The goal is to explore rapid prototyping, experiment with different design directions, and demonstrate practical applications of AI-assisted development.

- **No frameworks** — Vanilla HTML, CSS, and JavaScript
- **AI-built** — Each project is designed and implemented with AI pair programming
- **Open source** — Code is available for learning and remixing

## Projects

| Project | Description |
|---------|-------------|
| **[Random Quote Generator](./Day1/index.html)** | A quote generator with a curated collection of inspirational quotes from around the web. Features a developer-inspired dark theme and serif typography. Built with vanilla JavaScript. |

## Project structure

```
DailyBuildai.com/
├── index.html              # Homepage – lists all projects
├── projects.js             # Project metadata (titles, descriptions, URLs)
├── README.md               # This file
└── Day1/                   # Project: Random Quote Generator
    ├── index.html          # Quote generator page
    └── quotes.js           # Fallback quotes when API is offline
```

## How to run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/TimmyAmant/DailyBuildai.com.git
   cd DailyBuildai.com
   ```

2. Open `index.html` in a browser, or serve the folder with a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js (npx)
   npx serve .
   ```

3. Visit `http://localhost:8000` (or open the file directly).

## Adding new projects

1. Create a new folder for your project (e.g. `Day2/`).
2. Add an `index.html` (and any JS/CSS) for the project.
3. Register it in `projects.js`:

   ```javascript
   {
     id: 'day2',
     title: 'Your Project Name',
     description: 'What it does...',
     url: './Day2/index.html',
     githubUrl: 'https://github.com/TimmyAmant/DailyBuildai.com',
     screenshot: null,
   }
   ```

4. The homepage will automatically list the new project.

## Tech stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, flexbox, grid
- **JavaScript** — Vanilla ES6+, no build step
- **Fonts** — Google Fonts (loaded via CDN)

## License

MIT — Use and remix as you like.

---

*Built with AI and [Cursor](https://cursor.com)*
