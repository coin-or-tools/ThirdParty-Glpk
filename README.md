# ThirdParty-Glpk

This is an autotools-based build system to build and install the
[GNU Linear Programming Kit](https://www.gnu.org/software/glpk) (GLPK)
as it is used by some COIN-OR projects.

## Installation steps

1. Obtain the GLPK source code.

   **********************************************************************
   Note: It is YOUR RESPONSIBILITY to ensure that you are entitled to
         download and use this third party package.
   **********************************************************************

   The shell script `get.Glpk` can be used to automatically download and
   extract the GLPK source code. The script will attempt to download a
   specific GLPK version from http://ftp.gnu.org/gnu/glpk.

   The script requires wget, curl, or fetch to be available on the system
   and in the shells search path (`$PATH`).

2. Run `./configure`. Use `./configure --help` to see available options.

3. Run `make` to build the GLPK library.

4. Run `make test` to test the GLPK library.

5. Run `make install` to install the GLPK library and header files.
