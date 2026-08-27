# ai-summary-ext

MV3 extension: one click, tl;dr of any article

## Features

- Reads the page, extracts main text, sends to your endpoint
- Popup shows a 5-bullet summary
- Manifest V3 service worker, no build step
- Options page for API base and key

## How to use

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
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── src/
│   └── config.js
├── .editorconfig
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

## Known issues

- none reported yet (surprisingly)

## License

MIT licensed, see LICENSE.
