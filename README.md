# 1.NSMHT Dataset Description

Compared to fixed cameras, wearable cameras have time-varying non-specific view coverage and can be used to alternately observe people at different sites by varying the camera views. However, such view change of wearable cameras may introduce intervals of transitional frames without useful information, which brings new challenge for the important multiple object tracking (MOT) task. 

We do not find publicly available dataset with non-specific coverage switch-group tracking. Therefore, we use head-mounted GoPro to collect a new video dataset, which consists of 34 videos with length from 400 to 1,500 frames, in total 28,630 frames, taken at 5 different outdoor sites. Specifically, on 16 videos, it switches to tracking between crowd and non-crowd scenes; on 12 videos, it switches tracking between two groups of people; and on 6 videos, it switches tracking between three groups of people.

# 2.Download

Please download the dataset using the links below: [Baidu Yun](https://pan.baidu.com/s/1YqSQnps8uUHEFtoW79ONvA)(code:vwa9)

# 3.Content

Each video contains three folders and a profile: 

- "det" folder. This folder contains the detection results of video sequences.
- "gt" folder. This folder contains the annotation results of video sequences.
- "img1" folder. This folder contains the original images of  video sequence.
- "seqinfo.ini" file. This file contains the configuration information of video sequence.

# 4.LICENSE

- The images and the corresponding annotation results can only be used for ACADEMIC PURPOSES. NO COMERCIAL USE is allowed.
- Copyright © College of Computer Science, Tianjin University. All rights reserved.

# 5.Cite

Please cite the following paper if this dataset helps your research:

Sibo Wang, Ruize Han, Wei Feng, Song Wang. Multiple human tracking in non-specific coverage with wearable cameras.
