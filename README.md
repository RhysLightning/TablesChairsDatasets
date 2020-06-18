# TablesChairsDatasets
An unlabelled dataset of 32x32 Images for use with ANN.  These contain mainly tables and chairs but also other objects.  Images are organised into folder by type.

These datasets were made for use in an experiment testing the effect of context on CNN performance.  They were designed for use with a CNN trained on the Cifar100 dataset (dataset described in this paper: https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf).


# Standard_Datasets
Images used as part of the original experiment

## Table_and_chair_normal
19 Images of tables and chairs in expected configurations

## Table_and_chair_odd_position
19 Images of tables and chairs in odd configurations (e.g. corner to corner)

## Table_and_chair_odd_pose
19 Images of tables and chairs in odd poses (e.g. inverted)

## Table_chair_and_apple
19 Images of either table and apple or chair and apple


# Other_Datasets
Images created later not belonging to the above categories

## Additional Apples
More pictures of apples

## Brown Table
A set of equivalent replacement images for all images in 'Standard_Datasets' which feature the grey table.  These replace the grey table with a brown topped one.

## Single Images
Images of each object used in the experiment on its own with several angles.

## After Cifar Exploration
Pictures of various objects designed to be more similar to those found in the Cifar100 dataset
