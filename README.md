# Cave Explorer

PyGame + PyGbag PC game.

### features

- WASD motion controls, long-press enabled
- ESC to quit
- Fog of war hides the map
- Player spreads light in a small radius
- Stepping into a new cave increases map scale
- Caves are auto-generated

### deploy virtual environment

```bash
python -m venv venv
```

Activation for **windows**:

```bash
venv/scripts/activate
```

### install libraries

```bash
pip install -r requirements.txt
```

### run pygame

```bash
python game/main.py
```

### build html

```bash
pygbag --build game
```
