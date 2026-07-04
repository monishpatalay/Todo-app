# Todo App (React)

A simple React to-do list — add a task, check it off to remove it. Originally built as ES6 spread-operator practice (see `package.json` name).

**Live site:** https://monishpatalay.github.io/Todo-app/

## Features

- Add a task via a text input
- Click a task to remove it (`deleteItem` filters it out by index)

## Tech Stack

React 16.8 (`react-scripts` / Create React App tooling).

## Running It

```bash
npm install
npm start
```

Opens at [http://localhost:3000](http://localhost:3000).

### Build for production

```bash
npm run build
```

## Note on repo size

This repo's `node_modules` directory is committed to git (no `.gitignore`), which bloats the repository significantly. Consider adding a `.gitignore` with `node_modules/` and running `git rm -r --cached node_modules` to untrack it going forward.
