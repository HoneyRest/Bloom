# Bloom

**Bloom** is a private, single-page **cycle-synced Pilates planner**—phases, workouts, and progress with **no backend, no login, and no database**.

## Contents of this folder

| File | Purpose |
|------|---------|
| `index.html` | The full app. |
| `bloom-icon.png` | Bookmark / home-screen icon. |
| `buyer-setup-guide.md` | Setup, privacy, backup, troubleshooting. |

## Static hosting (GitHub Pages)

1. Create a repository and upload **all files** from this folder to the **root**.
2. Enable **Pages** from branch **main**, folder **`/ (root)`**.
3. Share the generated `https://USERNAME.github.io/REPO/` URL with buyers.

### Local preview

```bash
python3 -m http.server 8080
```

Visit `http://localhost:8080/`.

## Privacy & data

**Private web app. No login, no subscription.** Data stays **in your browser** on the device you use.

**If you clear browser data or switch devices, export a backup first.**

## Icon

Replace **bloom-icon.png** with your branded square PNG if desired; keep paths in **index.html** in sync.
