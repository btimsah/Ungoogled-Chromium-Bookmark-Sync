# Ungoogled Chromium Bookmark Sync

Synchronize your bookmarks and extensions (store URLS) across any browser or device — **without a Google account, without telemetry, and without the Chrome Web Store.**

Aptosity Bookmarks was originally designed for browsers like Ungoogled Chromium and Helium, but has evolved into a reliable, third-party source of bookmark and extension truth.

Whether you are running **Ungoogled Chromium, Firefox, Brave, or standard Chrome**, this extension and web interface bridge the gap between your isolated, privacy-first browser and the rest of your digital life.

## Why Use This?

- **No Google Account Required** — Decouple your browser data from Google entirely.
- **No Chrome Web Store Required** — Download the raw `.zip` and load it in Developer Mode.
- **Cross-Browser & Device Sync** — Sync directly to your secure web dashboard at [`aptosity.com/sync`](https://aptosity.com/sync), accessible from any browser, including Firefox, Safari, and mobile browsers.
- **Extension Backup** — Saves your installed extension URLs as bookmarks, making it easy to reinstall them on a fresh Ungoogled Chromium setup.
- **Privacy First** — Your data is not sold or exposed. You can wipe your profile from the server at any time.

---

## Getting Started

This extension requires a **free Aptosity account** to act as the sync engine.

### 1. Install the Extension

Because you are not using the Chrome Web Store, you can load the extension manually:

1. Download the latest `UngoogledSync.zip` from the [**Releases page**](https://github.com/).
2. Unzip the file to a permanent folder on your computer.
3. Open Ungoogled Chromium and navigate to `chrome://extensions/`.
4. Enable **Developer mode** in the top-right corner.
5. Click **Load unpacked** and select the unzipped folder.
6. Pin the Aptosity extension to your toolbar.

### 2. Connect Your Browser

Once the extension is installed:

1. Sign up or log in at [**Aptosity.com/sync**](https://aptosity.com/sync).
2. Open the **Config** tab on the web dashboard and copy your unique **Sync Token**.
3. Click the Aptosity extension icon in your browser toolbar and open **Config/Settings**.
4. Paste your Sync Token.
5. Click **Import from Browser** to push your current local bookmarks to the cloud.

> **No local bookmarks?**  
> Go to the web dashboard's **Config** tab and upload your exported `bookmarks.html` file.

> **Want to back up your extensions?**  
> In the browser extension popup, click **Sync Extensions**. This saves your installed extensions as URLs in an **Extensions** folder.

---

## Managing Your Data

You are always in control of your synchronization data.

- **Export** — Download a standard `bookmarks.html` file at any time and import it into any browser's native bookmark manager.
- **Wipe Profile** — Instantly clear your Aptosity profile from the server.  
  *Wiping does not affect bookmarks already stored in your browser; it only clears the cloud copy.*
- **Revoke Token** — Regenerate your Sync Token to instantly sever the connection between your browser and the server.

---

## Premium Features

Aptosity is independently run by one person, with no corporate affiliation. To keep the infrastructure running without unwanted tracking or ads, premium features are unlocked through **one-time payments** — there are no recurring subscriptions.

### Premium Includes

- **Download Extension (.zip)** — Direct access to the standalone `.zip` file for Ungoogled Chromium, Helium, or other browsers without Chrome Web Store access.
- **Full Sync Features** — Unlock advanced synchronization options and full dashboard capabilities.

> Premium payments are one-time charges, helping avoid unwanted recurring billing.

---

## Pro Tips for Multi-Browser Users

### Helium

Match the Aptosity aesthetic by setting your browser appearance to **Violet** in Helium's settings.

### Mobile Access

Set your mobile browser's new-tab or home page to:

`https://aptosity.com/sync/`

This gives you instant access to your bookmarks on the go.

### Firefox

Use a custom new-tab extension to set your home page to:

`https://aptosity.com/sync/`

### Exporting Bookmarks

In standard Chrome, Brave, or Edge:

1. Open the Bookmark Manager with `Ctrl+Shift+O`.
2. Click the `⋮` menu.
3. Select **Export bookmarks**.
4. Save the resulting `bookmarks.html` file.

---

## Support & Notes

- **Independent Project** — Aptosity is designed to be as simple, reliable, and friction-free as possible.
- **Refresh** — To see the latest bookmark changes on the web interface, simply refresh the page.

---

## Get Started

Visit [**Aptosity.com/sync**](https://aptosity.com/sync) to get started.
