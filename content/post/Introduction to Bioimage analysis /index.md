---
title: "Introduction to Bioimage analysis for Master of Science in Neurosciences"
date: 2022-09-08
layout: post
draft: false #set to false to go live
tags: ["bioimage analysis", "python"]
---

**Introduction to Bioimage analysis for Master of Science (M.Sc.) in Neurosciences.**

See repository for details

**See below Repository link**


## Repository Link

<a href="https://github.com/amgfernandes/FIJI_Clij2_GPU_Weka_ML_course"> Introduction to Bioimage analysis </a>


# FIJI Clij2 GPU Weka ML course


Introduction to Bioimage analysis for Master of Science (M.Sc.) in Neurosciences



## In preparation for the course please install in advance:


- ### FIJI: https://imagej.net/software/fiji/


- ### Python/Anaconda installation (optional): https://docs.anaconda.com/anaconda/install/



- ### Download or use Git to clone this repository: 
  


You can use `Download ZIP` or Git: `git clone https://github.com/amgfernandes/FIJI_Clij2_GPU_Weka_ML_course.git`

### For the python part:

You can create a new environment called `bioimage`:

```
cd python_visualization

conda create --name bioimage -y

conda activate bioimage

conda install pip -y

pip install -r requirements.txt
```

And add your new env kernel to your jupyter

```
conda install -c anaconda ipykernel

python -m ipykernel install --user --name=bioimage
```

## Bioimage Analysis: Recommended Reading and Viewing:
- Python: Basics for Data Scientists --> https://github.com/FabrizioMusacchio/Python_Course
- Introduction to Bioimage Analysis --> https://bioimagebook.github.io/README.html
- Introduction to Bioimage Analysis video --> https://www.ibiology.org/techniques/introduction-to-bioimage-analysis/
- Bioimage analysis for computational biology --> https://github.com/BiAPoL/Bio-image_Analysis_with_Python
- Introduction to Image Analysis with FIJI --> https://www.crick.ac.uk/sites/default/files/2018-07/Introduction%20to%20image%20analysis%20with%20FIJI_David%20Berry_TheFrancisCrickInstitute_0.pdf
- ML for Bioimage analysis --> https://montpellierressourcesimagerie.github.io/mri-workshop-machine-learning/slides_day1.revealjs.htm#/3
