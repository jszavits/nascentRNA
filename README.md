# Predicting variability in nascent RNA from transcription initiation kinetics

This is supplemental material accompanying paper [Predicting variability in nascent RNA from transcription initiation kinetics](https://doi.org/10.1101/2022.03.30.486441). Here you can find the computer code that predicts nascent RNA number distribution from the distribution of the times between successive transcription initiation events. The assumption is that transcription elongation takes a fixed amount of time to finish, whereas the only two assumptions on the transcription initiation kinetics are that the initiation time distribution does not change over time, and that there is no transcriptional memory between initiation events.

The files are organised as follows:
| File | Type | Description |
|-----------|-----------|-------------|
|`eukaryotic-transcription-SSA.ipynb`|Jupyter notebook file with Julia code| The program computes the initiation time distribution and the nascent RNA distribution using stochastic simulations for a stepwise model of eukaryotic transcription. |
|`eukaryotic-transcription-exact.nb`|Mathematica notebook file| The program computes the initiation time distribution and the nascent RNA distribution using inverse Laplace transform for a stepwise model of eukaryotic transcription.|

