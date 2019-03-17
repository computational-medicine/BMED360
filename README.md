# In Vivo Imaging and Physiological Modelling

![BMED360 image](./assets/bmed360_logo.png)

This is the repository for the course [BMED360](https://www.uib.no/en/course/BMED360) given at the Department of Biomedicine<br>

(*) Biomedicine covers those areas of human biology, chemistry and medicine that seek to explain the factors behind health and disease at the molecular and cellular level. This information is applied in the development of better diagnostics and treatments.<br>

Here you find code and documentation for the course. 

The goal of this course is to obtain theoretical and practical knowledge on functional and quantitative in vivo imaging in man and animal using magnetic resonance imaging (MRI) and computer-based image analysis. The focus is on brain imaging (perfusion, diffusion, permeability mapping) and structural and functional connectivity, but also examples from functional kidney imaging and (image-based) systems biology will be presented. A major objective is also to give insight about the importance of mathematical models and computations in analysis and understanding of complex physiological processes, and the need of cross-disciplinary collaborations.

You will find more detailed information about 
this course at [MittUiB](http://mitt.uib.no/course/17428).

# Setting up your system

**Follow the instructions at [Setting up your system](setup.md) (`setup.md`) to get ready**

Note: To access the course notebooks interactively without downloading any software we are planning to use [Binder](https://mybinder.org), see also
[BinderHub](https://github.com/jupyterhub/binderhub).


# Notebooks
The course is based on the Jupyter Notebook, a web-based framework for developing and presenting code-based projects (take a look at https://youtu.be/HW29067qVWk og https://youtu.be/2eCHD6f_phE for introductions to Jupyter Notebooks).

Throughout the course you will work with notebooks that contain various material and programming tasks. We recommend that you *make a copy of our notebooks before you are editing them*. In this respect you might adopt the naming convention `my_[name_of_notebook].ipynb`.


## Get started - test your environment
* [Python, Numpy, Pandas, Matplotlib, Nibabel, Biopython and more](notebooks/0.0-test.ipynb): run through this notebook (`notebooks/0.0-test.ipynb`) to check that your environment is OK.<br>

____________________________________________________________________________________________________________________________________<br>

## Major topics in the "In Vivo Imaging and Physiological Modelling" course are:


[LECTURES](https://sites.google.com/site/bmed360/courses):

- **Lec 0: Tools and Repositories**  (see also https://computingskillsforbiologists.com)
- **Lec 1: Introduction to modelling, MRI and image processing**
- **Lec 2 & 3: Water diffusion and diffusion tensor MR Imaging (MR-DTI)** (part1) (part2)
- **Lec 4 & 5: Blood perfusion and dynamic susceptibility contrast MR imaging (DSC-MRI)** (part1) (part2)
- **Lec 6: Vascular permeability and T1-weighted dynamic contrast enhanced MRI (DCE-MRI)**
- **Lec 7: Structural and functional brain connectivity using multimodal recordings** 
- **Lec 8: Special topic** (e.g. Introduction to systems biology; [On consciousness, resting state fMRI, and neurodynamics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2880806); [Deep learning in medical imaging with focus on MRI](https://www.sciencedirect.com/science/article/pii/S0939388918301181))  


[LABS](https://sites.google.com/site/bmed360/labs): 

- **Lab 1** Image processing in PYTHON and MATLAB
- **Lab 2** Multispectral imaging and tissue classification (machine learning; supervised and unsupervised learning)
- **Lab 3** Processing of diffusion MRI data (DTI and DSI)
- **Lab 4** Processing of dynamic susceptibility contrast MR images (DSC-MRI) 
- **Lab 5** Vascular permeability mapping and Dynamic T1-weighted Contrast Enhanced MRI
(DCE-MRI)
- **Lab 6** Estimation and visualization of structural and functional brain connectivity incl. complex network analysis



<p>&nbsp;</p>
<div><strong>Order of lectures and programming labs / demos (tentative schedule Spring 2019)</strong>:</div>
<div>
<table border="1" cellspacing="0">
<tbody>
<tr>
<td>&nbsp;BLOCK 1</td>
<td>&nbsp;Day 1 (April 24)</td>
<td>&nbsp;Lec 1</td>
<td>&nbsp;Lab &nbsp;1</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 2 (April 26)</td>
<td>&nbsp;Lec 2</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 3 (April 29)</td>
<td>&nbsp;Lec 3</td>
<td>&nbsp;Lab 2</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 4 (April 30)</td>
<td>&nbsp;Lab 2 cont</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 5 (May 3)</td>
<td>&nbsp;Lab 3</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 6 (May 6)</td>
<td>&nbsp;Lec 4</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 7 (May 7)</td>
<td>&nbsp;Lec 5</td>
<td>&nbsp;Lab 4</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 8 (May 8)</td>
<td>&nbsp;Lec 6</td>
<td>&nbsp;Lab 5</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 9 (May 13)</td>
<td>&nbsp;Lec 7</td>
<td>&nbsp;Lab 6</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 10 (May 14)</td>
<td>&nbsp;Home prj</td>
<td>&nbsp;present</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;HOME<br />PROJECT</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;BLOCK 2</td>
<td>&nbsp;Day 11 (June 3)</td>
<td>&nbsp;Home<span>&nbsp;</span><br />project results&nbsp;</td>
<td>&nbsp;Lec 8</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 12 (June 4)</td>
<td>&nbsp;Exam<br />&nbsp;prep.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 13 (June 5)</td>
<td>&nbsp;Q &amp; A</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 14 (June 6)</td>
<td>&nbsp;Exam<br />&nbsp;&nbsp;prep.</td>
<td>&nbsp;MC /<br />&nbsp;quiz<br />&nbsp;exam</td>
</tr>
<tr>
<td>&nbsp;</td>
<td>&nbsp;Day 15 (June 7)</td>
<td>Oral exam</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
</div>
<p>&nbsp;</p>
