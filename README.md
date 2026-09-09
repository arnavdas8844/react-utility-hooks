# react-utility-hooks

A handful of React hooks I keep copy-pasting between projects

## What it does

- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- Tiny: no dependencies besides React

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Getting started

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```
