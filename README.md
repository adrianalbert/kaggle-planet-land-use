# kaggle-planet-land-use

This repository contains experiments for Kaggle's competition on identifying deforestation in the Amazon Basin using Planet imagery.

## Running notes on goals and approach

* how to treat noisy class labels? This seems like a very relevant research question.

## Updates and useful info from discussion forum

* the initial release of data gives TIFF headers which could be used to retrieve label information for test images if they are nearby any training image (i.e., in the same scene) as explained here: https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/discussion/32091
* some participants have likely used this info to advantage
** organizers stated they will release a new 'clean' set of images soon (is this represented in whats available for download now?)
