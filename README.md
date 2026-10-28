# Helios Election System

Helios is an end-to-end verifiable voting system.

[![Travis Build Status](https://travis-ci.org/benadida/helios-server.svg?branch=master)](https://travis-ci.org/benadida/helios-server)

[![Stories in Ready](https://badge.waffle.io/benadida/helios-server.png?label=ready&title=Ready)](https://waffle.io/benadida/helios-server)

## Repository layout

* `backend/` - Django server (Python): apps `helios`, `helios_auth`, `server_ui`, settings, dependencies (`pyproject.toml`).
* `frontend/` - Templates, CSS/JS/images, voting booth and verifier. The server finds this folder through the `FRONTEND_PATH` setting (default: `frontend/` next to `backend/`).

See `INSTALL.md` for setup.
