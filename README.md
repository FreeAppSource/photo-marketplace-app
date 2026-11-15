# Photo App

> 👨‍💻 Developed by **[Suresh Kumar Meesala](https://github.com/SureshKumarMeesala)** · 🎨 UI design by **2 Four** (credits below)

A mobile app built with **React Native (0.88+)**, **Expo SDK 58+** and **Expo Router**, using **JavaScript and JSX (`.js`, `.jsx`)**. Every screen is built from the original Sketch design `photo-app-2-four.sketch` by **2 Four**: one route per artboard, with the artboard's layout, colours, images and text.

![Photo App screens](./showcase.jpg)

## 📱 Screens (18 design artboards)

Listed in the order of the app's flow. "Taps" is the number of tap targets wired on the screen (buttons, tabs, back arrows, list rows).

| # | Screen (artboard) | Route | Size | Taps |
|---|---|---|---|---|
| 1 | **01-Home** · start screen | `src/app/s-01-home.jsx` | 375 × 812 | 8 |
| 2 | **05-Messages** | `src/app/s-05-messages.jsx` | 375 × 814 | 6 |
| 3 | **postt** | `src/app/postt.jsx` | 375 × 812 | 3 |
| 4 | **Notify** | `src/app/notify.jsx` | 375 × 812 | 5 |
| 5 | **07-Profile** | `src/app/s-07-profile.jsx` | 375 × 814 | 9 |
| 6 | **PRODUCT DETAILS** | `src/app/product-details.jsx` | 375 × 960 | 4 |
| 7 | **02-category selction** | `src/app/s-02-category-selction.jsx` | 375 × 812 | 7 |
| 8 | **Location set** | `src/app/location-set.jsx` | 375 × 812 | 2 |
| 9 | **Cht** | `src/app/cht.jsx` | 375 × 814 | 1 |
| 10 | **postt** | `src/app/postt-2.jsx` | 375 × 812 | 2 |
| 11 | **postt** | `src/app/postt-4.jsx` | 375 × 812 | 2 |
| 12 | **07-Profile** | `src/app/s-07-profile-2.jsx` | 375 × 814 | 2 |
| 13 | **07-Profile** | `src/app/s-07-profile-5.jsx` | 375 × 814 | 1 |
| 14 | **07-Profile** | `src/app/s-07-profile-6.jsx` | 375 × 814 | 1 |
| 15 | **07-Profiles** | `src/app/s-07-profiles.jsx` | 375 × 814 | 2 |
| 16 | **07-Profile** | `src/app/s-07-profile-4.jsx` | 375 × 814 | 2 |
| 17 | **postt** | `src/app/postt-3.jsx` | 375 × 812 | 1 |
| 18 | **07-Profile** | `src/app/s-07-profile-3.jsx` | 375 × 814 | 2 |

Screenshots of every screen are in [`screenshots/`](./screenshots).

## 🧩 How it's built

- `src/screens/*.json`: each design artboard converted to screen data (vector shapes, gradients, image fills, masks, shadows, blurs and rich text, positioned as in the design), plus its tap targets
- `src/sketch/SketchScreen.jsx`: draws a screen at the device's width with `react-native-svg`, native `Text`/`TextInput` and `expo-blur`, and handles navigation between screens
- `src/app/`: Expo Router routes, one per artboard (`index.jsx` opens the start screen)
- `assets/images/`: images used by the design

## 🛠️ Tech Stack

- **Framework**: React Native 0.88+ / Expo SDK 58+
- **Navigation**: Expo Router (file-based routing)
- **Language**: JavaScript & JSX (`.js`, `.jsx`)
- **Rendering**: `react-native-svg`, `expo-blur`
- **Fonts**: Google Fonts via `@expo-google-fonts` (Inter, Montserrat, Open Sans, Poppins), standing in for the design's original fonts where those aren't free

<!-- run-locally:start -->

## ▶️ Run locally

```bash
npm install
npx expo start
```

Then press `i` for the iOS simulator, `a` for Android, or `w` for the web, or scan the QR code with Expo Go.

<!-- run-locally:end -->

<!-- developer:start -->

## 👨‍💻 Developer

This React Native app was developed by **Suresh Kumar Meesala**.

| | |
|---|---|
| Developer | [Suresh Kumar Meesala](https://github.com/SureshKumarMeesala) |
| GitHub | [@SureshKumarMeesala](https://github.com/SureshKumarMeesala) |
| Organization | [FreeAppSource](https://github.com/FreeAppSource) |
| Repository | <https://github.com/FreeAppSource/photo-marketplace-app> |

<!-- developer:end -->

---

<!-- design-credits:start -->

## 🎨 Design Credits

This app is based on the free **Photo App Concept** design by **2 Four**, downloaded from Sketch App Sources. All visual design credit goes to the designer. The screens are reproduced from the original Sketch file; fonts that aren't free are replaced with similar Google Fonts, so some details may differ slightly from the original.

| | |
|---|---|
| Designer | [2 Four](https://www.sketchappsources.com/contributor/twofour) |
| Original design | [Photo App Concept](https://www.sketchappsources.com/contributor/twofour) |
| Downloaded from | [Sketch App Sources](https://www.sketchappsources.com/free-source/4514-photo-app-sketch-freebie-resource.html) |
| Original file | `photo-app-2-four.sketch` |
| License / usage | Not stated on the page. Free download; give credit (Sketch App Sources Terms). Confirm with the designer before commercial use. |

**Attribution:**

> UI design: "Photo App Concept" by 2 Four (https://www.sketchappsources.com/contributor/twofour), downloaded from Sketch App Sources (https://www.sketchappsources.com/free-source/4514-photo-app-sketch-freebie-resource.html).

The original design source files are not included in this repository; get them from the links above. This app's **code** is released under the [MIT License](./LICENSE); the visual design remains the designer's (see [NOTICE](./NOTICE)).

Photos, brand logos and avatars inside the design may belong to third parties and are not covered by the designer's permission.

<!-- design-credits:end -->
