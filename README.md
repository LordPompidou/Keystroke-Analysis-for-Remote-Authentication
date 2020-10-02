# Keystroke Analysis for Remote Authentication

This repository is where the research paper `Keystroke Analysis for Remote Authentication` by [Gabriel Padis](https://github.com/LordPompidou) and [Rim Zaafouri](https://github.com/rz160211), supervised by Dr Darragh O’Brien is made public.
In it is the final paper in pdf format, but also the literature review, the source datasets and the source code. We hope that this will be helpful to other when researching this topic.

## Usage

### What is here
* In `images/` are the images for the paper
* In `src/`
    * In `datasets/` is the used datasets, including the open dataset from Killourhy and Maxion
    * In `exports/` are exported graph from scripts and notebooks
    * In `network_gns3/` are the scripts to send and receive data, datasets that we generated from our simulations
    * `stats_jitter.py` & `stats_latency.py` are the statistics about our results
    * `Nearest_Neighbor.ipynb` & `Neural_Network.ipynb` are the research notebooks
    * `main.py` is the main script calling `Subject.py` and `DetectorNearestNeighbor.py` & `DetectorNeuralNetwork.py`

### What can you do
Anything really.

If you spot something, have a question, a remark or want to point out a mistake, feel free to do so.

Just don't steal and copy without referencing this work. The goal is to allow people to work on the same knowledge base.
