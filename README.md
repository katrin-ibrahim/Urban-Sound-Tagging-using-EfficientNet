
# Urban Sound Tagging using EfficientNet
The purpose of this project is to investigate how urban audio samples in computer-readable
forms might be classified into the appropriate classes using an image transfer learning
model. As a baseline, the EfficientNet-B1 model is used, along with Log-mel Spectrogram feature representations. To improve
the baseline results,various audio data augmentation techniques are investigated.
The two notebooks available are for the ESC-50/ESC-10 dataset and the UrbanSound8k dataset.

## Best Results
- 94.25% on ESC-10
- 85.9% on ESC-50
- 76.5% on UrbanSound8k


## Authors

- [@katrin-ibrahim](https://github.com/katrin-ibrahim)

## Acknowledgements
- The model architecture was adapted from [J.Kim in the dcase 2020 challenge](https://dcase.community/documents/challenge2020/technical_reports/DCASE2020_JHKim_21_t5.pdf)


## Feedback

If you have any feedback, please reach out to me at katrinemadfathy@gmail.com


## To do 

- Experiment with larger network

- Experiment with class conditional data augmentation 

## License

[GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html)

