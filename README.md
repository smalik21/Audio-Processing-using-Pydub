# Audio Processing using Pydub
This Google Colab notebook contains Python code for processing audio files using the Pydub library. The code requires the user to add the audio directory in the audio_dir variable and run all the cells in the notebook. The user can change the number of audio files required in the dataset and the minimum and maximum number of speakers in an audio file.

## Requirements
- Google Colab
- Pydub library for audio processing

## Usage
- Add the audio directory.
- Run all the cells in the notebook to import and process the audio files.
- Change the `num_files` variable to the number of audio files required in the dataset.
- Change the `min_speakers` and `max_speakers` variables to the minimum and maximum number of speakers required in an audio file.
- Use the `get_timestamps(labels[index])` function to return the timestamps for the occurrences of different speakers in the audio file. This function takes as input the audio file path and returns a dictionary of the form `{speaker_name: [start_time, end_time], ...}`.
