# cliparse

Small TypeScript CLI: CSV to JSON converter

## Install

```bash
npm install
npm run build
```

## Highlights

- commander-based subcommands
- npm link friendly
- Ships as an ESM binary
- Strict tsconfig, no any

## Usage

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version

## License

MIT licensed, see LICENSE.
