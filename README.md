# Diagram exporter example
An example on how to use reactome (https://reactome.org) Rest API.

This example consists in a [Jupyter notebook](diagram-exporter-tutorial.ipynb) that shows how to use python to get the most significant pathways for a list of genes. This example should easily be portable to other languages such as Java or R.

The diagram exporter is a service offered by Reactome to obtain the diagram images via http Rest API that can be found in the Content Service: https://reactome.org/ContentService/#/exporter/toRasterUsingGET

The analysis service allows users to send data and visualize it on top of the diagram. To see more about how to perform an analysis go to https://reactome.org/dev/analysis.

## Install
To run the notebook, you need first to install jupyter http://jupyter.org/install.html.

Then clone the project in your disk

```
cd ~
git clone https://github.com/pasculorente/diagram-exporter-use-case.git
cd diagram-exporter-use-case
```

After that, run jupyter into this folder

```
jupyter-notebook
```
