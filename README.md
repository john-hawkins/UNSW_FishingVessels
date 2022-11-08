# UNSW Project : Fishing Vessel Trajectory Clustering

To run the code in this project you will need the file drifting_longlines.csv from the RodneyProjects DropBox folder.

Data was originally downloaded from [Global Fishing Watch](https://globalfishingwatch.org/datasets-and-code/)

## Colab Execution

Copy this file into the root of the Google Drive.
Then open the notebook [cartoPy.ipynb](cartoPy.ipynb) in Google Colab.


## Local Execution

Copy the data file into the data directory (but change the path to your DropBox installation)

```
cp ~/Dropbox/RodneyProjects/Data/drifting_longlines.csv ./data/
```

Start with some simple data exploration to understand the data
and start processing it for later modelling. This Notebook contains
multiple experiments in understanding how we determine the initial
trajectory of the fishing vessels.

```
jupyter notebook exploration.ipynb
```



## Documentation

Rodney is suggesting that we look at implementing something similar to this
package to de-noise the trajectory data before using it in a model. That is
the goal of the clustering he has been suggesting.

https://cran.r-project.org/web/packages/trajectories/vignettes/article.pdf

We need to digest this and determine how to apply these ideas.



