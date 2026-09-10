👋 Hi, I'm Benjamin Trendelkamp-Schroer (@btschroer). I lead the **PCSA** team (portfolio construction, simulation, and analytics) at [Ultramarin](https://ultramarin.ai).

Before PCSA I worked in the Selection team, which is still where most of my commits are.

## Repos PCSA owns

| Repo | What I can help with |
|---|---|
| `backtest` | Axioma optimiser integration; constraint modelling — active weights per issuer, industry, and benchmark, leverage, ADV and trading-volume limits, relaxations, reachable bounds; Prefect flows that ingest Axioma derby deliveries; releases |
| `apa-proxy` | Running APA reports: portfolio identifiers, license server, concurrency |
| `ultramarin-uilabs-client` | Prefect ingest flows — SFTP and NFS deliveries, raw → staging hive partitions, deployments |
| `ultramarin-metrics`, `ultramarin-metrics-plugins` | I wrote much of the original metrics library, so I can explain why it is shaped the way it is. @markounikau-ultramarin owns it now and knows the current code |

## Where else I've spent time

**`selection`** (2024–2026, my main repo before PCSA)
- Alpha features: reversal and trend, risk, analyst estimates, earnings-call/TDA, short interest and stock loan
- The lazy `ExecutionGraph` feature engine and the feature client
- Cross-sectional and Fama-MacBeth models, time-series splitting, SHAP and model insights
- The migrations: pandas → polars, pydantic v1 → v2, conda → pixi, fsspec I/O, mypy

**Platform and CI**
- `infrastructure` — GKE node pools, Prefect server and work pools, buckets, service accounts, Terraform
- `ultramarin-client-core`, `action-auth-gcp` — service auth: IAP, OIDC ID tokens, GitHub → GCP Workload Identity Federation
- Supply chain: moving workflows off long-lived keys, SHA-pinned Actions, Dependabot, image scanning

## Ask me about

Why an optimisation is infeasible or a constraint behaves unexpectedly. How a feature is computed and where its data comes from. Whether a backtest result is trustworthy. How to get a Prefect flow deployed. How a repo authenticates to GCP.

Tag me on a PR, open an issue, or ping me on Slack. Half-formed questions are welcome — I would rather talk early than review a rewrite.
