<div align="center">

# CMD-cURL

A collection of Windows Batch scripts that stream ASCII art animations in your terminal using the Windows built-in `curl` command.

</div>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Requirements

- Windows 10 version 1803 or later (curl is included by default)
- Active internet connection

## Animations

| Script | Animation |
|---|---|
| `Donut.bat` | Spinning 3D donut |
| `Forrest.bat` | Forrest Gump running |
| `Globe.bat` | Rotating globe |
| `Nyan.bat` | Nyan Cat |
| `Parrot.bat` | Party parrot |
| `Rick.bat` | Rick Astley |

## Installation

```bash
git clone https://github.com/sha-wrks/CMD-cURL.git
cd CMD-cURL
```

## Usage

Double-click any `.bat` file, or run it from the command line:

```cmd
Rick.bat
```

Press `Ctrl+C` to stop the animation.

## How It Works

Each script calls `curl ascii.live/<name>`, which streams an ASCII art animation over HTTP directly to your terminal. No external binaries or additional dependencies are required beyond the system curl bundled with Windows 10 and later.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## Security

See [SECURITY.md](SECURITY.md) for the security policy and vulnerability reporting process.

## License

MIT. See [LICENSE](LICENSE) for details.
