# OBD-Data-Logger

Setting environment:

Download VS code
Download stm32 extension - includes STMCube
Download GitHub extension and login
Download Claude and link it to VS code
Download Git - https://git-scm.com/install/windows

git config --global user.name "name name"
git config --global user.email "email@email.com"

Confirm that git --version is installed

Control shift P -> git: clone and paste the GitHub repo

## Environment setup (Windows)

1. Install Git: https://git-scm.com/install/windows
2. Configure Git identity:
   ```
   git config --global user.name "Your Name"
   git config --global user.email "you@example.com"
   git --version
   ```
3. Install VS Code.
4. Install STM32CubeMX (separate download from st.com; use the same version on every machine).
5. In VS Code, install the **STM32Cube for VS Code** extension pack (it fetches CMake, Ninja, the ARM GCC toolchain and the ST-LINK GDB server on first build).
6. Install the ST-LINK USB driver if the board isn't detected.
7. Install the Claude Code VS Code extension and sign in.
8. Clone: `Ctrl+Shift+P` → **Git: Clone** → paste the repo URL. Sign in to GitHub when prompted.

## Daily workflow

- `git pull` before starting work
- `git add -A`, `git commit -m "..."`, `git push` when done