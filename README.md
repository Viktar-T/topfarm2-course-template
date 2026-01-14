<div align="center">

# TopFarm2 Course Template

Beginner-friendly setup for working in GitHub Codespaces with VS Code (web), Jupyter notebooks, and GitHub Copilot.

[![Open in Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/)

</div>

## Repo naming (students)
Create your repo from this template and name it:
- `topfarm2-<surname>-<group>` (example: `topfarm2-lee-g3`)

## 1) Create your repo from this template
1. Click **Use this template** (top right on GitHub).
2. Choose **Create a new repository**.
3. Name it using the rule above. Make it **Public** (unless your instructor says otherwise).
4. Click **Create repository**.

## 2) Open a Codespace
1. In your new repo, click the **Code** dropdown.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main**. Wait ~1–2 minutes for setup.

## 3) Open and run the Lesson 1 notebook
1. In VS Code (web), open the Explorer sidebar.
2. Navigate to `notebooks/lesson1_hello_topfarm2.ipynb` and open it.
3. If prompted for a kernel, pick **Python 3.11**.
4. Run cells from top to bottom: click the **Run** triangle on each cell or press **Shift+Enter**.  
5. If a cell fails: read the red error, then **Restart kernel** (top-right) and **Run All**.

## 4) Add screenshots to `reports/lesson1.md`
1. Take two screenshots:
   - Notebook running in Codespaces (web).
   - Final layout plot after your changes.
2. Save images in the repo (e.g., `reports/img/`).
3. Edit `reports/lesson1.md` and add the image paths under **Screenshots**.
4. Example Markdown for an image you saved as `reports/img/layout.png`:
   - `![Final layout](reports/img/layout.png)`

## 5) Commit and push
1. In VS Code left sidebar, open **Source Control**.
2. Stage all changes.
3. Commit message example: `Add lesson1 notebook results`.
4. Click **Sync** (or **Push**) to upload to GitHub.

## 6) Submit
- Send **only** your GitHub repo link to your instructor.

## Troubleshooting (quick)
- If the kernel hangs or errors: **Restart kernel** → **Run All**.
- If imports fail: rerun the first import cell; ensure `pip install -r requirements.txt` finished.
- If plots don’t show: rerun the plot cell; scroll down—plots appear under the cell.
- If Codespaces feels slow: reload the browser tab; close unused tabs.

## Optional: Faster Codespaces (prebuilds)
- Instructors can enable prebuilds on the template to speed up first launch. Students don’t need to change anything if prebuilds are on.

## Files you must have
- `notebooks/lesson1_hello_topfarm2.ipynb` (run + edits)
- `reports/lesson1.md` (filled, with 2 screenshots)
- Screenshots stored in the repo (e.g., `reports/img/`)

## Grading rubric (quick)
- **2 points**: Notebook runs, experiments done, Copilot change described, 2 screenshots, report complete.
- **1 point**: Partial work; missing one required item or minor errors.
- **0 points**: Notebook not runnable or required items missing.

## What's inside
- `notebooks/` — Lesson notebooks for hands-on work.
- `reports/` — Student report templates to fill and submit.
- `data/` — (optional) place for datasets if provided.
- `.devcontainer/` — Codespaces setup (Python 3.11, Jupyter, Copilot, Pylance).
- `requirements.txt` — Python libraries used in notebooks.
- `.gitignore` — Keeps temporary files out of Git.
