# Instructions

1. Load the ipynb file into Google Colaboratory.
2. In the Paths cell, adjust WORK_DIR to point to the location of the project inside your Google drive. It is assumed that in this path, you have the following directory tree (where the experiment directories' names are arbitrary):
WORK_DIR
├───data
│    ├───Tatoeba
│    │   └───eng-fra.txt
│    └───WMT
│        ├───train.de.txt
│        └───train.en.txt
└───results
    ├───experiment01
    │   ├───decoder
    │   └───encoder
    ├───experiment02
    └───experiment03
3. Run all the cells up to the Run Pipeline section.
4. Mount the Google drive.
5. The Initialise Experiment cell controls the parameters of the experiment. Adjust them before running the cell.
6. The next two cells perform training (the first by iteration, the second by epoch). Whichever one you choose, adjust the length of the training sessions before running. Also note that the model can either be created or loaded from a saved experiment. If a new experiment is created, make sure to create its directory, otherwise the save operation will fail.
7. The Evaluate cell allows the testing of the model.

# Loading existing experiments

The repository contains completed experiments.
Each experiment directory contains a params.txt file. The content of this file can be copied to replace the content of the Initialise Experiment cell. Consequently, after initialising the experiment and calling experiment.loadModel(), the experiment should be loaded.
