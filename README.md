# Atlas — Insurance Financial Asset Intelligence

A free, responsive, static GitHub Pages portfolio-management **demonstration** created for Wenting Wang. No account, paid API, backend, build tools, framework, or installation is required.

## Launch on GitHub Pages

1. Create a public repository on GitHub (for example `insurance-asset-portal`).
2. Upload `index.html`, `styles.css`, and `app.js` to the **repository root**. You may optionally upload this README and `.nojekyll`.
3. In **Settings → Pages**, under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then **Save**.
4. Visit `https://YOUR-USERNAME.github.io/insurance-asset-portal/` after GitHub finishes deployment.

You can also open `index.html` in any current desktop or mobile browser, or run `python -m http.server 8000` from this folder and browse to `http://localhost:8000`.

## Included features

- Executive portfolio dashboard with metrics, a sample trend, allocation breakdown, and holdings table
- Asset holdings registry with search, class filter, adding sample holdings, and CSV export
- Analytics and reporting: weighted yield, book vs market value, exposure charts, CSV extracts
- Investment transactions and cash dashboard with sample transaction entry and CSV export
- Asset–liability coverage comparison with editable liability assumption
- Risk, policy, and regulatory-readiness checklist
- Asset allocation and insurance investment-strategy roadmaps
- Documents and reports download center
- Locally operated keyword-based assistant supporting questions about the currently loaded sample data
- Responsive mobile navigation and accessibility labels
- Browser localStorage persistence and one-click demo reset

## Critical limitations

**Illustrative data only.** All portfolio holdings, returns, valuation prices, claims liabilities, credit ratings, and transactions are fictional. The trend chart is an illustration, not a historical time series. Weighted yield is a simple market-value-weighted estimate, not projected investment income. Transaction entry is a ledger demonstration; it does not alter holdings or perform real trades.

**Not a real AI service.** The chatbot uses local predefined logic and is not connected to a language model or retrieval database. This ensures a fully free, keyless deployment.

**Not production secure.** Public GitHub Pages cannot safely host sensitive insurer account data, serve authenticated banking/insurance workflows, hold private API keys, or provide regulated audit controls. localStorage is unencrypted client-side browser storage. Do not enter real confidential or regulated information. For production, implement secure SSO/MFA and RBAC, audited APIs, custody feeds, data validation, observability, encryption, governance, and a private AI integration.

## Project structure

- `index.html` — application layout and assistant shell
- `styles.css` — responsive layout and styling
- `app.js` — client-side navigation, sample data, charts, CSV download, local persistence, and demo assistant
- `.nojekyll` — bypasses Jekyll when published with GitHub Pages

Author branding: **Wenting Wang**.
