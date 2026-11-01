# Human Library — PsychSIG Telegram Mini App · v2

A phone-first, self-contained app for an interactive Human Library demo.

## Changes in v2

- Starts directly on the book catalogue, without an intro or headings.
- Bigger covers, minimal editorial purple layout and tighter Inter Tight typography.
- One accessible book: **Anxiety — How it feels like**. Five other books are locked.
- Tap the unlocked book to watch it expand to full size.
- Swipe LEFT on the book to open the front cover and reveal the already rendered first page; swipe LEFT again for page two. Swipe RIGHT to turn back. The app no longer shows a temporary placeholder page.
- On desktop, click near the right or left page edges, or use arrow keys.
- A discreet lock toast replaces the old popup dialog.
- Respects reduced-motion settings; optional Telegram haptics and back button.

## Deploy

Upload **index.html** to the root of a new GitHub repository and enable **Settings → Pages → Deploy from a branch → main → /(root)**. Open the HTTPS URL in a browser or via a Telegram bot web_app button. Keep your bot token out of this public repository.

## Notes

The `Inter Tight` font loads from Google Fonts when internet is available, with local system fallback. All visual styling and interactions are contained in `index.html`.

The preview copy is generic demo text, **not a quotation or account from a real sharer**. Only publish identifiable or sensitive stories after obtaining the sharer's explicit approval. The five locked books have no hidden story data inside the app.
