# Tabular Playground Series - June 2021

This GitHub repository contains the notebooks, the models and most of the submissions that have been done while participating to the Kaggle Tabular Playground Series of June 2021. The Tabular Playground competitions is a new experiment initiated by Kaggle in 2021. It consists of competitions launched on the first of every month and that ends the first of the next month. This one, as the title suggested, is the one that took place in June. The information for this competition can be found on [Kaggle](https://www.kaggle.com/c/tabular-playground-series-jun-2021).

## Data Description

_Quoting Kaggle website_

The dataset is used for this competition is synthetic, but based on a real dataset and generated using a CTGAN. The original dataset deals with predicting the category on an eCommerce product given various attributes about the listing. Although the features are anonymized, they have properties relating to real-world features.

## Evaluation Metric

For this competition, the metric is imposed: the __multi-class logarithmic loss__

## Notes

The Repository contains several branches that are associated with various models/investigations I tested. Here is a list of the branches, with the associated multi-class logarithmic loss score estimation on the test set (the lower the better):
 1. gradient-boosting          - 1.75809
 2. xgboost                    - 1.75629
 3. neural-network-bseline     - 1.74487
 4. neural-network-hypertuning - 1.74514
 5. neural-network-2conv       - 1.74622
 6. neural-network-4dense      - 1.74652
 7. neural-network-resnet-like - 1.74473

The model with the best performance (neural-network-resnet-like) has been merged to the master branch.

