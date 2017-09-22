---
title: ANTs | Tutorials
id: tutorials
permalink: /tutorials/
layout: research
---

# Tutorials

On this page, we present a comprehensive collection of tutorials for learning how
to use various tools in the ANTsX ecosystem. Some tutorials are short and demonstrate 
specific functions at a glance, whereas other tutorials are more in-depth and cover
a broad functionality. If there's something specific you'd like to learn about, feel
free to ask us to make a tutorial for it!


------------------------------------------------------------------------
### Comprehensive ANTs Tutorial

Everyone interested in ANTs should start here. This 41-page guide gives
a short overview of the methodology and software behind ANTs using real examples. 
The tutorial can be downloaded here [as a pdf](https://github.com/stnava/ANTsDoc/raw/master/ants2.pdf). 

------------------------------------------------------------------------
### ANTsR Cookbook

Everyone interested in ANTsR should start here. On this page, you can find a 
cookbook with a comprehensive listing of ANTsR tutorials and answers to 
frequently asked questions. The cookbook [can be accessed here](https://rpubs.com/antsr/cookbooks)

------------------------------------------------------------------------
### Template Building

This tutorial gives two examples of template building using the different template 
building scripts available in ANTs - faces and brain slices.
The code and data [can be found on github](https://github.com/ntustison/TemplateBuildingExample)

------------------------------------------------------------------------
### MALF Labeling

This tutorial givesn an example of ANTs MALF labeling using antsJointLabelFusion.sh.
The code and data [can be found on github](https://github.com/ntustison/MalfLabelingExample)

------------------------------------------------------------------------
### Cooking up template priors

This short tutorial gives you code and a collection of real brian images to demonstrate
how to make template priors. The code and data 
[can be found on github](https://github.com/ntustison/antsCookTemplatePriorsExample)

------------------------------------------------------------------------
### Pediatric Template of Brain Perfusion

This tutorial uses ANTs and ANTsR to show you how to process raw pediatric MRI
data with the following goals:

- Organize and inspect the raw data and identify potential problem cases.
- Develop a template construction procedure to address our hypotheses.
- Attach prior distributions to the template.
- Process the full data with ANTs pipelines.
- Perform univariate and multivariate statistical tests.

The complete code and data [can be found on github](https://github.com/stnava/ANTsTutorial)

------------------------------------------------------------------------
### Congressional Template Building

This repository contains code and notes for building a template of all members of 
congress using ANTs and antsMultivariateTemplateConstruction2.sh.
The code and data [can be found on github](https://github.com/ntustison/CongressionalFaceTemplates)

------------------------------------------------------------------------
### Basic Brain Mapping

This short tutorial demonstrates a simple and fast brain registration example. Also,
this tutorial shows how to use a brain mask to restrict the registration focus.
The code and data [can be found on github](https://github.com/stnava/BasicBrainMapping)

------------------------------------------------------------------------
### Processing Amyloid PET 

This tutorial shows you how to process Amyloid PET and create an Amyloid template.
The code and data [can be found on github](https://github.com/stnava/petSUVR)

------------------------------------------------------------------------
### Processing Arterial Spin Labeling

Arterial spin labeling (ASL) is a functional MRI technique that can quantitatively 
measure brain perfusion without using a radioactive tracer. This tutorial shows you
how to process such data using ANTs and ANTsR.
The code and data [can be found on github](https://github.com/stnava/antsASLProcessing)

------------------------------------------------------------------------
### Minimal fMRI Processing

This tutorial by Brian Avants shows minimal preprocessing techniques for fMRI data using ANTs.
The code and data [can be found on github](https://github.com/stnava/fMRIANTs)

------------------------------------------------------------------------
### In-depth fMRI Processing

This additional tutorial by Nick Tustison shows more in-depth techniques and functionality for
processing fMRI data using ANTsR.
The code and data [can be found on github](https://github.com/ntustison/ANTsRfMRITutorial)

------------------------------------------------------------------------
### Chicken and Butterfly - Registration

These are two tutorials demonstrating global registration optimization using landmark
distances and multi-start affine initialization with ANTs on trivial examples.
The code and data for the chicken tutorial [can be found on github](https://github.com/stnava/chicken).
The code and data for the butterfly tutorial [can be found on github](https://github.com/stnava/butterfly).

------------------------------------------------------------------------
### ANTs Brain Registration with Mask

This tutorial demonstrates ANTs registration on real brain images.
The code and data [can be found on github](https://github.com/ntustison/antsRegistrationWithMaskExample)

------------------------------------------------------------------------
### ANTs CT Lung Registration

This tutorial demonstrates CT Lung registration using ANTs.
The code and data [can be found on github](https://github.com/ntustison/antsCtLungRegistrationExample)

------------------------------------------------------------------------
### Multi-modality processing

This tutorial demonstrates how to process multi-modality data using ANTs.
The code and data [can be found on github](https://github.com/stnava/ANTS_MultiModality).

------------------------------------------------------------------------
### Sparse CCA Tutorial

This tutorial demonstrates Sparse Canonical Correlation Analysis for multivariate, 
multi-view statistical analysis in ANTsR.
The code and data [can be found on github](https://github.com/stnava/sccanTutorial)

------------------------------------------------------------------------
### NeuroBattery

This incredible tutorial/repository demonstrates using ANTs to process multiple-modality images
(MRI, ASL/PCASL, DTI, and fMRI).

The code and data [can be found on github](https://github.com/jeffduda/NeuroBattery)

------------------------------------------------------------------------
### Eigenanatomy

This tutorial demonstrates the use of Eigenanatomy using ANTsR.
The code and data [can be found on github](https://github.com/stnava/eigenanatomy1)

------------------------------------------------------------------------
### Joint Intensity Fusion Example

This brief tutorial shows how to perform joint intensity fusion using ANTs.
The code and data [can be found on github](https://github.com/ntustison/JointIntensityFusionExample) 

------------------------------------------------------------------------
### Single Subject Template

In this tutorial, you will build a template from a single image and a rotated version of that image,
then visually compare the template with the two images used to make the template. This
tutorial uses ANTs (antsMultivariateTemplateConstruction).
The code and data [can be found on github](https://github.com/ntustison/SingleSubjectTemplateExample)

------------------------------------------------------------------------
### Cortical Thickness Tutorial

This is another tutorial demonstrating specifically how to use the ANTs cortical
thickness pipeline with T1 images, T1+T2 images, and how to perform each of the 5 major
steps in the pipeline individually.
The code and data [can be found on github](https://github.com/ntustison/antsCorticalThicknessExample)

------------------------------------------------------------------------
### Cortical Thickness Notes and Figures

This is the code and figures by Nick Tustison from the ANTs vs Freesurfer cortical
thickness comparison paper. This will help you learn about the ANTs cortical thickness pipeline - also
known as DiReCT or Kelly Kapowski - with some code also available.
The code and data [can be found on github](https://github.com/ntustison/KapowskiChronicles)

------------------------------------------------------------------------
### Denoise Image Example

This short example demonstrates how to use the DenoiseImage command in ANTs.
The code and data [can be found on github](https://github.com/ntustison/DenoiseImageExample)

------------------------------------------------------------------------
### Lung Ventilation Segmentation

This example shows segmentation of the lungs based on ventilation.
The code and data [can be found on github](https://github.com/ntustison/LungVentilationSegmentationExample)

------------------------------------------------------------------------
### Atropos and N4 Example

This example shows how to use the antsAtroposN4 command in ANTs.
The code and data [can be found on github](https://github.com/ntustison/antsAtroposN4Example)

------------------------------------------------------------------------
### ANTs Visualization

This tutorial shows you how to visualize volumes and surfaces, and how to create
tiled image mosaics using ANTs.
The code and data [can be found on github](https://github.com/ntustison/antsVisualizationExamples)

------------------------------------------------------------------------
### Brain Extraction Example

This example shows how to perform brain extraction using ANTs.
The code and data [can be found on github](https://github.com/ntustison/antsBrainExtractionExample)

------------------------------------------------------------------------
### BRATS 2013 Tumor Segmentation

This repository contains notes and code in ANTs/ANTsR for the BRATS 2013 tumor
segmentation challenge. 
The code and data [can be found on github])https://github.com/ntustison/BRATS2013

























