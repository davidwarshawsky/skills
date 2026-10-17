# Install `deepwiki`

## Quick Install (Windows PowerShell)

```powershell
.\install.ps1
```

This script:
- Configures `PYTHONIOENCODING=utf-8` at the user level (persistent across sessions)
- Sets it for the current session (works immediately)
- Installs deepwiki via `uv tool`
- Verifies the installation

---

## Manual Installation

```bash
uv tool install git+https://github.com/davidwarshawsky/deepwiki
deepwiki --help
```

Alternatives:

```bash
uvx --from git+https://github.com/davidwarshawsky/deepwiki deepwiki --help
pipx install git+https://github.com/davidwarshawsky/deepwiki.git
pip install git+https://github.com/davidwarshawsky/deepwiki.git
```

Windows PowerShell:

```powershell
uv tool install git+https://github.com/davidwarshawsky/deepwiki
deepwiki --help
```
