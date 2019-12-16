# CytoSkaler

## Introduction

CytoSkaler is an interactive imaging tool that can used to segment subcellular and whole cellular areas and generate imaging metrics on those segmentations.

CytoSkaler uses machine learning to generate segmentations of subcellular and whole cellular areas. Specifically, two DeepLab V3+ networks have been trained for the task of semantic segmenation in order to classify relavant pixels in an image as subcellular areas. The first network is used to segment pixels in images representing cytokskeleton-like patterns and the second network is used to segmnet pixels in images representing cytoplasm-like patterns.

## Input

CytoSkaler takes in one or multiple image sets. An image set is a collection of separate channels focused on the same area.
An example of an image set is below:

![alt text](https://github.com/awezmm/CytoSkaler/blob/master/ImagesForReadme/exampleinput1.png)

