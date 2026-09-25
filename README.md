# The House of Unkept Promises - Telegram Interactive Reader

This folder is a static Telegram Mini App. No server or always-on computer is required for the reader itself.

## What is included
- 34-chapter table of contents grouped into 5 parts
- Chapter reader with Previous / Next
- Search across the whole book
- Chapter bookmarks
- Reading position / Continue Reading
- Font-size controls
- Light / dark theme
- Telegram Mini App integration

## Phone-only setup (GitHub Pages)
1. On your phone, create a free GitHub account if needed.
2. Create a new PUBLIC repository, for example `unkept-promises-reader`.
3. Upload these files to the repository root: `index.html`, `styles.css`, `app.js`, `book.json`, `cover.png`.
4. In the repository: Settings -> Pages -> Build and deployment -> Deploy from a branch -> `main` / root -> Save.
5. GitHub will give you an HTTPS Pages address. Open it in Safari/Chrome first and make sure the reader works.
6. In Telegram open @BotFather and create/select your bot.
7. Configure the bot's Menu Button / Mini App with your HTTPS Pages address. Use button text such as `Open Book`.
8. Open your bot, tap Start, then tap `Open Book`.

## Important
- Do not put your BotFather token in these files. This reader does not need the token.
- Bookmarks and reading progress are saved on the device/browser using localStorage.
- Anyone with the Pages URL can access the book if the repository/site is public. For private access, add authentication or use a private hosting/backend setup.

## Optional next upgrade
An `Ask the Book` feature can be added later, but that needs a backend/API so secrets are not exposed in the browser.
