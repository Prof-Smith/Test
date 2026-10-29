Option Pricer v3.0.2 calculation-display hotfix

Replace docs/app.js and docs/index.html in the repository with these files, commit, and push to main.

Changes:
- Adds a prominent recalculated-results strip for CRR, BSM benchmark, intrinsic value, time value, p*, and market difference.
- Displays caught calculation errors instead of leaving blank panels.
- Keeps numerical results visible if Plotly fails to load.
- Adds automatic recalculation after input changes, while retaining the Recalculate button.
- Adds cache-busting v3.0.2 asset references.
