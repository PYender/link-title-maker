# Link Title Maker

A tiny, free web app that turns any URL into a **clickable word or phrase**. Perfect for emails and documents when you don’t want to paste full URLs or write a prompt each time.

**Live usage:** host this `index.html` with GitHub Pages and open it in the browser.

---

## Quick start (GitHub Pages)

1. Create a repository, e.g. `link-title-maker`.
2. Add this file as `index.html` at the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch** → branch `main` → folder **/** (root). Save.
5. After a minute, your app will be live at  
   `https://<your-username>.github.io/<your-repo>/`

> If you prefer a `/docs` folder, move `index.html` into `/docs` and select that folder in Pages settings.

---

## How to use

1. **Prefix** *(optional)* — text that appears before the link (e.g., `view repo:`).
2. **Link text** — the word/phrase you want clickable.
3. **URL** — destination (must start with `http://` or `https://`).
4. Click **Generate**.
5. Copy one of:
   - **Copy HTML (linked)** — pastes only the clickable word/phrase (works best in Gmail/Word/etc.).
   - **Copy HTML (with prefix)** — same, but includes the prefix outside the link.
   - **Copy Markdown** — `[Link text](URL)`.
   - **Copy Markdown (with prefix)** — `Prefix [Link text](URL)`.

**Modes:**
- **Link text only** *(default)* — only the “Link text” is clickable.
- **Prefix + text** — the whole phrase becomes the link.

---

## Notes

- Clipboard features require a **secure context** (HTTPS). GitHub Pages is HTTPS, so everything works.
- LinkedIn/SMS don’t support clickable anchor text in plain posts; only the raw URL is clickable.
- Want to change the corner label? Replace “HIVEEVE Project” in the `.brand` element.

---

## Local use (optional)

Open `index.html` locally in a browser. If the **Copy** buttons don’t insert styled HTML (varies by browser security), the app falls back to copying plain text/Markdown.

---

## Credits

Built for the **HiveEve Project**. Free to use.
