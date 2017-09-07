# Using the BOSS

The [BOSS](https://github.com/jhuapl-boss/) is a cloud based spatial database store that runs on Amazon Web Services.

NeuroData has its own deployment of the BOSS.
<https://api.boss.neurodata.io/v1/mgmt/>

## Create a login

1. Create a user at the following website <https://api.boss.neurodata.io/v1/mgmt/>
1. Decide on a group name (format: `ndd17_NAME`)

## Getting access to data

### Tell Ben/Eric

1. Data you will be accessing (or problem you will be working on - can figure out which data to give you access to)
1. The group name

### What we will do

1. Give the group a collection with full admin access
    1. Any member should be able to create experiments and channels inside this collection
1. Give read access to the data you will be playing with

## Accessing data

1. [Intern](https://github.com/jhuapl-boss/intern) - Python 2/3 module for interacting with the BOSS
    1. Downloading/uploading data including annotations
    1. Uploading should be done in chunks of 16 z at a time to avoid write locks
    1. Annotation uploads should be limited to < 2000
1. [Ingest large vol](https://github.com/neurodata-dev/ingest_large_vol) - Command line program for _image_ ingest of TIFF files
1. [ndwebtools](https://neurodata.io/tools/ndwebtools/) - tools that could be useful specifically in regard to data on the BOSS
    1. TIFF image cutouts for imaging data
    1. links to NeuroDataViz specific to data resources
    1. bookmarklet to navigate from NeuroDataViz to the image cutout form
    1. integration with NeuroData's data ingest exploratory data analysis/visualization
1. [ndviz](https://viz.boss.neurodata.io/) - Web application for looking at the data in the BOSS
    1. recommend you use ndwebtools to generate the links for a channel to ndviz

## Gotchas

1. Downsampling may not work
1. Everything should be supercube (512x512x16) aligned for best outcome
1. Annotation uploads should be done with care (< 2000) supported

## Contact info

ben  
Slack: @benfalk

eric  
Slack: @perlman