Using uv:
```
curl -LsSf https://astral.sh/uv/0.9.5/install.sh | sh
uv run litestar -h
```

Using pip:
```
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
litestar -h
```

Using docker:
```
docker build . -t litestar-4449-repro
docker run --rm litestar-4449-repro
```
