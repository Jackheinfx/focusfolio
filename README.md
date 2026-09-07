# focusfolio

MV3 extension playground: page reading-time estimator

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Features

- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based
- No remote calls, everything stays local

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT - see [LICENSE](LICENSE).
