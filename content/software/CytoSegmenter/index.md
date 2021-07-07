---
title: CytoSegmenter
date: "2020-11-01"
---
A Kernel-based change detection method to map shifts in phytoplankton communities measured by flow cytometry.<br/>

In this project in collaboration with [Dr. Corinne Jones](https://sites.stat.washington.edu/people/cjones6/) and [UW Pr. Zaid Harchaoui](http://faculty.washington.edu/zaid/), we applied a new method to segment flow cytometry data on phytoplankton measured during research cruises. Understanding how phytoplankton communities vary in time and space across ocean basins is critical for predicting how marine ecosystems will respond to future climate change. We propose an approach to segmenting sequences of point clouds into distinct segments. The software, called [Cytosegmenter](https://github.com/cjones6/cytosegmenter), first generates Hilbertian embeddings for each point cloud. It then segments the data by applying a kernel-based change-point detection method on the embeddings. To estimate the number of change points we propose using auxiliary labeled data.