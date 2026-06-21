
<!--
@author hxAri (hxari)
@create 2025-02-24 15:15
@update 2026-06-18 00:03
@github https://github.com/uranite-lang/uranite

Uranite - Uranite Copyright (c) 2025 - hxAri <hxari@proton.me>
Uranite Licence under GNU General Public Licence v3

Syntax highlighting configuration for the Nano text editor.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.
-->

# Uranite Language Support for Nano

This directory contains syntax highlighting configuration for the Nano text editor.

## Installation

To install for your user, append the content of `uranite.nanorc` to your `~/.nanorc` file, or include it:

```bash
mkdir -p ~/.nano
cp uranite.nanorc ~/.nano/
echo "include ~/.nano/uranite.nanorc" >> ~/.nanorc
```

Alternatively, you can copy it to the system-wide nano directory (usually `/usr/share/nano/`):

```bash
sudo cp uranite.nanorc /usr/share/nano/
# Then edit /etc/nanorc to include it if it doesn't auto-include everything
```
