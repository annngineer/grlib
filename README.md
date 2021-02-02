# grlib
Contains GRLIB library from Gaisler [link to Download GRLIB page on gaisler.com](https://www.gaisler.com/index.php/downloads/leongrlib) with following changes:
* `designs/` folder. Only `*.vhd | *.v | *.xco | *.xci | *.patch` files have left to significantly reduce repo's size. Those changes make impossible to use `make` to generate a top-level file, run simulation or run synthesis. Purpose of the repo is to be used as submodule in projects with its own building system. `bin` folder left in case some traditional Gaisler building system will be needed
* `boards/` folder. Only `*.vhd | *.v | *.xci | *.patch` files have left to reduce repo's size.
