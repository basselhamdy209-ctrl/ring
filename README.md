# Secret Ring Gift ❤️

A small, responsive romantic gift page with a CSS 3D-style ring, animated gemstone, floating hearts, a revealable message, pause control, and sparkle effect. It uses HTML, CSS, and JavaScript only.

## Preview locally
1. Extract `secret_ring_gift.zip`.
2. Open `index.html` in a browser.
3. Internet is only needed for the optional Google Fonts import; the page still works without it.

## Publish a shareable link with GitHub Pages
1. Sign in or create an account at https://github.com/.
2. Create a **new public repository** (for example, `secret-ring-gift`). GitHub Pages on a free plan generally requires a public repository.
3. Upload `index.html`, `style.css`, and `script.js` to the repository's root folder.
4. Open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
6. Wait for GitHub Pages to publish. The shareable URL will look like `https://YOUR-USERNAME.github.io/secret-ring-gift/`.
7. Send the URL only to the intended person.

## Privacy: important limitations
- The page includes `noindex` meta tags to ask compliant search engines not to index it. This is **not access control** and cannot guarantee that it will never appear in search.
- Anyone who receives or guesses the URL can open it, and the recipient can forward it or take screenshots.
- A public GitHub repository means the page's source files are public. Do not put real passwords, private data, personal contact details, or anything confidential in these files.
- A hard-to-guess URL is less discoverable, but it is still not password protection.
- If you need actual access restriction, host it behind a password-protected service or implement server-side authentication. A password written only in client-side JavaScript is not secure.
- The page requests `no-referrer`, but hosting/CDN logs and the hosting provider may still record ordinary access metadata.

## Customize the message
Open `index.html` and edit the text inside:
`<p class="message">A little something, just for you <span>❤️</span></p>`
Then save and upload the changed file.
