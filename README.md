# ImGui Builder

A **no-code UI builder** for [Dear ImGui](https://github.com/ocornut/imgui). Lay out windows and widgets visually — no C++ written by hand — then export the result into your project.

<img width="2007" height="1152" alt="изображение" src="https://github.com/user-attachments/assets/43b8d12e-0f47-4137-ba6a-442c25655b17" />



## Features

- **Visual layout** — drag and arrange widgets in a tree instead of typing code.
- **Live preview** — the editor canvas renders the real ImGui output as you work.
- **Property inspector** — edit labels, sizes, flags and layout options per widget.
- **Widget library** — buttons, checkboxes, sliders, combos, tabs and containers.
- **Code export** — generate ready-to-paste ImGui source from your layout.
- **Lightweight** — a single native executable, no runtime dependencies.

## How to build

Building is a one-step process. **Run `build.exe`** from the repository root:

```bat
build.exe
```

That's it — the script configures the toolchain, compiles the project and leaves the binary in the build output folder. No CMake invocation or manual dependency setup is required.

> **Note:** if the build fails, delete the build output folder and run `build.exe` again to force a clean configure.

### Requirements

| Requirement | Details |
| --- | --- |
| OS | Windows 10 / 11 (64-bit) |
| Toolchain | Installed by `build.exe` if missing |
| Disk space | ~100 MB for intermediate build files |

## Usage

1. Run the built executable.
2. Add widgets from the library into the layout tree.
3. Select a widget and tune its properties in the right-hand panel.
4. Check the result in the live preview.
5. Export the generated ImGui code and paste it into your project.
