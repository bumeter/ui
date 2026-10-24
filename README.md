# Bumeter UI

The screens of [Bumeter](https://bumeter.cc) — Overview, Conversations, session analysis, Skills, Settings — as one built web page. [Desktop](https://github.com/bumeter/bumeter) loads it in a Tauri window and the [VS Code extension](https://github.com/bumeter/vscode) in a webview.

```
npm install @bumeter/ui
```

The package ships `dist/` only. The page picks its transport at start: Tauri when it runs in Tauri, VS Code when it runs in a webview, otherwise sample data (`npm run dev`).

Develop: `npm install`, `npm run dev`, `npm test`. To try a change in Desktop or the extension without publishing: `npm run build && npm link`, then `npm link @bumeter/ui` in that repo.

License: GPL-3.0-or-later.
