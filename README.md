# L2Disciple web page (GitHub Pages)

`index.html` is the whole page (no other files, no outside scripts or fonts). Made 2026-11-17.

## Put it online (github.com in the browser, no git needed)

1. On github.com: **+** (top right) -> **New repository**. Name it e.g. `l2disciple`, **Public**, -> **Create repository**.
2. On the empty repository page: **uploading an existing file** -> drag `index.html` in -> **Commit changes**.
3. Repository **Settings** -> **Pages** -> *Build and deployment*: Source **Deploy from a branch**, Branch **main**,
   folder **/ (root)** -> **Save**.
4. After a minute or two the page is at `https://<your-github-name>.github.io/l2disciple/`
   (Settings -> Pages shows the address).

To change the page later: open `index.html` in the repository -> pencil icon (Edit) -> change -> **Commit changes**,
or upload a new `index.html` the same way as in step 2.

## Before publishing

- Links: search the file for `CLIENT LINK`, `SYSTEM LINK` and `DISCORD LINK`; put the URL in `href="#"` and remove ` soon`
  from `class="btn soon"` (also the "(coming soon)" text).
- Rates / settings on the page = `run/game/config` on 2026-11-17. If you change a config before going online, change the
  page too.
