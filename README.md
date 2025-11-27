Spoken Language Identification using CNN and Mel Spectrograms

Overview
It is often difficult to identify what language someone is speaking especially using only audio.
This project builds a CNN model that identifies the spoken language from an audio clip using mel spectrograms as an input.
The model was trained on six different languages from Mozilla Common Voice dataset.
Language used: German, Hindi, Arabic, Korean, Baoulé, and Irish.

Dataset Information
•	Source: Mozilla Common Voice
•	Total audio clips: ~30,000
•	Audio format: mp3
•	Sample rate: 16,000Hz

Methodology
•	Audio files were collected for each language.
•	Each audio file was converted into a mel spectrogram (a visual image of sound).
•	The spectrograms were used to train a CNN model.
•	The model learned patterns in speech such as frequency, rhythm, and tone.
•	Data augmentations techniques such as Gaussian noise, Time stretching, and Pitch shifting were applied.
•	Normalization was applied
•	Regularization and early stopping were used to prevent overfitting
•	When a new audio is given, the model predicts which language is being spoken.

Results
•	Validation accuracy: ~85%
•	Test accuracy: ~90%

Why This Project Matters
A language identification model like this can be useful for:
•	Speech translation systems
•	Multilingual customer support
•	Emergency services
•	Voice assistants
•	Linguistic research
Being able to detect language automatically helps improve communication in global systems.

Tools Used
•	Python
•	TensorFlow / Keras
•	Librosa
•	NumPy
•	Matplotlib
•	Google Colab

References
•	Singh, G., et al. (2021). Spoken language identification using deep learning. Computational Intelligence and Neuroscience.
•	Potla, S., & Vardhan, B. V. (2022). Spoken language identification using CNN with log mel spectrogram features in Indian context. International Journal of Advanced Trends in Computer Science and Engineering, 11(6), 273–279. https://doi.org/10.30534/ijatcse/2022/071162022
•	Mozilla Common Voice. (n.d.). Mozilla Common Voice dataset. https://commonvoice.mozilla.org
•	McFee, B., Raffel, C., Liang, D., Ellis, D. P. W., McVicar, M., Battenberg, E., & Nieto, O. (2015). Librosa: Audio and music signal analysis in Python. Proceedings of the 14th Python in Science Conference (SciPy).
•	Wolf-Monheim, F. (2024). Spectral and rhythm features for audio classification with deep convolutional neural networks. arXiv.
•	Librosa Developers. (n.d.). Librosa documentation. https://librosa.org
