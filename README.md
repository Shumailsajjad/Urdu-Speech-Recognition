### Urdu-Speech-Recognition

#### Speech Processing Project

This project represents a continuation of my exploration into speech recognition models, albeit with a different problem nature and data collection approach. This unsupervised speech processing project employed a mixed-methods approach to develop an Urdu speech recognition model. It consisted of two main phases. 

In the data collection phase, I utilized Praat software to record 708 sentences, aiming to construct a phonetically rich Urdu corpus. Each sentence was recorded separately in a controlled environment, with a sampling frequency of 16000 Hz, and subsequently cleaned to remove any background noise.

Moving on to the analysis phase, the recordings were divided into 80:20 train-test sets. The training dataset underwent processing through a pre-trained wav2vec2 model to facilitate Urdu speech recognition. This process was repeated with different training weights on the test data, ultimately achieving a best word error rate of 0.63. 

This project provided valuable insights into building a qualitative dataset and leveraging it to develop an assistive model beneficial to low-literate Urdu-speaking populations.

## Dataset

[Drive Link of Recordings](https://drive.google.com/drive/folders/1Acb_PQ0MSvRHpF9EMSoy6x_5RgeryYnc)

## Files

- **Dataset and Summary.docx:** Summary document containing information about the recording device and the drive link of recordings.
- **Wav2Vec.ipynb:** Notebook detailing the training and testing of the wav2vec model on the audio data, including hyperparameter tuning.
- **Best Model Analysis:** Document highlighting the best model parameters and providing sample examples of audio-to-text classification from the best model.
