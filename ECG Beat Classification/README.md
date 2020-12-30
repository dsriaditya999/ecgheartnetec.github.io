# ECG Beat Classification

This folder contains various experiments corresponding to the ECG Beat Classification using HeartNetEC model (as mentioned in the paper).

The following is a list of files present in this folder, with a brief description :

- **ECG_BeatClassification_RawData.ipynb** - A python notebook consisting of experiments corresponding to training and evaluation of ECG Beat Classification using raw data (without denoising) on Physionet's MIT BIH Arrhythmia Database. Note that this a Google Colab Notebook.

- **ECG_BeatClassification_DenoisedData.ipynb** - A python notebook consisting of experiments corresponding to training and evaluation of ECG Beat Classification using denoised data (raw data from Physionet's MIT BIH Arrhythmia Database passed through the denoising block). Note that this notebook also consists of the ablation experiments.

- **ECG_EventClassification_CPSC.ipynb** - A python notebook consisting of experiments corresponding to training and evaluation of ECG Event Classification using CPSC-2018 dataset.

- **ECG_BeatClassification_NoiseAnalysis.ipynb** - A python notebook consisting of experiments corresponding to Noise Analysis of HeartNetEC model for determining its robustness.

- **NoiseAnalysis.xlsx** - An excel document consisting of data processed used for noise analysis visualization. 

- **ECG_BeatClassification_NoiseAnalysis_Visualization.ipynb** - A python notebook consisting of code for visualizing various plots for Noise Analysis.

