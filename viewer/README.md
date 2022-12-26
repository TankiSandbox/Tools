# Tanki Viewer

### Commands

| Key      | Description                  |
|----------|------------------------------|
| Escape   | Exit program.                |
| Tab      | Toggle wireframe.            |
| R        | Reset.                       |
| I        | Show/hide information.       |
| H        | Show/hide hull.              |
| T        | Show/hide turret.            |
| ZXC      | Rotate turret.               |

### Camera movement

| Key      | Description                  |
|----------|------------------------------|
| WASD     | Move camera.                 |
| QE       | Move camera upward/downward. |
| Scroll   | Increase/decrease fov.       |
| Mouse    | Look around                  |

### How to add a new paint

1. Create a new directory with the name of the paint inside `resources/paints/standard`.
2. Copy the paint with filename `paint.jpg` to this new directory.
3. Add a new entry between the `<standard>` tags in the `config.xml`. E.g.:
   `<paint name="my_paint" />` the name attribute should match with the
   name of the directory created in step 1.
