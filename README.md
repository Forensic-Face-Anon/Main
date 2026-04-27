# Forensic Face Anonymisation with Micro-Expression Retention

<p align="center">
  Ng Junhao Marcus | Pham Hong Quan Rose Evangeline Anne Dagman Destor Douglas Chun-hao Tan
</p>

<p align="center">
  (Team 1)
</p>

## Abstract
Facial anonymisation is commonly used to protect the identity of witnesses in legal and forensic video testimony. However, conventional methods such as blurring, pixelation, and back-lit shadowing often suppress facial dynamics that may remain relevant for credibility assessment and human interpretation. 

This project studies face anonymisation as a privacy--utility trade-off in forensic, human-facing settings, where the goal is not only to conceal identity but also preserve non-identity facial signals.

<img src="assets/pipeline.png" width="80%">

We compare four anonymisation strategies across identity leakage, micro-expression fidelity, usability, and deployment cost, focusing on whether anonymised representations remain interpretable for human observers in legal proceedings while reducing the risk of identity recovery. 

Our results frame forensic face anonymisation as a reproducible privacy--micro-expression--utility benchmark and indicate that representation-level approaches can offer a more balanced alternative to conventional visual redaction.


## Anonymisation Pipeline

### 1. Landmark to 3D Avatar Mapping (LivePortrait)
See repository:  
Virtual environment: https://console.paperspace.com/tvddx1t71y/notebook/r8zlkxkulcuedct  
See results:  [OneDrive file](https://sutdapac-my.sharepoint.com/:f:/g/personal/rose_destor_mymail_sutd_edu_sg/IgAei8FaMV5rT6URxU2SqBf8AUjxDFGTrZOntO3TriQag2Q?e=hoMHGB)


### 2. Optical Flow (FacialFlowNet / DecFlow)
See repository:  
Virtual environment: https://console.paperspace.com/tvddx1t71y/notebook/rlvy7kqvxkdnp7r
See results:  [OneDrive file](https://sutdapac-my.sharepoint.com/:f:/g/personal/rose_destor_mymail_sutd_edu_sg/IgByiGLOv2xDR7aU_6zg7pE0AT_lnugGXW18ah0bBA8P9sM?e=9Ds6kB)

### 3. Binary Masking with Overlaid Keypoints (Masked Piper)
See repository:  
Virtual environment: https://console.paperspace.com/tvddx1t71y/notebook/rysrlfen5qivr3l
See results:  [OneDrive file](https://sutdapac-my.sharepoint.com/:f:/g/personal/rose_destor_mymail_sutd_edu_sg/IgArZAWOlCPFT5-2-3fykXJhARc_WyssnPIOWtJAdkMHy2M?e=4OGcRZ)

### 4. Gaussian Blurring with Overlaid Keypoints (MediaPipe)
See repository: https://github.com/Hypernating/face-anonymisation  
See results:  [OneDrive file](https://sutdapac-my.sharepoint.com/:f:/g/personal/rose_destor_mymail_sutd_edu_sg/IgARLyoYKXTcQqLe2x4xgjsvAWDn0sJhlm7zvpsfLkyxCdo?e=rLmByE)

## Evaluation

### 1. Cosine Similarity
See repository:   
Virtual environment: https://console.paperspace.com/tvddx1t71y/notebook/rxj8b5dmq75sqos  

### 2. Human Evaluation