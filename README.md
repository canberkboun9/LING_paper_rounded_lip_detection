# Rounded Lip Detection System
A filter based detection system using [dlib library](https://github.com/davisking/dlib) and opencv. Main purpose is to detect a rounded lip while talking.

To use the code, you must download the pretrained model from the HuggingFace.

[HF Download Link](https://huggingface.co/public-data/dlib_face_landmark_model/blob/main/shape_predictor_68_face_landmarks.dat)

- Put the .dat file and your image to the same directory (or any directory, but, beware the pathing) with the code.
- For video testing purposes, there will be improvements in the code. It only creates frames from the video for now. 
- Further down the line, from the video, the score will be calculated and plotted against time.

- Also, for now, the score is not a normalized value and doesn't represent any meaning. Only that, the higher the score, the higher the probability. This will be improved.

![image](https://github.com/user-attachments/assets/3d26e6da-9231-4378-bfd7-12a5ed2b733a)
![image](https://github.com/user-attachments/assets/28239bd5-49de-4546-b358-268c10daf99c)
![image](https://github.com/user-attachments/assets/bb5fcda4-427a-4fb9-ac08-7ea9d1bd14f7)
![image](https://github.com/user-attachments/assets/c233fc7f-24fd-4af4-9c3a-ef2dcfa52df0)


![image](https://github.com/user-attachments/assets/d2a8afea-9587-425a-b80d-bced3d18d93f)
![image](https://github.com/user-attachments/assets/d154760f-1876-4306-909e-c3e3cc2cb853)
