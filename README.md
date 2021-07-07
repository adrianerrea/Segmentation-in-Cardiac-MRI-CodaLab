# Segmentation-in-Cardiac-MRI-CodaLab

## Description

In recent years, many machine/deep learning models have been proposed to accurately quantify and diagnose cardiac pathologies. However, the segmentation of the right ventricle (RV) is a challenging task due to the highly complex and variable shape of the RV and its ill-defined borders in cardiac MR images. The last MICCAI challenge to focus on right ventricular segmentation took place in 2012, well before the deep learning revolution, and was based on 48 cases from a single clinical center. As part of the 12th Workshop on Statistical Atlases and Computational Modelling of the Heart (STACOM 2021), we invite participants to implement and evaluate advanced machine/deep learning approaches for right ventricular segmentation, based on a large multi-disease, multi-view and multi-center sample of 360 cardiac MRI datasets. A novel aspect of this challenge is the inclusion of long-axis images to help the automatic definition of the basal plane of the RV, which can be confused with the right atrium.

## Links

Home Page: https://competitions.codalab.org/competitions/31559

MICCAI 2021 Challenge Page: https://www.ub.edu/mnms-2/

## Insights

+ The data provided contains more labelled masks than needed so my first step was to change from a multiclass problem to a binary problem through a preprocessed phase
+ Four perspectives for each patient was provided and the final metric took into account all of them so one approach was to create a model for each perspective as the final submits must go separately for each perspective

## Conclusions

+ I tried to make the inference phase for the 3D model already trained but I could not finalize it and I did not make any submit to the competition
+ However, I think it was worthwhile to post the code used as it may be useful in the future for similar problems
