Testing out CICD for compilation of `.au3` and `.py` files to `.exe`.

CICD `.yaml` does:

- `detect-changes` which finds all files to compile
- `build` which compiles `.py` using pyinstaller or `.au3` using autoit compiler
- `create-release` which packs all `.exe` files to `.zip` under a gh release
