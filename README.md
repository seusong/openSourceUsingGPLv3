# MyOpenSourceProject

MyOpenSourceProject is a simple example project that demonstrates how to use GPL-licensed software within an open-source project.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

This project incorporates code from GNU Wget, which is also licensed under the GPLv3. Please see the `external/wget` directory for more information.

## Building MyOpenSourceProject

To build MyOpenSourceProject, follow these steps:

1. Build GNU Wget:

   ```sh
   + other operated os
   cd external/wget
   ./configure
   make

   + for mac os
   make sure that you install all dependencies: wget, autoconf,automake, libtool, pkg-config, gnutls, pcre2

   for base:
   - brew install wget
   - brew intall pcre2 -> export PKG_CONFIG_PATH="/usr/local/opt/pcre2/lib/pkgconfig:$PKG_CONFIG_PATH" -> pkg-config --modversion libpcre2-8
   - brew install wget

   after:
      gcc -o my_project main.c
      ./my_project


   ```
