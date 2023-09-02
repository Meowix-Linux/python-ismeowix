<p align="center">
    <img src="https://github.com/Meowix-Linux/Meowix-ISO/blob/main/assets/meowix.svg?raw=true" width=25% height=25%>
</p>

<h1 align="center">Python Library: ismeowix</h1>

<p align="center">Library for Meowix Python applications to check if the intended operating system is being used</p>

<p align="center">
    <a href="https://www.gnu.org/licenses/gpl-3.0.en.html"><img alt="GPLv3 License" src="https://img.shields.io/badge/License-GPLv3-red.svg"></a>
</p>

## Installation

You may either install a pre-built version of the package or build it yourself.

### Downloading a pre-built package

Pre-built packages are available on [PyPI](https://pypi.org/project/ismeowix) (for Windows and macOS) and in [Meowix-Repo](https://github.com/Meowix-Linux/Meowix-Repo).

### Building the package manually

To build the package manually, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/Meowix-Linux/python-ismeowix.git
```

2. Navigate to the repository directory:

```bash
cd python-ismeowix
```

3. Build the package:

```bash
python setup.py sdist bdist_wheel
```

After the above command finishes, there should be package files in the `dist/` directory.

*Looking for the `pacman` version of this package? That's in [python-ismeowix-PKGBUILD](https://github.com/Meowix-Linux/python-ismeowix-PKGBUILD).*

## License

This repository is licensed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html). The Catppuccin theme is licensed under the [MIT License](https://opensource.org/licenses/mit/). Licenses for other software included in the distribution are usually found within the files provided by their respective packages. If you have found that Meowix has violated any licenses or copyrights, please don't hesitate to open an issue on the repository/repositories that do so, and we will do our best to respond in a timely manner.
