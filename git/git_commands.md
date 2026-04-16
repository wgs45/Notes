# 🌌 GitHub CLI & Workflow Mastery

---

## 💠 Intuition — Why This Matters

> [!NOTE]
> Modern development is not just coding — it’s **orchestrating systems**. Git + GitHub CLI transforms your terminal into a **control center** for CI/CD, collaboration, and deployment.

- 📡 Replace browser clicks with **terminal-native workflows**
- ⚡ Reduce friction → faster iteration cycles
- 🔒 Enforce safety via **branch protection + CI gates**

---

## 🧪 Formal Logic — Core System Components

### 💠 GitHub CLI “Big Three” (Execution Control)

> [!IMPORTANT]
> These commands form your **CI/CD observability loop**.
>
> | Command        | Role                  | Mental Model   |
> | -------------- | --------------------- | -------------- |
> | `gh run list`  | View recent runs      | 📊 Dashboard   |
> | `gh run watch` | Monitor live progress | 📡 Live Stream |

## | `gh run view --log` | Inspect failures | 🔍 Debug Console |

### 💠 Secrets Management (Secure Vault)

> [!IMPORTANT]
> Never commit sensitive data — treat secrets as **externalized config**.
>
> | Command                   | Purpose      | Security Behavior |
> | ------------------------- | ------------ | ----------------- |
> | `gh secret set MONGO_URI` | Store secret | 🔒 Hidden value   |

## | `gh secret list` | List names only | 👁️ No exposure |

### 💠 Pull Request Lifecycle (Controlled Merge Flow)

> [!IMPORTANT]
> PRs enforce **quality gates before merging to main**.
>
> | Command                | Role       | Outcome              |
> | ---------------------- | ---------- | -------------------- |
> | `gh pr create --fill`  | Open PR    | 🚀 Fast creation     |
> | `gh pr checks --watch` | Monitor CI | ⏳ Safe merge timing |

## | `gh pr merge --merge --delete-branch` | Merge + cleanup | 🧹 Clean repo |

### 💠 Local Pre-Flight Checks (Cost Optimization)

> [!NOTE]
> Catch errors **before CI/CD runs** to save time & compute.
>
> | Command      | Purpose          | Benefit                   |
> | ------------ | ---------------- | ------------------------- |
> | `pnpm build` | Compile check    | ⚡ Prevent build failures |
> | `pnpm lint`  | Style validation | 🧹 Clean codebase         |

## | `act` | Run GitHub Actions locally | 💸 Zero CI cost |

## 🔄 Workflow — End-to-End Dev Cycle

```bash
# 1. Create feature branch
git checkout -b fix-errors   # isolate changes safely
# 2. Stage & commit
git add .
git commit -m "my actual fix"   # meaningful commit history
# 3. Push to remote branch
git push origin fix-errors   # triggers CI/CD
# 4. Create Pull Request
gh pr create --fill   # auto-fill from commit message
# 5. Monitor CI/CD
gh pr checks --watch   # wait until safe to merge

```

System Impact: Establishes a safe, observable, and automated delivery pipeline from local code → production.

⸻

🛠️ Tooling — Repository Hardening

🔒 Branch Protection Rules

[!IMPORTANT]
Treat main as production infrastructure, not a playground.

- 🚫 Disable admin bypass → no direct overrides
- 🧱 Require PRs for all changes
- ✅ Enforce CI checks before merge

⸻

🧪 GitHub Actions (Automation Engine)

[!NOTE]
CI/CD is defined declaratively via YAML.

```yaml
name: CI Pipeline
on:
push:
branches: - main
pull_request:
branches: - main

jobs:
deploy:
if: github.ref == 'refs/heads/main'
runs-on: ubuntu-latest
steps: - uses: actions/checkout@v3 # clone repo - run: pnpm install # install deps - run: pnpm build # build app - run: pnpm lint # lint check

```

System Impact: Converts your repo into a self-testing, self-validating system.

⸻

⚡ Optimization — High-Leverage Practices

- ⚡ Always run local checks first → avoid wasted CI minutes
- 📡 Use gh run watch immediately after push → instant feedback loop
- 🔍 Debug failures via CLI → no context switching
- 🔄 Keep branches short-lived → faster merges, fewer conflicts
- 🔒 Store all secrets in GitHub → never .env in repo

⸻

🏁 System Takeaways

[!IMPORTANT]
Think like a System Architect, not just a coder.

- 💠 GitHub CLI = terminal control plane
- 🔄 PR workflow = quality gate system
- 🔒 Secrets + branch protection = security layer
- ⚡ Local checks = cost + time optimization
- 🧪 GitHub Actions = automation backbone
