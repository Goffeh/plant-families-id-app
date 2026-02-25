# 🌿 Plant Families of the World ID App

A mobile-friendly, offline-capable web app for identifying plant families by their characteristics. Built for botanists, students, and plant enthusiasts who want a fast and flexible field reference tool.

Made by **Goffe Hoving**.

---

## 🌐 Live App

> _Add your GitHub Pages link here once deployed, e.g.:_  
> https://yourusername.github.io/plant-families-id-app/

---

## 📱 Features

- **Search by multiple characteristics** — growth form, leaf type, flower parts, stamen count, fruit type, distribution, reproductive strategy, dispersal method, and uses
- **Dropdown + free text search** — select from pre-loaded options or type your own keywords
- **Multi-filter support** — all filters work together; results must match every criterion
- **Expandable family cards** — click any result to reveal full details
- **Works fully offline** — once loaded, no internet connection is needed (PWA)
- **Installable** — can be added to your phone's home screen like a native app
- **Dark mode** — toggle between light and dark themes
- **Your own data** — load any CSV file with plant family data; saved locally in your browser

---

## 🚀 How to Use

1. Open the app in your browser
2. Paste or upload your CSV data file on the start screen
3. Click **Save to Browser** to store it for offline use
4. Use the search filters to narrow down plant families by characteristics
5. Click a family card to expand it and see full details
6. Use **Show All Families** to browse the complete list

### Search tips

- **Numbers in flower characteristics** (e.g. `5`) match petals/sepals/tepals/merosity. Other counts like lobed styles are written out as words (e.g. `three lobed style`).
- **Stamen numbers** should be typed with a trailing comma (e.g. `5,`) to avoid false matches with `15` or `50`.
- **Fruit carpel and seed counts** are written out as words in the data (e.g. `three carpels`, `five seeds`).
- **Distribution** reflects native occurrences only — introduced or cultivated ranges are not included.
- Click the **+** button next to any field to add up to 5 search boxes per characteristic.

---

## 📂 CSV Data Format

The app expects a CSV file with the following column headers:

| Column | Description |
|---|---|
| `Family` | Family name (e.g. Fabaceae) |
| `Order` | Order name |
| `Group` | Clade or group (e.g. Eudicots) |
| `Sp. estimate` | Approximate number of species |
| `Common genera` | Example genera |
| `Growth Form` | Growth habit and structure |
| `Leaf Characteristics` | Leaf shape, arrangement, texture, etc. |
| `Flower Characteristics` | Floral structure, colour, symmetry, merosity |
| `Stamen Characteristics` | Number and arrangement of stamens |
| `Fruit Characteristics` | Fruit type, carpel count, seed count |
| `Distribution` | Native geographic range |
| `Reproductive Strategy` | Pollination method |
| `Common Dispersal Type` | Seed/fruit dispersal mechanism |
| `Two extremes` | Example species showing variation |
| `Uses/other info` | Economic uses and notable features |

---

## 🗂️ Repository Contents

| File | Purpose |
|---|---|
| `index.html` | Main app — all HTML, CSS, and JavaScript in one file |
| `manifest.json` | PWA manifest for installability and home screen support |
| `service-worker.js` | Enables offline caching |
| `icon-192.png` | App icon (192×192px) |
| `icon-512.png` | App icon (512×512px) |

---

## 🛠️ Deployment (GitHub Pages)

1. Push all files to a GitHub repository
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and click **Save**
4. Your app will be live at `https://yourusername.github.io/your-repo-name/`

---

## 📄 License

Feel free to use and adapt this app for personal or educational purposes. If you share a modified version, a credit to the original author (Goffe Hoving) is appreciated.
