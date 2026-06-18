# Setup Guide — GitHub Profile README

This folder is designed for the special GitHub profile repository:

```text
Reinhrd / Reinhrd
```

## 1. Create the profile repository

Create a **public** repository named exactly:

```text
Reinhrd
```

GitHub will recognize it as your Profile README repository because the repository name matches your username.

## 2. Upload the files

Upload:

```text
README.md
.github/workflows/snake.yml
```

Keep the same folder structure.

## 3. Activate the animated contribution snake

1. Open the repository on GitHub.
2. Go to **Settings → Actions → General**.
3. Under **Workflow permissions**, choose **Read and write permissions**.
4. Save.
5. Go to the **Actions** tab.
6. Open **Generate Contribution Snake**.
7. Choose **Run workflow**.

The workflow creates an `output` branch containing the animated SVG files. Once the workflow completes, the snake section in `README.md` will appear automatically.

## 4. Optional personalization

You can update these items inside `README.md`:

- Name in the animated introduction.
- Short professional positioning.
- Project names and descriptions.
- Social/contact badges.
- Technology icons.
- Colors used in badges and activity graphs.

## 5. Why some widgets may initially look blank

GitHub statistics, language cards, activity graphs, and the contribution snake depend on external services or GitHub Actions. They may need a few minutes after your first commit or first workflow run to render.

## 6. Recommended pinned repositories

Pin 4–6 repositories on your profile:

1. Smart Workshop Intelligence
2. NSSS Price-Time Reversal Lab
3. A machine-learning classification project
4. A time-series / forecasting project
5. A data-visualization or Tableau project

This makes the profile README and your actual work reinforce each other.
