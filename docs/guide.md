# MyMath user guide

[English](guide.md) · [한국어](guide.ko.md) · [← Back to the project page](../README.md)

From install to print, only what you need, in order. If you are new, sections 1–3 are enough to get going.

## 1. Install

One installer sets up both the editor and the InDesign plugin. There is nothing to configure.

1. **Run the installer** — Double-click `MyMath-Setup.exe`. It installs without asking anything, and the editor opens once when it finishes.

   > 💡 If **"Windows protected your PC"** appears, click **[More info] → [Run anyway]**. It shows because this free app is not code-signed yet.

2. **Open the panel in InDesign** — Restart InDesign and choose **[Plugins] → MyMath**. If a folder path is already filled in under "Connection" at the bottom of the panel, you are ready.
3. **First time only — [Allow]** — The first time you place an equation, InDesign asks whether the plugin may launch the editor. Tick **[Remember my choice]** and click **[Allow]**. It won't ask again.

   > This is a standard Adobe security prompt that applies to every plugin.
   > ![](../img/permission-dialog.png)

### Requirements

- **InDesign 18.5 (August 2023) or later** — earlier versions cannot run this kind of plugin panel.
- **Windows 10 / 11** and the Adobe Creative Cloud app (you already have it if you use InDesign).

### Uninstall

Windows Settings → Apps → uninstall "MyMath Editor". The editor and the InDesign plugin are removed together. Equations already in your documents stay, and print as before.

## 2. Your first equation — 10 seconds

The shortest route is the quick-insert box in the panel. You never leave InDesign.

1. **Put the cursor in a text frame** — Click with the Type tool where the equation should go.
2. **Type in the quick-insert box** — Type it the way it reads — `1/2`, `x^2`, `sqrt(2)`, `(a+b)/(c+d)` — or use LaTeX (`\frac{a}{b}`).
3. **Press Enter** — The editor renders it in the background and places it at the cursor, sized to the body text and vertically aligned for you.

## 3. Building equations in the editor

For longer equations, click **[Edit Equation]** in the panel to open the editor. When you are done, click the editor's **[InDesign]** button (or <kbd>Ctrl</kbd>+<kbd>S</kbd>) — it is placed at the cursor.

![](../img/shot1-gallery.png)

### Fastest: pick one and tweak it

The **equation gallery** under the canvas holds more than 1,000 equations shown exactly as they render. Click something close: it lands on the canvas with the cursor in the first empty slot (⬚). Change the numbers and letters.

### Building from scratch

- **Just type** — `x^2` and `1/2` turn into math as you go.
- **Ribbon** — palettes for fractions, roots, integrals, matrices, brackets and more. Matrices open a wizard where you set the size.
- <kbd>Ctrl</kbd>+<kbd>/</kbd> — **symbol search** by name ("root", "integral", "permutation").
- <kbd>Ctrl</kbd>+<kbd>G</kbd> then a letter — **Greek** (G → γ, Shift+G → Γ). Works whatever your keyboard layout.
- <kbd>Enter</kbd> — **new line** (multi-line equations). Use [Align at =] in the properties panel to line up the equals signs.
- <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>V</kbd> — **smart paste**. Detects Word equations, MathML, AsciiMath or LaTeX and pastes accordingly.

### Keeping your favourites

The left sidebar has **Recent, Favourites and Clips**. Clips are saved as named files (`Documents\MyMath\Clips`), so you can share the folder with colleagues.

## 4. Editing an equation

The equation source is stored inside the document, so you can always re-edit in place.

1. **Click the equation in the document** — Use the Selection tool. The panel shows the equation's content and size.
2. **[Edit Equation]** — The editor opens with that equation loaded.
3. **Change it, then [InDesign]** — The equation is replaced in the same spot and the text after it reflows naturally.

## 5. Whole manuscripts

A book with hundreds of equations doesn't have to be done one by one.

### Manuscripts written with $…$

Write equations as plain text like `$x^2+1$`, flow the manuscript into InDesign, then click **[Convert $...$ equations]** in the panel's Document section once. Every `$…$` becomes an equation graphic. Write a real dollar sign as `\$` and it is left alone.

### Word and Hangul manuscripts

Put the cursor in a text frame and click **[Place manuscript (Word · HWPX)]**, then pick a `.docx` or `.hwpx` file. The text flows in and the equations inside the manuscript become graphics automatically. For old `.hwp` files, re-save as HWPX in Hangul first.

### Scope

Use **[Scope: whole document / selected frame]** in the panel to limit the operation — handy when you only want to convert one chapter.

## 6. Working with the whole document

| | |
|---|---|
| **Re-render all equations** | After changing the body size or typesetting settings (script ratios, rule thickness, colour), this updates every equation in the document. The size box next to it can also unify all equations to one size. |
| **Send equation list** | Every equation in the document appears in the editor sidebar under "Document equations", with page numbers. Click one to edit it. 🔍 **Check** finds typos (commands that don't render), empty slots and duplicates — use it at the proofing stage. |
| **Count equations** | Tells you at once, e.g. "128 equations across 34 pages". |
| **Export** | CSV (page, content, size), SVG, PNG — for reusing the same equations on the web or in slides. |

## 7. Vertical position

Inline equations are centred on the body text automatically. You rarely need to touch this.

To nudge one particular equation: select it and use **▲ ▼** under "Vertical offset" in the panel. The step (0.05–1 pt) is set in the dropdown beside it. **[0]** returns it to the automatic position. The nudge applies only to the selected equation and never affects equations you place later.

## 8. Print quality

- Equations are placed as **vector PDF**. They stay sharp at any magnification.
- Black is **pure K100**, not a four-colour black, so it prints on the black plate only. Verified with PDF/X-1a export.
- Glyphs are drawn as **outlines**, so there are no math fonts to install or send to the printer.
- Equation graphics are **embedded** in the document. No linked files, so no "missing links".
- In the editor's Preferences (<kbd>Ctrl</kbd>+<kbd>;</kbd>) under "Print colour" you can choose direct CMYK, a **spot colour** or **overprint**. The default (K100) suits most books.

## 9. Language

The panel and the editor **follow InDesign's language**. To use a different one, choose it under **Language** at the bottom of the panel's Connection section — the panel changes at once and the editor follows. To change only the editor, use its menu **View → Language**. Supported: English · 한국어 · Deutsch · Français · 日本語 · Español · 简体中文 · Português · Italiano · Русский.

## 10. Troubleshooting

**MyMath is missing from the [Plugins] menu**

Check that InDesign is 18.5 or later (Help → About InDesign) and fully restart InDesign. If the installer showed a message saying the plugin could not be added, just run the installer once more.

**[Edit Equation] doesn't open the editor**

You may have clicked [Block] in the first permission prompt. Start **MyMath Editor** from the desktop yourself and the panel connects straight away — keeping the editor open is also the fastest way to work.

**Body text disappeared after placing an equation**

Click **[Redraw view]** in the panel's Document section. It is a display glitch only; your document is intact.

**I see red text inside an equation**

That is an unknown command (a typo). Fix that part in the editor. If an equation still has empty slots (⬚), the editor warns you before placing it.

**The editor closed unexpectedly**

Open it again: a recovery bar appears above the canvas. Click [Recover] to get back what you were editing.

**Still stuck**

The panel keeps its own log: `panel-boot.log` in the `PluginData` folder under `%APPDATA%\Adobe\UXP\PluginsStorage\IDSN`. Send that file along and the cause can be found quickly. Send it to uibsee@hanmail.net or attach it to a GitHub issue.
