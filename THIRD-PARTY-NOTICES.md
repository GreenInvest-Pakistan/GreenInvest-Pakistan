# Third-party and open-source notices

The GreenInvest Windows package contains open-source runtime components. Those
components remain governed by their own licences; their inclusion does not
license GreenInvest's proprietary application model or source code.

## Principal components

- **CPython 3.13** — Python Software Foundation licence and historical terms.
- **Qt 6.11.2, PySide6 6.11.2, and Shiboken6 6.11.2** — distributed by
  GreenInvest under GNU LGPL version 3 using separate dynamically linked
  libraries.
- **Qt WebEngine / Chromium-derived components** — Chromium BSD licence and the
  third-party notices supplied with the WebEngine resources and source.
- **PyInstaller** — GPLv2-or-later with its exception permitting distribution
  of non-free applications built with PyInstaller.
- **Python dependencies** — their exact versions and wheel-supplied licence
  files are included in the release ZIP's `THIRD-PARTY-LICENSES` directory.

## Qt/PySide recipient rights

The unmodified LGPL-covered shared libraries are stored separately under the
release's `_internal/PySide6` and `_internal/shiboken6` directories. A recipient
may extract the package and replace them with ABI-compatible, recipient-built
versions. GreenInvest does not prohibit reverse engineering required to debug
changes to those LGPL-covered components.

Exact corresponding source locations:

- [Qt 6.11.2 source modules](https://download.qt.io/official_releases/qt/6.11/6.11.2/submodules/)
- [Qt WebEngine 6.11.2](https://github.com/qt/qtwebengine/tree/v6.11.2)
- [Qt WebEngine Chromium 146-based source](https://github.com/qt/qtwebengine-chromium/tree/146-based/chromium)
- [PySide6 and Shiboken 6.11.2](https://github.com/qtproject/pyside-pyside-setup/tree/v6.11.2)
- [Qt LGPL obligations](https://www.qt.io/development/open-source-lgpl-obligations)

The repository's [`LICENSES`](LICENSES) directory contains the core Python,
GPL, LGPL, Chromium, and PyInstaller texts for review without downloading the
application. The release archive contains the more complete package-by-package
set generated from the exact locked build environment.
