# purplerain

## 📑 Project Documentation
For a detailed breakdown of goals, milestones, and technical requirements, please refer to the official project plan:
- **[Project Plan Document](https://docs.google.com/document/d/1RGcGkZOCT4o82sTc0dEztuPdRH4IaqqFcgrrK5VMRwA/edit?tab=t.0)**

## WIP Items
- **[Weekly Reflection #1](https://docs.google.com/document/d/189fmn751rzRS7JZok5fnFov3hEypNOJ-mbh3aNaxpiU/edit?tab=t.0)**
- **[Video Update Slideshow](https://docs.google.com/presentation/d/1pVHoRLjgGMjIAV1Io36SoTaroasC2D2w7Rd8RtaDfx0/edit?slide=id.g3c4e4db0526_1_0#slide=id.g3c4e4db0526_1_0)**
- **[Colab Workspace](https://colab.research.google.com/drive/1qp1Ox-pQSeDY5qkCfzjStaqSGTYO4pCI?authuser=1#scrollTo=s2QoMS8kZor8)**

---

## 🛠 Development Workflow

This project follows a standard branching strategy to maintain code integrity and stable deployments.

### Branch Specifications

| Branch | Purpose | Stability |
| :--- | :--- | :--- |
| `main` | Production-ready code. Only merged from `development`. | Stable |
| `development` | Integration branch for features. | Testing/Beta |
| `feature/*` | Individual features or task-specific work. | Work-in-Progress |

### Git Workflow
1. **Feature Creation:** Branch off from `development` using the naming convention `feature/your-feature-name`.
2. **Commit Often:** Use clear, concise commit messages.
3. **Keep it Updated:** Periodically pull the latest changes from `development` into your feature branch to resolve conflicts early.

---

## 🚀 Pull Request (PR) Instructions

Before submitting a PR, ensure your code follows the project's style guidelines and passes any local tests.

1. **Target Branch:** All feature PRs should target the `development` branch.
2. **PR Template:**
    * **Description:** What does this PR do?
    * **Related Docs:** Link back to specific sections of the [Project Plan](https://docs.google.com/document/d/1RGcGkZOCT4o82sTc0dEztuPdRH4IaqqFcgrrK5VMRwA/edit?tab=t.0).
    * **Screenshots/Logs:** (If applicable) Provide visual proof of the fix or feature.
3. **Review:** A minimum of one peer review is required before merging.

---

## ⚙️ Setup & Installation

*Coming soon...*

> **Note:** Direct commits to the `main` or `development` branches are restricted. Please use the PR process described above.
