# uv Skill

**How to use uv (the Python package manager) for all Python package management, environment management, project workflows, building, and publishing tasks. Use this skill whenever the user mentions uv, Python packages, dependencies, virtual environments, pyproject.toml, or wants to install/manage Python projects.**

uv is an extremely fast Python package manager written in Rust that replaces pip, pip-tools, pipx, poetry, pyenv, twine, and virtualenv. It's 10-100x faster than traditional tools.

---

## References

Detailed documentation is organized in the `references/` directory:

- [01-quick-start.md](references/01-quick-start.md) - Installation and common workflows
- [02-project-management.md](references/02-project-management.md) - init, add, remove, sync, lock, export, tree, version, audit, format
- [03-running-commands.md](references/03-running-commands.md) - uv run and PEP 723 scripts
- [04-tools.md](references/04-tools.md) - Global tool management (uvx, tool install/run/upgrade/list)
- [05-python-management.md](references/05-python-management.md) - Python installation and version management
- [06-virtual-environments.md](references/06-virtual-environments.md) - Virtual environment creation (uv venv)
- [07-pip-interface.md](references/07-pip-interface.md) - pip-compatible commands (install, sync, compile, freeze, etc.)
- [08-build-publish.md](references/08-build-publish.md) - Building and publishing distributions
- [09-authentication.md](references/09-authentication.md) - Authentication management
- [10-cache-management.md](references/10-cache-management.md) - Cache operations
- [11-self-management.md](references/11-self-management.md) - uv self update/version
- [12-configuration.md](references/12-configuration.md) - pyproject.toml, uv.toml, .python-version
- [13-workspaces.md](references/13-workspaces.md) - Workspace configuration and commands
- [14-environment-variables.md](references/14-environment-variables.md) - All UV_* environment variables
- [15-key-concepts.md](references/15-key-concepts.md) - Lockfiles, dependency groups, extras, sources, markers, etc.
