# mujoco-experiments

A collection of physics simulation experiments built with
[MuJoCo](https://mujoco.org), the multi-joint dynamics engine for robotics,
biomechanics, and control research.

## Setup

Requires [uv](https://docs.astral.sh/uv/) and Python 3.12.

```bash
git clone git@github.com:mpeyrard/mujoco-experiments.git
cd mujoco-experiments
uv sync
```

Verify the install:

```bash
uv run python -c "import mujoco; print(mujoco.__version__)"
```

## Dependencies

| Package | Purpose |
| --- | --- |
| `mujoco` | Physics engine and Python bindings |
| `numpy`, `scipy` | Numerics and control math |
| `glfw`, `pyopengl` | Interactive viewer and OpenGL rendering |
| `imageio`, `mediapy` | Rendering frames to images and video |
| `matplotlib` | Plotting simulation data |

## Project layout

```
src/mujoco_experiments/   # experiment code
pyproject.toml            # project and dependency definitions
```

## Experiments

_None yet. Experiments will be listed here as they are added._

## License

[MIT](LICENSE)
