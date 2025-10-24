Using uv:
1. `curl -LsSf https://astral.sh/uv/0.9.5/install.sh | sh`
1. `uv run litestar -h`

Using pip:
1. `python3 -m venv .venv`
1. `source .venv/bin/activate`
1. `python3 -m pip install -r requirements.txt`
1. `litestar -h`

Using docker:
1. `docker build . -t litestar-4449-repro`
1. `docker run --rm litestar-4449-repro`
