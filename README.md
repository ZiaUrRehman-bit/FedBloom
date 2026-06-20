# FedBloom — No-Code Federated Learning

FedBloom is a desktop application for building, training, and deploying
federated learning experiments without writing code. It's aimed at people
who have data worth protecting — clinicians, bankers, researchers — and
want federated learning's privacy benefits without needing a machine
learning engineering team to get there.

🌐 **Website:** https://ziaurrehman-bit.github.io/FedBloom/
📦 **Download:** see [Download](#download) below
📖 **Source / docs:** this repository (private — the public
[ziaurrehman-bit/FedBloom](https://github.com/ziaurrehman-bit/FedBloom) repo hosts only the
website and release binaries)

---

## What it does

- **Simulate** federated learning locally with virtual clients, or **deploy**
  for real across machines on your LAN, over Tailscale, or via public
  IP / port forwarding.
- **30+ built-in models** — MLP, CNN, ResNet-18 and 9 more torchvision
  architectures, Logistic Regression, Linear SVM, Decision Trees, Random
  Forest, XGBoost, LightGBM, CatBoost, Naive Bayes, TabNet, Wide & Deep,
  and more.
- **17+ built-in datasets** (MNIST, CIFAR-10, Adult Income, Iris, Wine,
  Breast Cancer, and more) — or bring your own CSV or image dataset.
- **Data Pre-processing workbench** — explore, clean, normalise, encode,
  and export your data before it ever touches a training run, available
  on both the server and client side.
- **Differential Privacy** (DP-SGD via Opacus) and robust aggregation
  (FedAvg, FedProx, Krum) — raw data never leaves the client machine.
- **Federated unlearning** (simulation) — a client can ask the server to
  forget specific records it contributed, without retraining every other
  client from scratch.
- **Hyperparameter optimisation**, live metrics (accuracy, loss, ROC,
  convergence, per-client resource usage), and built-in server↔client chat.
- Resilient real deployments: training can proceed with fewer clients than
  expected, and the operator is notified (with the option to continue
  automatically) if a client disconnects mid-round.
- Dark and light themes, role-aware dashboards for Server and Client modes.

## Download

Pre-built Windows installers are published as
[GitHub Releases](https://github.com/ziaurrehman-bit/FedBloom/releases) on the public
distribution repo.

```
https://github.com/ziaurrehman-bit/FedBloom/releases/latest/download/FedBloom-Setup.exe
```

**System requirements:** Windows 10/11 (64-bit), 4-core CPU, 4 GB RAM
minimum (8 GB recommended). No Python installation required — the
installer bundles everything. macOS/Linux support is planned.

> No release has been published yet — this link will go live the moment
> the first `FedBloom-Setup.exe` is attached to a release.

## License

MIT — see the website footer for details.

## Author

**Zia ur Rehman** — ML / FL Researcher & Software Engineer
[GitHub](https://github.com/ZiaUrRehman-bit) · engrziaurrehman.kicsit@gmail.com
