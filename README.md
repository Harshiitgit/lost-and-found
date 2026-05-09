# Lost & Found Portal

A web-based platform to report and search for lost and found items.

## Features

- Report lost items
- Report found items
- Search functionality
- Contact support
- Responsive design

## Requirements

- Python 3.6+
- Git
- Modern web browser

## Installation

```bash
git clone https://github.com/Harshiitgit/lost-and-found.git
cd lost-and-found
```

## Quick Start

### Option 1: Using start script (Linux/Mac)
```bash
chmod +x start.sh
./start.sh
```

### Option 2: Python HTTP server
```bash
python3 -m http.server 8000
```

### Option 3: VS Code
Press `Ctrl+Shift+B` (Windows/Linux) or `Cmd+Shift+B` (Mac)

Then open: **http://localhost:8000**

## Project Structure

```
lost-and-found/
├── index.html              # Home page
├── report-lost.html        # Report lost form
├── report-found.html       # Report found form
├── search.html             # Search page
├── contact.html            # Contact page
├── style.css               # Main styles
├── start.sh                # Start script
└── css/                    # CSS files
    ├── common.css
    ├── home.css
    ├── report-lost.css
    ├── report-found.css
    ├── search.css
    └── contact.css
```

## Usage

1. **Home Page** - View overview and quick search
2. **Report Lost** - Submit lost item details
3. **Report Found** - Submit found item details
4. **Search** - Find items by name, category, or location
5. **Contact** - Get support

## Technologies

- HTML5
- CSS3
- JavaScript
- Python HTTP Server

## Troubleshooting

**Port 8000 already in use?**
```bash
python3 -m http.server 8001
```

**Python not found?**
- Windows: Check PATH environment variable
- Mac/Linux: Use `python3` or install via package manager

**Styles not loading?**
- Hard refresh: `Ctrl+Shift+R` (Windows/Linux) or `Cmd+Shift+R` (Mac)

## Contributing

1. Fork the repository
2. Create feature branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "Add feature"`
4. Push: `git push origin feature/your-feature`
5. Create Pull Request

## License

MIT License - See LICENSE file for details

## Support

- Issues: [GitHub Issues](https://github.com/Harshiitgit/lost-and-found/issues)
- Contact: Use the Contact page in the app

---

**GitHub**: [github.com/Harshiitgit/lost-and-found](https://github.com/Harshiitgit/lost-and-found)
