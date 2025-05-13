# MIDI Electron App

A cross-platform MIDI application built with **Electron**, **React 19**, **TypeScript**, and **Vite**.

## Features

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)

### Install dependencies

```sh
npm install
```

### Development

Start both the React frontend and Electron app in development mode:

```sh
npm run dev
```

- React app runs at [http://localhost:3000](http://localhost:3000)
- Electron opens a window pointing to the dev server

### Lint

```sh
npm run lint
```

### Build

Build both the Electron and React apps:

```sh
npm run build
```

### Package for Distribution

#### Windows

```sh
npm run t:win
```

#### Linux

```sh
npm run t:linux
```

The packaged app will be in the `dist/` directory.

## Project Structure

```
├── dist-electron/      # Compiled Electron main process
├── dist-react/         # Compiled React frontend
├── src/
│   ├── assets/         # App icons and static assets
│   ├── electron/       # Electron main process source
│   └── ui/             # React UI source
├── electron-builder.json
├── package.json
├── vite.config.ts
├── tsconfig*.json
└── README.md
```

## Configuration

- **Electron Builder:** See [electron-builder.json](electron-builder.json)
- **Vite:** See [vite.config.ts](vite.config.ts)
- **TypeScript:** See [tsconfig.app.json](tsconfig.app.json), [tsconfig.node.json](tsconfig.node.json)

