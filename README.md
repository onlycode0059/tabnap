# tabnap

MV3 extension playground: page reading-time estimator

Built for my own use; public in case it helps someone.

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Features

- Popup shows today's total focus time
- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local

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

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas
