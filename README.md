# DAVEnet Pytorch

Implementation in Pytorch of the DAVEnet (Deep Audio-Visual Embedding network) model, as described in

David Harwath, Adrià Recasens, Dídac Surís, Galen Chuang, Antonio Torralba, and James Glass, "Jointly Discovering Visual Objects and Spoken Words from Raw Sensory Input," ECCV 2018

## Requirements

- pytorch
- torchvision
- librosa

## Data

You will need the PlacesAudio400k spoken caption corpus in addition to the Places205 image dataset:

http://groups.csail.mit.edu/sls/downloads/placesaudio/

http://places.csail.mit.edu/

Please follow the instructions provided in the PlacesAudio400k download package with respect to how to specify the paths to the datasets in the datafiles/[train,val].json files.

## Model Training

python run.py --data-train datafiles/train.json --data-val datafiles/val.json

See the run.py script for more training options.

## License

This code is distributed under the BSD license.