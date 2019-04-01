# Chord detection on Jazz Audio-Aligned Harmony(JAAH) dataset

A comparison between two chord detection algorithms provided by Essentia library based on JAAH dataset. 

## Environment Requirements

To run this notebook, you should have installed following libraries:
* Essentia, https://essentia.upf.edu/documentation/
* Mir_eval, https://pypi.org/project/mir_eval/
* Numpy, http://www.numpy.org/
* Pandas, https://pandas.pydata.org/
* Matplotlib, https://matplotlib.org/
* Seaborn, https://seaborn.pydata.org/
* Music21, https://web.mit.edu/music21/

It's recommended to run on a docker environment, which could be found there: https://github.com/MTG/MIR-toolbox-docker.

In case you want to install the depencies manually, you can run the following line:

`pip install numpy matplotlib pandas seaborn music21 mir_eval`

For installing essentia you can follow this document: https://essentia.upf.edu/documentation/installing.html


## Dataset
We are using the JAAH Dataset, particularly the transcriptions in `.lab` format. 




*Note that we did not include the audio files from JAAH dataset, since it will be avaliable on Dunya soon.* 

We are already providing the results of our ACE estimations inside the `./results/` folder. The code will check if the .json results exist to avoid processing the files again.

In case you would like to run the code and extract the features yourself, please locate the audio files in .flac format in the `./audios/` folder. You should also delete the provided results before processing the audio tracks.

For more information about JAAH dataset, see: https://github.com/MTG/JAAH

For more information about Dunya, see: https://dunya.compmusic.upf.edu/
