# Then & Now — website

A small static website for the app: home page, Privacy Policy, Terms of Use and Support. Plain HTML and CSS, with no build step. It works on phones and in dark mode.

| File | Page |
| --- | --- |
| `index.html` | Home |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms of Use |
| `support.html` | Support / FAQ |
| `style.css`, `icon.png`, `apple-touch-icon.png`, `.nojekyll` | Styling and icons |

## Publish on GitHub Pages (about 10 minutes, free)

1. Sign in at **github.com** (create a free account if needed).
2. Click **+ → New repository**. Name it `thenandnow`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in **all the files from this folder**, including `.nojekyll`. On a Mac, press ⌘⇧. in Finder to show hidden files. Then click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two, the site is live at:

   - Home: `https://YOUR-USERNAME.github.io/thenandnow/`
   - Privacy Policy: `https://YOUR-USERNAME.github.io/thenandnow/privacy.html`
   - Terms of Use: `https://YOUR-USERNAME.github.io/thenandnow/terms.html`
   - Support: `https://YOUR-USERNAME.github.io/thenandnow/support.html`

   GitHub always shows your username in lowercase in the address.

## Then

- In the Xcode project, set `privacyPolicyURL` and `termsOfUseURL` in `ThenAndNow/AppConfig.swift` to the two addresses above, and delete the `#warning` reminder at the bottom of that file.
- In App Store Connect, use the **Privacy Policy** address and the **Support** address (both required). In the app description, include the Terms of Use address (Apple requires it for subscriptions).

## Updating later

Edit a file on GitHub (open it → pencil icon → **Commit changes**). The site updates within a minute. If you change a policy, also update the "Effective" date at the top of the page.
