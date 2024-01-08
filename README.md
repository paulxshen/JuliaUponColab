# JuliaUponColab
Installs Julia runtime on Google Colab

Run in cell
```
%%shell
git clone "https://github.com/paulxshen/JuliaUponColab/"
bash JuliaUponColab/setup.sh
```

Then reload page and change runtime to Julia 

Optionally, also run 
```
using AbbreviatedStackTraces
ENV["JULIA_PKG_PRECOMPILE_AUTO"] = 0
```
 to simplify stack trace and avoid unnecessary precompilations

By Paul Shen <pxshen@alumni.stanford.edu>, script adapted from ageron
