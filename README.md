# Control Plane

Layout
- web/            finished frontend (static)
- docs/BACKEND_PROMPT.md  prompt for an AI agent to build server.py + SQLite backend
- server.py       (to be generated from the prompt)

Preview frontend now (mock API, no backend):
    python -m http.server 8000 --directory web
    open http://127.0.0.1:8000/login.html   (any email, password >= 8 chars, any 6 digits)

After backend exists: set `mock:false` in web/js/config.js, then `python seed.py && python server.py`.
