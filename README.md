# exploring cpp in a jupyter notebook

thx to @olilarkin

escpecialy for the docker environment

:)


try interactiv c++ in your browser:  

jupyter-lab:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pflegende/XeusClingMatplotLibExample.git/master?urlpath=lab/tree/cppInterpreter.ipynb)

jupyter-notebook:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pflegende/XeusClingMatplotLibExample.git/master?filepath=cppInterpreter.ipynb)


This is a template for a environment like a interpreter  with c++ / c  in a jupyter notebook.

---

following is the original readme made by @olilarkin and forked by @pflegende *** thu mart 2nd 2021 22:40

Xeus-cling & matplotlib-cpp in a jupyter notebook

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/olilarkin/XeusClingMatplotLibExample.git/master?filepath=XeusClingMatplotLibExample.ipynb)


This is a template for doing audio DSP visualizations with [xeus-cling](https://xeus-cling.readthedocs.io/en/latest/) and [matplotlib-cpp](https://github.com/lava/matplotlib-cpp) and rendering to wav from C++ in a jupyter notebook.

Thanks to @wolfv for the matplotlib-cpp code, @martinRenou for the binder yml and @DannyHavenith for the original docker image, which has been slightly modified:

https://hub.docker.com/repository/docker/olilarkin/xeus-cling-mpl

also uses the [ICST DSP library](https://www.zhdk.ch/en/research/icst/software-downloads-5379/downloads-dsp-library-5384) AudioFile class for wav writing


## how to run it
* install [docker desktop](https://www.docker.com)
* using a terminal, or git-bash mingw-64 terminal on windows
* `git clone --recursive https://github.com/olilarkin/XeusClingMatplotLibExample`
* `cd XeusClingMatplotLibExample`
* `./launch-notebook.sh`
