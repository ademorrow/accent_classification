This study used an XGBoost regression model to perform
accent classification on African American English (AEE) audio
recordings collected in the Corpus of Regional African
American Language (CORAAL). Audio features selected for
model training included 20 mel frequency cepstrum
coefficients, the mel spectrogram, spectral rolloffs, the
complete ComParE 2016 feature set, power normalized cepstral
coefficients (PNCC), and perceptual linear prediction (PLP)
features.
The CORAAL dataset contained speakers from five distinct
United States cities: Rochester, NY, New York, NY (lower east
side of Manhattan), Washington, DC, Princeville, NC, and
Valdosta, GA. Although each city contains hundreds of audio
files, the number of unique speakers is extremely small. But as
a study in feature performance on “clean” and “noisy” audio,
this corpus is large enough to show trends in model
performance between the two test sets.
Two models were trained for this study. The first model was
trained on the raw audio files. The second model was trained
on an augmented training set with additional time shifted, speed
altered, and pitch altered audio files to help correct extreme
skew in the dataset. Accuracies, feature performance, and test
results in both clean and noisy data will be reported for both
models. Additionally, inference testing was performed on a
blind set of clean and noisy data to test generalization of the
augmented model. While overall accuracy was robust on clean
augmented data, noisy data and inference data performed
poorly. This model proves that feature selection alone is not
sufficient to create a robust AAE accent classification model.
