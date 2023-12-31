# Prerequisites

### Image Analysis basics
This course won't explain the concepts behind many image analysis operations, such as _filtering_, _segmentation_ etc. There are many places to learn more about this, but an excellent place to start is Pete Bankhead's [free book](https://bioimagebook.github.io/index.html).

### Computing
In its current state, it's very hard to use napari without having to deal with the _command line interface_ (as opposed to _graphical user interfaces_, or GUIs), at least to set things up. This can be uncomfortable for people who haven't used this kind of interface before, but we'll try to minimise the usage and keep things easily copy-and-paste-able!

This course can be taken without prior knowledge of programming, although familiarity with programming may help to understand some of the concepts. Since napari is a `Python` package, knowing this language will definitely help for getting the most out of napari.

### System setup
This is the important bit! It's crucial that students start the course with a fully working python installation so we can get straight on to the interesting stuff. The most common way of getting set up with python is to install either Anaconda or Miniconda. TODO: SHOULD WE GO STRAIGHT FOR MAMBA?

Here we'll use the example of Miniconda. Installation information is found [here](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html).

![Miniconda](images/miniconda.png)

There are installation options for all major operating systems.


![Downloads for miniconda](images/miniconda_downloads.png)

Now conda should be accessible via the command line, either: `Terminal` on Mac OS or `Anaconda Prompt` on Windows. You can verify a correct installation by typing `conda --version` into your command line application, which should return something like this:


![Conda version check](images/conda_version_check.png)
