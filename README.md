# ScamLens — Digital Safety Scanner

A responsive, frontend-only educational cybersecurity prototype.

## Included features
- Message scanner with explainable pattern-based indicators
- URL structure inspection (does not visit submitted URLs)
- Heuristic warning score (not a probability)
- Local scan history with CSV export and clear-history option
- Scam safety academy and interactive quiz
- Responsive dark cybersecurity interface
- Custom SVG favicon
- Functional in-page navigation and official safety-resource links
- No backend, database, API key, package installation or build step

## Run locally
Open `index.html` in a modern browser. Alternatively, run a local server:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Deploy to GitHub Pages
1. Create a GitHub repository, e.g. `scamlens`.
2. Upload **all four files** (`index.html`, `style.css`, `app.js`, `favicon.svg`) and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for deployment. Your website will be available at `https://YOUR-USERNAME.github.io/scamlens/`.

Keep the files together in the same folder. The relative asset paths are configured for a GitHub Pages project site.

## Important limitations
- This is a heuristic pattern-matching demo, not a trained AI model.
- It does not connect to live threat-intelligence, malware scanning, URL reputation or domain registration services.
- It cannot verify sender identity or prove that a message or URL is safe.
- Scores are illustrative warning indicators, not probabilities of fraud.
- A low score does not mean a message or URL is safe.
- History is stored in the current browser's LocalStorage. It is not synced between devices.
- Do not enter real passwords, OTPs, banking details or other sensitive information.
- Do not put secret API keys in a GitHub Pages frontend. For future AI/API integration, use a secure server-side proxy.

## India cybercrime resources
- National Cyber Crime Reporting Portal: https://cybercrime.gov.in/
- Financial cyber fraud helpline: 1930
- CERT-In: https://www.cert-in.org.in/
- Reserve Bank of India: https://www.rbi.org.in/

## Stack
HTML5 · CSS3 · Vanilla JavaScript · LocalStorage · GitHub Pages
