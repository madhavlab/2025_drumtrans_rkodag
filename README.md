### Overview

This repository focuses on **Meta-Learning-based Percussion Transcription** and **Tala Identification** using low-resource audio data. The two primary tasks include:

1. **Percussion Transcription**:

   - **Tabla Stroke Transcription (TST)**: Identifying and classifying Tabla strokes, along with their timing information,
      1. From Tabla solo recordings.
      2. From complete concert audio, including melodic instruments and the singer's voice.

   - **Automatic Drum Transcription (ADT)**: Extracting drum strokes and their timing information from drum audio tracks.
      1.  Drum Only Transcription (DTD): Transcription of drum strokes in isolation.
      2.  Drums in Presence of Other Percussion (DTP): Transcribing drums in the presence of other percussion instruments.
      3.  Drum in Melodic Instruments (DTM): Transcribing drums alongside melodic instruments.

2. **Tala Identification**:

   - Recognizing and analyzing rhythmic cycles (Tala) in Hindustani classical music.

___

### 


To facilitate research in these areas, this repository includes:

  1.  **Presentation**: A PowerPoint file that explains key concepts of rhythm in Hindustani music, including the structure of Tala.

  2.  **Synthetic_Mridangam_Stroke_Dataset_D_M**: A curated dataset of synthetic Mridangam strokes for audio research and analysis.
      

___

[Download Synthetic_Mridangam_Stroke_Dataset_D_M](https://iitk-my.sharepoint.com/:f:/g/personal/rkodag_iitk_ac_in/Esz9ax0h4jhDgRsY_qv_KbEB_TkYsfBnfKCYPqPiNeeRog?e=6nSbwO)
___
The dataset contains synthetic audio samples of Mridangam strokes.  The Mridangam, a prominent South Indian percussion instrument, is widely used in Carnatic music and has distinctive rhythmic patterns.

          Synthetic_Mridangam_Stroke_D_M/
      
              ├── Audio/            # Audio files for 10 classes of strokes
              
              ├── Onsets_10_Classes/     # Onset files for 10 stroke classes
              
              ├── Onsets_11_Classes/     # Onset files for 11 stroke classes (including silence class)
              
              └── README.md              # Additional details about the dataset

    Each main folder contains subfolders structured as follows:
          o	  Audio, Onsets_10_Classes, Onsets_11_Classes:
          o	  Each subfolder consists of 6 tonic folders: B, C, C#, D, D#, and E.
          o	  Each tonic folder contains 120 files, totaling 720 files per main folder

___

*The codes will be uploaded soon. 

     

