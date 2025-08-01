# qnts

[![npm version](https://badge.fury.io/js/qnts.svg)](https://badge.fury.io/js/qnts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Quick TypeScript Setup - A lightweight CLI tool to instantly scaffold a Node.js + TypeScript project with zero configuration.

## Installation

```bash
npm install -g qnts
```

or using npx (no installation required):

```bash
npx qnts my-project
```

## Usage

Create a new TypeScript project:

```bash
qnts <project-name>
```

Example:
```bash
qnts my-awesome-app
cd my-awesome-app
npm run dev
```

## What's Included

Each generated project includes:

- **TypeScript** 5.x configured and ready to use
- **ts-node** for direct TypeScript execution
- **Sensible tsconfig.json** with strict mode enabled
- **npm scripts** for development, building, and running
- **Sample code** to get you started immediately

### Generated Project Structure

```
my-project/
├── src/
│   └── index.ts       # Entry point with sample code
├── package.json       # Pre-configured with scripts and dependencies
└── tsconfig.json      # TypeScript configuration with strict mode
```

### Available Scripts

- `npm run dev` - Run TypeScript files directly (development mode)
- `npm run build` - Compile TypeScript to JavaScript
- `npm start` - Run the compiled JavaScript (production mode)

## Requirements

- Node.js 14.x or higher
- npm 6.x or higher

## Why qnts?

Unlike other TypeScript starters that come with complex build tools, bundlers, and configurations, `qnts` focuses on simplicity. It's perfect for:

- Quick prototypes
- Learning TypeScript
- Small scripts and utilities
- Starting a project without decision fatigue

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

```bash
# Clone the repository
git clone https://github.com/yourusername/qnts.git
cd qnts

# Install dependencies
npm install

# Build the project
npm run build

# Test locally
npm link
qnts test-project
```

## License

MIT © [Shoki Maeta]

## Keywords

typescript, nodejs, cli, scaffold, starter, boilerplate, quick-start, ts-node, development-tools