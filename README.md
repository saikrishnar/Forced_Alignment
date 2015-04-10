# Forced_Alignment


Extracting the attachment must yield, among others a run.sh. Running this file should be enough ideally, assuming that kaldi is installed.

However, the path to the dataset need to be changed.  Precisely, the line 26 should be pointing to the folder containing the  wavefiles.

Right now, it reads :

DATA=/home/neuron/saikrishna/Documents/GSoc_15/Implementation_kaldi/test_waves.

