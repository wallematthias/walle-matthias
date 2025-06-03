---
title: 'Reading in AIM files with vtkbone'
date: 2024-02-21
permalink: /posts/2024/02/reading-aims/
tags:
  - scancoIO
  - aim files
  - binary file reader
---

# Tutorial: Reading in AIM files with vtkbone

*Authors: Dr. Matthias Walle, Dr. Danielle Whittier, Jilmen Quintiens*

*Created: 17 Jan 2024*

*Last Modified: 22 Feb 2024*

## Introduction

This tutorial is part of a series designed to help you get started with the `vtkbone` library, enabling the reading, manipulation, and writing of `.AIM` files outside the Scanco system. In this part, we focus on the basics of reading an AIM file and converting it to a VTK or SimpleITK image object. The full tutorial series can be found here: [Scanco IO Module Tutorials](https://github.com/OpenMSKImaging/vtkbone/tree/master/Tutorials). Please see this link for further information on how to install `vtkbone`


## Prerequisites

Before starting, ensure you have completed the installation steps outlined in the README of the Scanco IO module repository. This includes setting up a conda environment with all necessary packages.

## Loading Necessary Packages

To begin, we'll load the necessary Python packages. The `vtkbone` package is essential for working with `.AIM` files, providing the tools needed for reading and writing these files.

```python
import vtk
import vtkbone
import numpy as np
import SimpleITK as sitk
```

# Reading an AIM File
Reading an AIM file and converting it to a VTK or SimpleITK object is straightforward with the utility functions provided by vtkbone. The following example demonstrates how to load an AIM file and inspect its metadata, including density calibration information which is crucial for converting images to meaningful units.

```python
# Specify the path to your AIM file
aim_file_path = 'path/to/your/AIMfile.AIM'

# Load the AIM file as a VTK object
aim_reader = vtkbone.vtkboneAIMReader()
aim_reader.SetFileName(aim_file_path)
aim_reader.Update()

# Convert the VTK object to a SimpleITK image
vtk_image = aim_reader.GetOutput()
sitk_image = sitk.GetImageFromArray(vtk.util.numpy_support.vtk_to_numpy(vtk_image.GetPointData().GetScalars()))
sitk_image.SetOrigin(vtk_image.GetOrigin())
sitk_image.SetSpacing(vtk_image.GetSpacing())
```

This code snippet loads an AIM file, converts it to a VTK object using vtkbone, and then to a SimpleITK image. It demonstrates the process of accessing the image data, origin, and spacing, which are essential for further image processing tasks.

## Conclusion
In this tutorial, we've covered the basics of loading .AIM files using the vtkbone library, focusing on converting these files to formats suitable for image processing tasks. The next part of this series will delve into manipulating and analyzing these images to extract meaningful information.

Stay tuned for more tutorials on utilizing the Scanco IO module for your research and development projects.


