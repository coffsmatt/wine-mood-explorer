# 🍷 Wine Mood Explorer

**Find a wine for the moment. Discover something new.**

Wine Mood Explorer is a free, interactive, mobile-friendly wine discovery app designed for friends, casual wine drinkers and curious enthusiasts.

Inspired by the educational approach of *Wine Folly*, it helps you explore wine based on your mood, occasion and personal taste preferences, with a particular focus on Australian wine varieties and regions.

## What's new in v3

- **Match scores and taste bars** on every pick, with a tick showing what you asked for
- **For the table** – everyone sets their taste, the app finds a bottle the whole group will enjoy (or a two-bottle plan)
- **My wines** – tap 👍 Loved it, 👎 Not for me or 🔖 Want to try; after two loved wines the app works out your style and tunes its picks
- **Share** your picks or your list straight to a group chat; shared links open with your settings
- **Guess the grape** – a wine-night game in the Explore tab
- Quiet evening and Adventurous now change the picks, Tasmanian sparkling counts as Australian, three Australian rosés added, offline support (`sw.js`) and iPhone home-screen icon added
- Dark mode throughout

## Features

### 🎭 Choose Your Mood
Select an occasion, including:
- Quiet evening
- With friends
- Dinner
- Celebrating
- Feeling adventurous

### 🎚️ Explore Your Taste
Use three intuitive sliders to describe your preferences:
- Light & delicate ↔ Bold & powerful
- Rich & mellow ↔ Crisp & refreshing
- Bone-dry ↔ Noticeably sweet

You can also select a wine colour or style and indicate what food you're eating.

### 🍇 Three Personalised Recommendations

**Safe Bet:** A familiar, reliable wine style.

**Smart Swap:** A related variety or regional alternative.

**Discovery Pick:** A less familiar wine worth exploring.

Each recommendation includes flavour characteristics, typical structure, Australian wine regions and related varieties.

### 🔬 Wine Geek Mode
Optional advanced controls for:
- Tannins
- Oak influence
- Fruit character

### 🎲 Surprise Me
Discover a less familiar wine variety that might suit your preferences.

### 📚 Learn About Wine
Explore different grape varieties, their typical flavour profiles, structural characteristics and regional expressions.

## Getting Started

No account, subscription or installation is required.

Open the published app in a web browser and start exploring.

## Publishing with GitHub Pages

1. Create a public GitHub repository named `wine-mood-explorer`.
2. Upload the application files to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save and wait for deployment.

Your app will be available at:

`https://YOUR-USERNAME.github.io/wine-mood-explorer/`

Replace `YOUR-USERNAME` with your GitHub username.

## Add to Your iPhone Home Screen

1. Open the published app in Safari.
2. Tap the Share button.
3. Select **Add to Home Screen**.
4. Tap **Add**.

The app can then be launched from your Home Screen.

## Project Files

```text
wine-mood-explorer/
├── index.html
├── manifest.webmanifest
├── icon.svg
├── sw.js
├── icon-180.png
├── icon-512.png
└── README.md
```

| File | Purpose |
|---|---|
| `index.html` | Main interface and recommendation engine |
| `manifest.webmanifest` | Web app configuration |
| `icon.svg` | App icon |
| `sw.js` | Offline caching support (bump `CACHE` in it when you upload a new version) |
| `icon-180.png`, `icon-512.png` | iPhone and Android home-screen icons |
| `README.md` | Project documentation |

## Privacy

- No user accounts, no database, nothing sent anywhere
- Your ratings and table settings are saved **on your own phone only** (browser storage) and can be cleared from the My wines tab

## Offline Use

The app includes a service worker to support offline use after the necessary files have been cached during an online visit.

Offline availability depends on browser support and cache retention.

## Updating the App

To make changes, edit `index.html` or the relevant project files and commit the updates to GitHub.

GitHub Pages will automatically publish the new version.

Some users may need to refresh the app to receive updates if an older version is cached.

## Wine Recommendation Disclaimer

Recommendations are educational and approximate.

Wine characteristics vary depending on region, climate, vintage and winemaking practices. Mood-based matching is intended as an enjoyable discovery experience rather than a scientifically validated assessment.

The app does not guarantee the availability of specific wines or bottles.

## Future Possibilities

Potential future improvements include:
- More grape varieties and wine regions
- Detailed regional wine
