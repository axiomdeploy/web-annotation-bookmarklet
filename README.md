# ⬡ Annotate

A **zero-installation screen annotation bookmarklet** for Chrome. Draw, highlight, and present on any website — pen, shapes, laser pointer, spotlight, and more, straight from your bookmarks bar.

**No extension. No download. No setup. No installation required.**

## ✨ Features

| Feature            | Description                                          |
| ------------------ | ---------------------------------------------------- |
| ✏ **Pen**          | Smooth freehand drawing with stylus pressure support |
| ▭ **Box**          | Snap rectangles around anything                      |
| ➤ **Arrow**        | Point exactly where it matters                       |
| ◉ **Laser**        | Glowing pointer with fade-out, sparks & rainbow mode |
| 🧽 **Eraser**      | Clean up individual strokes                          |
| 🖱 **Click-pass**  | Page stays fully interactive — links & buttons work  |
| 🔍 **Spotlight**   | Dim the page and highlight one area                  |
| 🔒 **Scroll lock** | Freeze the page while presenting                     |
| 💾 **Save PNG**    | Export your annotations as a transparent PNG         |
| 🧠 **Lightweight** | Single file, zero dependencies, capped memory        |

The toolbar automatically tucks itself away when the mouse moves away, turns into a glowing hexagon pill, and returns when you hover over it.

The toolbar is also fully draggable.

## 🚀 Setup

### 1. Open the installer page

Open the **Annotate** installer page hosted on GitHub Pages, or open `index.html` locally.

### 2. Bookmark the page

Press **Ctrl + D** and name the bookmark:

```text
Annotate
```

The installer page includes the green hexagon favicon.

### 3. Copy the bookmarklet

On the installer page, click:

```text
✒ Copy code
```

### 4. Replace the bookmark URL

Right-click the **Annotate** bookmark → **Edit** → replace the URL with the copied code → **Save**.

### 5. Use it anywhere

Open any regular website and click the **Annotate** bookmark.

Done. ✅

> **Tip:** You can also drag the Annotate button directly onto the bookmarks bar.
>
> If the icon becomes generic after dragging, use the bookmark-and-edit method above. This preserves the hexagon icon.

## ⌨️ Keyboard Shortcuts

| Key                | Action                              |
| ------------------ | ----------------------------------- |
| `1` – `5`          | Pen · Box · Arrow · Laser · Eraser  |
| `` ` `` (backtick) | Click-pass — page fully interactive |
| `Z`                | Lock / unlock page scrolling        |
| `X`                | Clear all drawings                  |
| `Ctrl + Z`         | Undo last stroke                    |
| `C`                | Cycle color                         |
| `S`                | Save PNG                            |
| `H`                | Spotlight — scroll to resize        |
| `R`                | Rainbow laser                       |
| `Esc`              | Close Annotate completely           |

> **Note:** `0` is not used as a shortcut.

## 🎁 Hidden Features

### 🌈 Rainbow Laser

Double-click the **Laser** button or press:

```text
R
```

### 📏 Straight Lines

Hold **Shift** while drawing with the Pen to create straight lines.

### ⬡ Hexa Pill

Press **▼** in the header to minimize the toolbar into a hexagon pill.

You can drag the pill anywhere and click it to expand the toolbar again.

### 💡 Tool Flash

When the toolbar is minimized, switching tools using the keyboard displays a small tooltip showing the active tool.

## 🌐 Compatibility

Annotate works on regular websites using:

* Google Chrome
* Microsoft Edge
* Brave
* Other Chromium-based browsers
* Firefox and other modern browsers supporting bookmarklets

### Limitations

Bookmarklets do not run on browser-internal pages such as:

```text
chrome://
edge://
```

They may also be blocked on heavily sandboxed pages, including some browser extension stores and other restricted pages.

## 🔐 Privacy

Annotate is designed to run entirely in your browser.

* No account required
* No external server required
* No analytics
* No data collection
* No extension installation
* No dependencies
* Website content is not uploaded anywhere

## 🛠️ Technical Details

Annotate is implemented as a JavaScript bookmarklet.

The installer keeps the source code in a plain-text script block and automatically generates the bookmarklet URL using `encodeURIComponent()`.

This means special characters such as:

```text
#
%
`
spaces
```

do not need to be manually encoded in the source code.

The same generated bookmarklet is used for:

* **Copy code**
* **Drag & Drop**
* **Preview**

## 📂 Project Structure

```text
Annotate/
├── index.html
└── README.md
```

## 📄 License

MIT License — free to use, modify, and share.

---

**⬡ Annotate — Draw anywhere. Highlight anything. Present with confidence.**
