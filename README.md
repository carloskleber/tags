# HP_HEM
High Performance Hybrid Electromagnetic Model, a computer implementation.

This library is intended to be easy to use. Interfaces to use it from other programming languages are provided for:
  Julia
  Mathematica (work in progress)
  Matlab

The `examples` folder contains various C files which reproduce results published in the technical literature. Use them as starting point to build your own cases in pure C if you want maximum performance. Examples of use from other programming languages are in their respective interface subfolder: `interfaces/language`.

These codes make use of [cubature](https://github.com/stevengj/cubature). It also uses [Intel's MKL](https://software.intel.com/en-us/mkl).

Don't forget to define `#MKLROOT` (use the bash script `mklvars.sh` that is shipped together with intel's MKL). In my case I use the command `source mklvars.sh intel64`.
