# ParMETIS - Parallel Graph Partitioning and Fill-reducing Matrix Ordering

This repository publishes a branch **main** that only differs from **upstream**
by adding all the header files in the installation that are directly included
from [code_aster] source files.

Original ParMETIS source files (Apache License Version 2.0) can be found on [its website][ParMETIS].

```shell
mkdir -p $HOME/dev/aster-prerequisites && cd $HOME/dev/aster-prerequisites
hg clone https://bitbucket.org/code_aster/metis
cd metis
hg update code_aster
```

See the file `BUILD.txt` for installation instructions.

[code_aster]: http://www.code-aster.org
[ParMETIS]: http://glaros.dtc.umn.edu/gkhome/metis/parmetis/overview
