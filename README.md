# FYP_GenreClassification
This program is able to detect the genre of an audio sample. The main intention is that it be used to detect the genres of songs generated by OpenAI's Jukebox and as such modifications have been made. This includes limitations such as that the program is only able to predict WAV files of 30 seconds in length.

It was trained using the FMA_Medium dataset, but selected data was used. Songs from the following genres were taken:

*Folk
*Pop
*Rock
*Country
*Classical
*Jazz
*Hiphop

Furthermore, due to time and resource constraints and to have a balanced dataset, the first 100 songs were taken. Each 30 second song was split into 3. The final model was trained on 2100 song snippets.

MIR techniques such as MFCC were used to allow the model to differentiate songs between multiple genres.
