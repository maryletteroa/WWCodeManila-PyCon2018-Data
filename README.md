# "Hello, World of Data!": Your ABC blocks in data handling, analysis, and visualization

by Marylette Roa, Iris Uy, Isabelle Tingzon, Clau Yagyagan, and the [WWCode Manila](https://www.meetup.com/Women-Who-Code-Manila/) community  
presented during [PyConPH 2018](https://pycon.python.ph/) at iAcademy Plaza, Gil Puyat Ave,. Makati City on February 25 2018.  


## Description
This workshop covers an introduction to data analysis using the programming language [Python](https://www.python.org/). It aims to introduce basic concepts, commonly used tools, and workflows to document, describe, analyze, and visualize data. Our targeted audience are those who are new to Python as a tool for data analysis, as well as those who are beginners in data analysis and are looking for tools to get started.

Time: 3 hrs  
Format: Follow-along demos & exercises  
Reminders:

1. Bring your own laptop (or share with a friend)
2. [Install needed tools](#tools-and-installation)
3. Download the [materials](materials)
4. Optional: Familiarize your self with [Jupyter Notebook](#launching-the-jupyter-notebook)
5. **Recommended**: Set up a [Plotly account](#setup-a-plotly-account)

Requirement: An understanding of the [Python programming language](https://www.python.org/) is necessary to answer the exercises. 

## Outline
The workshop is divided into the following topics. **Please download the [materials](materials) ahead of the workshop.**

* Introduction and Documentation with Jupyter notebook (15 mins)
* Data handling (45 mins)
* Analysis (45 mins)
* Visualization (45 mins)
* Today I Learned (15 mins)
* Q&A (15 mins)


## Tools and installation
This will take a bit to download and install so **make sure to set this up before the workshop starts**.

* Python 3.x
* Jupyter notebook
* Pandas
* Scikit-learn
* Seaborn
* Plotly

The easiest way to obtain most of these is to install the [latest version of Anaconda](https://www.anaconda.com/download/). Simply download the corresponding executable for your operating system. For this workshop, please choose the Python 3.6.x version. The installer should guide you through the process.

Once you have installed Anaconda, you also need to install the Python library `plotly` for the visualization part:


1. Open `Anaconda Prompt` from the Start menu (Windows) or open the `Terminal` application (Mac/Linux). 
2. Type the following, which should guide you through the installation process: 

```shell
conda install plotly
```

## Launching the Jupyter Notebook

Most of the materials in this workshop are presented using follow-along Jupyter notebooks. These are interactive notebooks which can contain texts, codes, results of codes, figures, and more. You can read more about Jupyter notebook [here](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html).

You can also [try Jupyter](https://try.jupyter.org/) without installing. 

However, Anaconda comes with Jupyter notebook! To launch this locally on your computer, simply look for the Jupyter Notebook icon in the Start Menu or Desktop (Windows) or type the following in the command prompt or terminal (Windows, Mac, Linux): 

```shell
jupyter notebook
```

The notebook will be launched in a new browser window. You can go ahead and explore the dashboard.  More things that you can do is in this [guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html). 

At the start of the workshop, we'll also help you with navigating and using the notebook. But if you want a quick go-over on your own, here's a good [YouTube resource](https://www.youtube.com/watch?v=jZ952vChhuI). Another way to maximize this tool is to familiarize yourselves with [keyboard shortcuts](http://maxmelnick.com/2016/04/19/python-beginner-tips-and-tricks.html). We'll use the basic shortcuts during the workshop, and we'll let you explore more on your own.

#### Tip: Navigating to the workshop notebooks
To make finding these notebooks simpler, save the workshop [materials](materials) in the same disk (e.g `C:`) where you installed Anaconda and open Jupyter Notebook by searching for it's icon in the Start menu (Windows), or launch the Jupyter notebook within the folder containing the materials using the `Anaconda Prompt` (Windows) or `Terminal` (Mac/Linux):

```shell
cd /path/to/wwcodemanila/dataworkshop/materials
jupyter notebook
```

Using the Jupyter dashboard, simply click the folders leading up to the `*.ipynb` files. 

## Setup a Plotly account
In order to plot with plotly, it is advisable to [set up an account](https://plot.ly/accounts/login/?action=login).

## Credits
We based our materials and exercises, with permission, on [Professor Jennifer Widom's short course on Big Data](http://www.professorwidom.org/bigdata/).


## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>