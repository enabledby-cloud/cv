# enabledby.cloud - CV

> Automated CV generation using RenderCV

This repository contains my CV as code, automatically built and deployed via GitHub Actions.

## 📄 View CV

The latest version is available at the **[branch cv-pdf](https://github.com/enabledby-cloud/cv/blob/cv-pdf/Marvyn-Stephano_Zalewski_CV.pdf)**.

## 🛠️ Technology

Built with [RenderCV](https://github.com/rendercv/rendercv) - a CV generator that creates awesome CVs from datastructures.

If you find RenderCV useful, consider [⭐ starring the project](https://github.com/rendercv/rendercv) to show your support!


## 🚀 Automated Pipeline

Every push to `main` automatically:
1. Validates the CV YAML schema
2. Renders the CV in multiple formats
3. Deploys to GitHub Pages

## 📝 Source

The CV content is defined in [cv.yaml](cv.yaml).

## 📜 License

See [LICENSE](LICENSE).