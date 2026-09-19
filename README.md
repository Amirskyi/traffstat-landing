# TraffStat

TraffStat landing page — global traffic & media buying infrastructure for Gambling, Betting, and Crypto.

## Structure

```
Traffstat/
├── index.html          # homepage
├── img/
│   ├── logo.png        # header logo
│   ├── logo-full.png   # full logo (fallback asset)
│   └── watermarked_img_10434291128467773460.jpg  # background image
├── README.md
└── .gitignore
```

## Local preview

Open `index.html` in a browser or start a simple server from the project root:

```bash
python3 -m http.server 8080
```

The site will be available at `http://localhost:8080`.

## Publishing on GitHub Pages

1. Create a GitHub repository and upload this folder.
2. In Settings → Pages, select the `main` branch and the `/ (root)` folder.
3. After deploy, the site will open at `https://<username>.github.io/<repo>/`.
