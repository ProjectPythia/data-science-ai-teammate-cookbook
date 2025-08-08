# How to Cite This Cookbook

The material in this Project Pythia Cookbook is licensed for free and open consumption and reuse. All code is served under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0), while all non-code content is licensed under [Creative Commons BY 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). 

Effectively, this means you are free to share and adapt this material so long as you give appropriate credit to the Cookbook authors and the Project Pythia community.

The source code for the book is [released on GitHub](https://github.com/ProjectPythia/cookbook-template) and archived on Zenodo. This DOI will always resolve to the latest release of the book source:  [![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

_📚 See the [Cookbook Contributor's Guide](https://projectpythia.org/cookbook-guide) for step-by-step instructions on how to create your new Cookbook and get it hosted on the [Pythia Cookbook Gallery](https://cookbooks.projectpythia.org)!_

## 🧪 Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### 🚀 Running on Binder

The simplest way to interact with a Jupyter Notebook is through [Binder](https://binder.projectpythia.org/), which enables the execution of a [Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not important for now. All you need to know is how to launch a Pythia Cookbook chapter via Binder.

Simply navigate your mouse to the top right corner of the book chapter you are viewing and click on the 🚀 rocket ship icon, and be sure to select “launch Binder”. After a moment you should be presented with a notebook that you can interact with. You’ll be able to execute and even change the example programs. You’ll see that the code cells have no output at first, until you execute them by pressing `{kbd}Shift+Enter`.

📖 Complete details on how to interact with a live Jupyter notebook are described in [Getting Started with Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

> ⚠️ Note: Not all Cookbook chapters are executable. If you do not see the rocket ship icon, such as on this page, you are not viewing an executable book chapter.

### 🖥️ Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

_(Replace "cookbook-example" with the title of your cookbooks)_

```bash
# 1. Clone the repository
git clone https://github.com/ProjectPythia/cookbook-example.git

# 2. Move into the directory
cd cookbook-example

# 3. Create and activate your conda environment
conda env create -f environment.yml
conda activate cookbook-example

# 4. Start JupyterLab
cd notebooks/
jupyter lab
