# my_web_profile

Personal portfolio site built with **Flask** and plain HTML/CSS.

Pages: home, about, works/work and contact. The contact form appends
submissions to `database.csv`.

## Run

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirment.txt
python server.py        # http://127.0.0.1:5000
```

## Layout

- `server.py` — Flask app and routes
- `templates/` — HTML pages
- `static/` — assets
- `database.csv` — contact-form submissions
