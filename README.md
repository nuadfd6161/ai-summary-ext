# ai-summary-ext

Chrome extension that summarizes the current page with an LLM

Started as a weekend hack, grew on me.

## Features

- Popup shows a 5-bullet summary
- Options page for API base and key
- Manifest V3 service worker, no build step
- Reads the page, extracts main text, sends to your endpoint

## Usage

```bash
# open any article, click the icon, get a 5-bullet summary
```

## Getting started

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
