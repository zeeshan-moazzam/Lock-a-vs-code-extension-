# 🔒 Lock - Read-Only Lock for VS Code  #
 
**Stop accidentally editing files you shouldn't touch.**

Lock adds a one-click lock icon to your VS Code status bar. Click it to instantly freeze your editor into read-only mode. Click again to unlock. That's it.

---

## The Problem

You open a config file, a `.env`, a production schema — just to *read* it. Five minutes later you've accidentally changed something and don't even know it. VS Code has no quick way to prevent this.

## The Solution

![Status bar showing unlocked and locked states](https://raw.githubusercontent.com/your-username/lock/main/assets/demo.gif)

Lock puts a **lock icon in the bottom-right corner** of your editor. One click locks the entire editor into read-only mode — highlighted in yellow so you always know the state you're in.

---

## Features

- **One-click toggle** — lock and unlock from the status bar
- **Visual indicator** — status bar turns yellow when locked, so you never forget
- **Zero config** — works immediately after install, no settings to configure
- **Lightweight** — runs silently in the background, zero performance impact

---

## How to Use

1. Install Lock from the VS Code Marketplace
2. Look for the **unlock icon** `🔓` in the bottom-right status bar
3. Click it to lock — the bar turns **yellow** and shows `🔒 Locked`
4. Click again to unlock

You can also run the command manually:
> `Ctrl+Shift+P` → `Lock: Toggle Read-Only Mode`

---

## Install

**From the Marketplace:**
Search `Lock` in the VS Code Extensions sidebar (`Ctrl+Shift+X`) and click Install.

**From .vsix (manual):**
```bash
code --install-extension lock-0.0.1.vsix
```

---

## Requirements

- VS Code **1.75.0** or newer

---

## Inspiration

This extension is **highly inspired by IntelliJ IDEA**.

When I switched to IntelliJ IDEA for a new project, I discovered its built-in read-only lock button — a small icon sitting quietly in the status bar that lets you freeze the entire editor with one click. It felt obvious, useful, and something I reached for constantly.

Then I went back to VS Code and realized: *it doesn't have this.*

There's no quick toggle, no status bar button, no visual indicator. If you want read-only mode in VS Code, you're digging through settings or relying on OS-level file permissions. That's too much friction for something so simple.

So I built **Lock Toggle** — bringing that one feature from IntelliJ IDEA that VS Code was missing.

---

## Why "Lock"?

Simple name, simple purpose — one click to lock your editor.

---

## Contributing

Found a bug or have an idea? Open an issue on [GitHub](https://github.com/your-username/lock).

Pull requests are welcome.

---

## License

MIT — free to use, modify, and distribute.
