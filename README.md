# About our project:
Sarcasm detection presents a challenging task in natural language
processing due to its nuanced and context-dependent nature. In
this paper, we propose a comprehensive multi-modal framework
for sarcasm detection, leveraging textual analysis, tone recogni
tion, and visual processing. We extend the MUStARD dataset to
include audio and video components, providing a diverse and an
notated collection for model training and evaluation. Our approach
utilizes late fusion techniques to integrate information from dif
ferent modalities, enhancing the model’s accuracy and robustness.
Interestingly, we observe that omitting the visual aspect leads to a
notable increase in accuracy, prompting further exploration into
the dynamics of sarcasm detection. Our study underscores the im
portance of considering multiple cues in sarcasm detection and lays
the groundwork for future advancements in this field.

## Structure of our project:
- The audio_data contains the extracted .wav files of the selected audio clips.
- The scripts folder contains separate scripts for each analysis and model for each modality.
- The video_data folder will contain all the video clips that the master csv file utilizes.
- Sarcasm_Model_Dataset.csv is the file that includes the data that our model will do training/testing on.
- SarcasmDetectionModel.ipynb contains the master code for each modality analysis/model  and it also contains the final fusion code for our model.

# Self-evaluation
Our dataset was on the smaller side. If given more time, we would like to expand on the current MUStARD dataset to include more Naturalistic Data that are not soley based on American Sitcom. We would like to include more data from different cultures and regions. This would allow our model expand its cultural and regional diversity, thereby enhancing its generalizability and applicability across different linguistic and cultural contexts. Additionally, incorporating data from various sources beyond American sitcoms would provide a more comprehensive understanding of sarcasm across different cultural norms and communication styles. This expansion could involve collecting data from television shows, movies, social media platforms, and other sources that capture real-life interactions and expressions of sarcasm. By broadening the dataset in this way, our model would be better equipped to recognize and interpret sarcasm in a wide range of settings and cultural backgrounds.

We propose a multi-modal sarcasm detection framework that integrates textual analysis, tone recognition, and visual processing. Our approach extends the existing MUStARD dataset, a widely used resource for sarcasm detection research, to include audio and video components. By incorporating tone of voice and facial expressions from video clips of well-known North American sitcoms, our dataset provides a comprehensive and diverse set of examples for training and evaluating sarcasm detection models. Ultimately, we successfully trained a multi-modal model that leverages textual, tonal, and visual cues to accurately identify sarcasm.
