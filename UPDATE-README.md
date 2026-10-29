# Option Pricer v3 Update

Copy the contents of this package into the repository root, preserving paths. Commit and push to `main`. The GitHub Actions workflow will execute the existing notebook, enrich `docs/model_results.json`, and deploy the updated dashboard.

## Included enhancements
- Interactive CRR contract sandbox with reset to validated notebook values
- Delta, gamma, vega, theta, and rho using CRR finite differences
- Spot-volatility sensitivity heat map and downloadable CSV
- Lattice convergence chart with market bid-ask range
- CRR, Black-Scholes-Merton benchmark, belief value, and market comparison
- Expandable evidence for theoretical bounds, put-call parity, risk-neutral probability, and convergence
- Horizon-alignment warning using `horizon_months`
- Model-risk stress panel
- Source-provenance table from `data/source_documentation.csv`
- Build metadata and Git commit identifier
- Responsive and keyboard-accessible controls

## Important
The browser sandbox is exploratory. The executed notebook and its generated JSON remain the source of record. The enhancement script does not overwrite notebook calculations; it only appends horizon, source, and build metadata.
