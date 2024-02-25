<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]

# UEx-AudioPy2
This repository has been created for the second lab session on audio processing with Python of the Multimedia Systems subject at the University of Extremadura (UEx).

## Table of contents
* [Getting started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Usage](#usage)
* [License](#license)

## Getting started
The instructions below help you replicate this repository.

### Prerequisites
Anaconda distribution is recommended. You can install it following the [official installation guide](https://docs.anaconda.com/anaconda/install/linux/).

Check if Anaconda is installed:
```
conda --version
conda -V
```

### Installation
The file [environment.yml](environment.yml) contains all the necessary packages to use this project inside the environment with the name `audiopy` provided. You can create a conda environment from the .yml file as follows:
```
conda env create -f environment.yml
```

Activate the conda environment:
```
conda activate <env_name>
```
where `<env_name>` is the name of the conda environment we have just created. It appears in the first line of the file [environment.yml](environment.yml); `audiopy` in this particular case.

Add the conda environment to JupyterLab so that it appears as a kernel:
```
python3 -m ipykernel install --user --name=audiopy
```

Check that the kernel has been installed correctly:
```
jupyter kernelspec list
```

### Usage
Now we can run JupyterLab and select `audiopy` as the running kernel:
```
jupyter-lab
```

Alternatively, we can use [Visual Studio Code](https://code.visualstudio.com/).

Now that we have everything set up, we can start playing with this repository! :sunglasses:

<img src="https://media.giphy.com/media/3o6MbkFs5CQqK05Jba/giphy.gif" width="300" height="225" />

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://linkedin.com/in/sfandres
