# Improved-Arrhythmia-Classification-Using-Select-Morphological-and-Heart-Rate-Variability-ECG-Feature
Final Project Thesis in partial fulfilment of the degree of MSc Big Data Science at the Queen Mary University of London. In this paper, several ML techniques will be employed to produce a model pipeline that takes an electrocardiogram signal (ECG) input signal vector, and correctly classifies individually identified heartbeats as normal, or one of several classes of arrhythmia. The classifications produced by the model should identify cases where ICD intervention is appropriate. 

## Files

The Jupyter notebooks in this folder represent the coded work for my final project. 
There are three notebook files in total:

* `ProjectConceptExploration.ipynb`
* `ProjectExtractionAndPreprocessing.ipynb`
* `ProjectExperimentsAndPipeline.ipynb`

## Project Concept Exploration

The first notebook:  ProjectConceptExploration.ipynb is a sandbox/testing notebook used for
testing and developing the implementation of various concepts used throughout the project.
It is provided here to give some insight to some of the code used in the final pipeline.

## Project Extraction and Preprocessing

The next notebook: ProjectExtractionAndPreprocessing.ipynb is used to extract the data from
the dataset, remap the provided physionet labels to AAMI labels, and finally save the data
in a readable format for the final pipeline input.

## Project Experiments and Pipeline

The final notebook contains the code for the main project's pipeline, and classifier model
experiments. Code for each stage of the pipeline is demonstrated. The final results are also 
recorded in here.
