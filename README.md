# Linker

VB6 Linker (`Linker.exe`) that expects a file path on the command line, strips quotes, and opens it with `ShellExecute` using `%ALLUSERSPROFILE%` as the working directory (exits immediately if no argument). Open `Linker.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Linker` (`Linker.vbp`) | VB6 | WinForms exe | Linker |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Linker.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Linker`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
