# Hush

**English** · [한국어](README.ko.md)

**Browse without the noise: no ads, pop-ups or clutter.**

Hush is an Android browser that gives the page the whole screen and lets you hide anything in
the way with a tap, remembered for the whole site. It is built on the system WebView, with no
account to make and no analytics or ad SDKs inside.

Android 7.0+ · 10 languages · light and dark

---

## Highlights

- **The page gets the screen.** The address bar slides away as you read and leaves a thin strip
  with the site's name. Tap it to bring the bar back, or go fully fullscreen.
- **Hide anything, once.** Tap an ad, a banner or a sticky box and it is gone from every page of
  that site.
- **Ads and trackers blocked from the start**, with optional filter lists for more.
- **YouTube without interruptions.** Ads skipped, playback that carries on in the background,
  videos that reopen where they stopped, your speed and quality on every video, sponsored
  parts skipped and Shorts hidden if you prefer.
- **Private by design.** Tracking stripped from links, Global Privacy Control, and incognito
  tabs in a profile of their own that leaves nothing behind.
- **A password manager** that encrypts on the phone and fills in only where it should.

---

## Features

### Browsing

- **Address bar that steps aside**: at the top or the bottom (Settings › Appearance › Address
  bar). It follows scrolling inside the page's own boxes too, and comes back when a site locks
  scrolling for a menu or a dialog.
- **Fullscreen** from the menu; the corner button or Back leaves it.
- **Compact address**: `naver.com/news` instead of `https://www.naver.com/news`. The full
  address returns when you edit it, or always with "Show full web address".
- **Gestures**: swipe the address bar sideways to switch tabs, pull the page down to reload,
  swipe in from the side of a page to go back or forward, swipe a notice away.
- **Search engines**: Google or Naver, or any site you can search, added with its results'
  address (`%s` where the words go).
- **Suggestions** from your bookmarks, history, open tabs and Google or Naver, with your
  favourite sites as tiles to tap before you type. Never sent from an incognito tab, nor to a
  search engine you added.
- **Start page** for new tabs: a search box, your bookmarks, and the sites you visit most, each
  with its own icon. Drag a bookmark to the top of the list to put it there. An incognito tab's says instead what it does not keep and who
  can still see.
- **Launcher shortcuts**: long-press the app icon for New tab or New incognito tab.
- **Share to Hush** from any app: the link in what you share opens in a new tab, without its
  tracking.
- **Safer by default**: `http` links are tried over `https` first, and open over `http` only
  where the site has no working `https`, as in other browsers. When a page can't load, an error
  page says why, offers the next step, and reloads by itself once you're back online. The
  address bar keeps the address you were going to, ready to fix and try again.
- **Long-press menus** for links, images, phone numbers, email and street addresses.

### Hide what's in the way

- **Menu › Select an area to hide**, then tap it. *Bigger* and *Smaller* pick the right box, and
  everything a rule will hide is outlined before you save. While you pick, the page can't
  navigate or open windows, so tapping an ad is safe.
- **Rules cover the whole site** (`www.` ignored). Turn one off for a single page when you need it.
- **Sites that keep moving** (name42.com, then name43.org) can share one list of rules.
- **Hide rules** (Settings › Ad blocking): every site's rules in one place. Edit a selector, turn a
  rule off everywhere, share a site's rules, or export and import them all as one file.

### Ad and tracker blocking

- **Built in**: known ad servers blocked and generic ad boxes hidden, on from the first launch.
- **Filter lists**, off until you choose them: EasyList, EasyPrivacy, List-KR and the EasyList
  Cookie List. Fetched over HTTPS and refreshed every five days.
- **Cookie banners** of the big consent platforms hidden, and the page unfrozen if it locked
  scrolling behind one.
- **Block pop-ups and page hijacking**: windows you didn't tap for are stopped, with an option to
  open them, and a page can't swap itself for another behind your back.
- **Pause for one site** from the shield in the address bar, which also counts what was blocked.
- A page on a blocked address says "Blocked by Hush", with **Open anyway**.

### YouTube

- **Skip YouTube ads**: ad breaks are taken out of a video's data before the player sees them.
  An ad that still plays is muted, sped up, and skipped with a real tap.
- **Keep YouTube playing in the background**, in picture-in-picture and with the screen off.
- **Resume YouTube videos**: a tab reopens its video where you stopped, under a "Continue
  watching" card. Wait for Play, play when headphones are connected, always play, or off.
- **YouTube Shorts**: hide them in feeds and search, the Shorts button, and channels' Shorts
  tab, each with its own switch. Shorts links still open.
- **Speed and quality**: every video starts at your playback speed, and at the highest quality
  you chose, one for Wi-Fi and one for mobile data. Signed in or not.
- **Skip sponsored parts** with SponsorBlock, off until you turn it on: a sponsor's ad, a plea
  to subscribe, an intro, as you choose, with Undo. SponsorBlock's server is told only the
  first four characters of a code from the video's ID, shared by thousands of videos.
- **From the YouTube app**: Share › Hush opens the video here.

### Video and sound

- **Picture-in-picture** when you leave the app with a video playing, or from the menu for a
  video in the page. The window offers **sound only**. Out of sight, YouTube keeps the picture
  it was playing, so the video is as sharp as you left it when you watch again.
- **Keep playing with the screen off**, with controls and a progress bar on the lock screen:
  back and forward 10 seconds, and previous and next where the page has them.
- **Sleep timer** from the menu: stop after 15 to 90 minutes, or when the video ends, the
  sound fading out first.
- **Pause when headphones disconnect.**

### Privacy and security

- **Incognito tabs** run in a WebView profile of their own (cookies, storage, cache) wherever the
  system WebView supports one, emptied when the last tab closes. They never reach history or the saved session, and the screen can't be
  captured unless you allow it. While any are open, tapping the **Close all incognito tabs**
  notification closes them all; it stays off the lock screen.
- **Remove tracking from links**: `utm_*` and click ids are stripped from links you share, copy
  or follow to another site.
- **Ask sites not to sell or share your data**, with Global Privacy Control.
- **Site information**: whether the connection is secure, the certificate in full (issuer,
  validity, names, fingerprints), and the site's hide rules and permissions.
- **Permissions on demand**: camera, microphone and location are asked per site, and Android's
  permission only when a site you allowed needs it.
- Third-party cookies are off, and an `https` page never loads anything over plain HTTP. **Clear browsing data** takes history,
  cookies and site data, and the cache.

### Passwords

- **Save** after you sign in (never in incognito), and **fill** with a tap on "Sign in as …".
- **Auto-fill** on HTTPS sites with one saved login, into empty fields only.
- **Strong password generator**: length 8–64, character sets, and no look-alike characters.
- **Passwords screen**: add, reveal or copy behind the screen lock, and closed to screenshots.
- Encrypted with AES-256-GCM under a key in the Android Keystore that works only while the phone
  is unlocked, and kept out of backups. A password is only ever saved for, or filled into, the
  site WebView says the page is on, never the site the page claims to be.

### Tabs and library

- **Tab switcher** with a picture of each page: swipe to close with undo, drag to reorder, and
  incognito tabs kept apart.
- **Recently closed tabs**, and undo right after you close one.
- **Unused tabs** free their memory, and can close by themselves after 1 to 90 days.
- **Tabs come back** on the next launch, and only the one in front loads at startup.
- **History** by day, with search.
- **Bookmarks** with search, editing and drag to reorder. Import and export as a standard
  bookmarks file.
- **Downloads**: asks before a page saves a file, then shows progress, open and retry.

### Reading and page tools

- **Reader view**, with **Read aloud**.
- **Find in page.**
- **Screenshot** of what's on screen or the whole page, to save or share.
- **Text size** for every site, or one site at a time from the menu.
- **Desktop site** per tab, **Add to home screen**, and **Print or save as PDF**.

### Make it yours

- **Light, dark** or the system's, and **Darken every site**.
- **Five styles**: Classic, Tonal, Blue, App icons and Glass.
- **10 languages**: English, 한국어, 日本語, 简体中文, 繁體中文, Español, Français, Deutsch,
  Português and Русский. Follow the phone, or choose one for Hush alone.
- **Home page, new tab page** and the home button, as you like them.
- **Set as default browser**, from the welcome sheet or Settings.

---

---

## Download

**[Hush 1.3.9](releases/1.3.9/Hush-1.3.9.apk)** · 3.4 MB · Android 7.0 or later ·
[what's new](CHANGELOG.md)

1. Download the APK on your phone and open it.
2. If Android asks, allow your browser or file app to install unknown apps.
3. An update installs over the version you have and keeps your tabs, bookmarks and passwords.

Picture-in-picture needs Android 8.0, launcher shortcuts Android 7.1.

### Check the download

Every version is signed with the same key. Android refuses an update signed by any other, so
an APK that installs over Hush came from here.

- APK SHA-256: `bd8a887324ead1fbe3f3e36f5f8676162baaca9e16a8b3ba80ed991d245971bf`
- Signing certificate SHA-256: `00:37:AE:C5:11:EF:6B:A7:37:50:6D:24:BD:AC:64:54:04:EE:37:1E:F1:F1:4D:F2:4A:FC:B6:5F:D3:67:8E:52`

```sh
shasum -a 256 Hush-1.3.9.apk
apksigner verify --print-certs Hush-1.3.9.apk
```

## Privacy

No account, no analytics, no ad SDKs. What is kept on the phone and what is sent where is in
the privacy policy, under Settings › About in the app.
