# Professional Talks & Workshops

A collection of artifacts, presentations, code samples, and resources from professional speaking engagements, workshops, and technical training sessions I have led.

## 📂 Content Index

| Topic / Talk Title |  Materials |
| :--- |  :--- |
| **Advanced Git Workflows** |  [View Folder](./git_workflows) |
| **AI Browsers** |  [View Folder](./ai_browsers) |

---

## 🏗 Repository Structure

Each folder typically contains:
* **Slides:** Jupyter Notebooks
* **Resources:** Additional artifacts (most often pictures) linked in slides deck.

To serve the presentation locally, navigate the appropriate directory and run the following command:
```
uv run jupyter nbconvert --to slides prez.ipynb --post serve --SlidesExporter.reveal_scroll=True
```

Please note that due to [this bug](https://github.com/jupyter/nbconvert/issues/78#issuecomment-1971661873), you need to not be in full screen mode for the scroll feature to work!