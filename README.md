# FastAPI mit UV

## Projekt einrichten

### 1. UV-Projekt initialisieren

```bash
uv init
```

### 2. FastAPI installieren

```bash
uv add "fastapi[standard]"
```

### 3. Server starten

```bash
uv run fastapi dev main.py
```

Der Server läuft dann unter http://127.0.0.1:8000

### 4. API testen

- Browser: http://127.0.0.1:8000
- Swagger UI: http://127.0.0.1:8000/docs

## Dateien

- `pyproject.toml` - Projektdefinition und Abhängigkeiten
- `uv.lock` - Lock-Datei mit exakten Versionen
- `main.py` - FastAPI Anwendung
