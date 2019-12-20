# TennisVideoActionClassification
First add the Video_RGB folder of the THETIS dataset to this directory (in Google Drive).
Then run one of the 'DataPreprocess.ipynb' notebooks in Google Colab, depending on which of the data extractors you are planning to test.
Once this is done, you should have a 'DataFeatures.npy' file, and a 'Labels.npy' file within the VIDEO_RGB folder.
Now if you plan to train an LSTM, run the 'LSTM_Video.ipynb' notebook, and choose the desired features and LSTM depth from within the notebook itself. You should be able to view and save a confusion matrix after running this.

Finally, if you plan to train just the single fully connected layer on the time-averaged features, run 'TimeAveraged.ipynb' notebook, and choose the desired feature extractor from within the notebook itself. You should be able to view and save a confusion matrix after running this.
