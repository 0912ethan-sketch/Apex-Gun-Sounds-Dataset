# Apex-Gun-Sounds-Dataset
Dataset Documentation 

**[ 📥 Click here to Download the Full Dataset (dataset.zip) ](https://drive.google.com/file/d/1F09YEW-4Q0MDPbifyZ1fh2Q8Inw-z7ps/view?usp=sharing)**

## 2. Dataset Documentation
•	Data Type & Source: The dataset consists of audio recordings (.wav format) collected semi-automatically through game simulations in the Apex Legends "Firing Range".
•	Amount and Composition: The dataset contains roughly 700 one-second audio clips across three weapon classes: R-301, Flatline, and Volt.
•	Collection Conditions & Process: To ensure feature variance, 15 short video clips (approx. 45-60 seconds each) were recorded using OBS Studio capturing internal system audio. In-game voice lines and music were muted to prevent data contamination. Variables introduced during collection included varying distances, weapon attachments (e.g., barrel stabilizers), environmental locations (open field vs. indoor cave to introduce reverb), and firing patterns (full-auto vs. burst).
•	Cleanup & Preprocessing: The raw video files were batch-converted to audio using a Python script. A filtering mechanism was applied to slice the audio into 1-second chunks and discard chunks containing silence (volume below 0.01 threshold).
These audio files are sliced into 1-second chunks, ready to be converted into Mel-spectrograms for machine learning tasks.

