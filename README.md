![AutoGaitA](https://github.com/mahan-hosseini/AutoGaitA/blob/main/res/autogaita_logo.png?raw=true)
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Black](https://img.shields.io/badge/code%20style-black-000000.svg)
# Automated Gait Analysis in Python 🐸

- AutoGaitA simplifies, accelerates, and standardises gait analyses after body posture tracking with [DeepLabCut](https://github.com/DeepLabCut/DeepLabCut) and [Simi Motion](http://www.simi.com/en/products/movement-analysis/simi-motion-2d3d.html?type=rss%2F). 
- AutoGaitA's first-level tools provide a wide range of automated kinematic analyses for each input video and AutoGaitA Group allows the comparison of up to six groups. 
- AutoGaitA enables comparisons to be made across experimental conditions, species, disease states or genotypes. 
- Despite being developed with gait data, AutoGaitA can be utilised for the analysis of any motor behaviour.

## Getting Started

***Note!** Our documentation provides step-by-step walkthroughs of how to install autogaita for **[Windows](https://docs.google.com/document/d/1Y4wrrsjs0ybLDKPzE2LAatqPDq9jtwjIuk4M0jRZ3wE/edit#heading=h.28j6wu2vamre)** and **[Mac](https://docs.google.com/document/d/1Y4wrrsjs0ybLDKPzE2LAatqPDq9jtwjIuk4M0jRZ3wE/edit)***

It is strongly recommended that a separate virtual environment for AutoGaitA is created via

`python -m venv env_gaita`

After creating and activating the virtual environment, AutoGaitA can be installed via pip

`pip install autogaita`

The main user interface can then be accessed via

`python -m autogaita`

## Tutorials and Examples

### Video Walkthrough Tutorials

**[The AutoGaitA YouTube Channel](https://youtube.com/playlist?list=PLCn5T7K_H8K56NIcEsfDK664OP7cN_Bad&si=mV5p2--nYvbofkPh) provides tutorials for file preparation and instructions on how to use AutoGaitA**

### Example Data
We provide an example dataset in the **example data** folder of this repository, with a set of mice walking over differently wide beams and both the beam as well as body coordinates being tracked with DLC. Note that this dataset was used in our tutorial videos introducing *AutoGaitA_DLC*, *AutoGaitA_Group* and in our video explaining file preparation for *AutoGaitA_DLC*.  We further provide a **group** folder there that can be used alongside the *AutoGaitA_Group* tutorial to confirm that users generate the same set of results following our instructions.

### Annotation Table Examples and Templates
Annotation Table example and template files for *AutoGaitA_DLC* and *AutoGaitA_Simi* can be found in the **annotation tables** folder of this repository.
Users are advised to use the template to enter their data's timestamp information and to then compare the resulting table with our example to check formatting.

## Documentation

**[The AutoGaitA Documentation](https://docs.google.com/document/d/1Y4wrrsjs0ybLDKPzE2LAatqPDq9jtwjIuk4M0jRZ3wE/edit?usp=sharing) provides complete guidelines on installation, file preparation, AutoGaitA GUIs, using AutoGaitA via the command line, installing FFmpeg for rotating 3D PCA videos, lists known issues and FAQ.**  

## License

AutoGaitA is licensed under [GPL v3.0](https://github.com/mahan-hosseini/AutoGaitA/blob/main/LICENSE) and Forschungszentrum Jülich GmbH holds all copyrights.

## Authors
Mahan Hosseini
