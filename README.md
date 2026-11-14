# bds

> **Status:** placeholder. This repository holds Streamlit's unmodified
> "blank app" starter template. No project-specific features exist yet.

The only app code is [`streamlit_app.py`](streamlit_app.py). It renders a title
and a link to the Streamlit docs.

## Project structure

```
.
├── streamlit_app.py           # Streamlit entry point (template page)
├── requirements.txt           # Python dependencies (streamlit)
├── .devcontainer/             # Dev Container / Codespaces config (Python 3.11)
├── .github/CODEOWNERS         # Inherited from the Streamlit template
└── LICENSE                    # Apache-2.0 (inherited from the template)
```

## Running locally

Prerequisites: Python 3.9+ and `pip`.

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
streamlit run streamlit_app.py
```

Streamlit serves the app at <http://localhost:8501>.

## Notes

- Secrets for Streamlit go in `.streamlit/secrets.toml`, which `.gitignore` already excludes.
- `.github/CODEOWNERS` still names `@streamlit/community-cloud` from the
  template. Change it to your own handle once the project grows.

## Credits

Generated from Streamlit's
[blank app template](https://github.com/streamlit/blank-app-template).
