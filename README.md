# Bionic-arm-
Responsible for EMG data acquisition with BITalino, processing signals using MATLAB and classification of signals into using ANN neural networks


A dataset of electromyography (EMG) signals was collected at the Robotics and Cobotics Department at Euromediterranean University of Fes, Morocco. The dataset includes EMG recordings from 40 participants, capturing six distinct hand movements using the BITalino sensor. Each participant contributed data through a structured acquisition process, executing five repetitions of each movement, each lasting five seconds. Post-acquisition, rigorous signal processing techniques, such as filtering and rectification, were meticulously applied to render the dataset analytically reliable. The dataset facilitates a range of applications, including gesture recognition, movement classification, and predictive modeling. Moreover, it serves as a foundational resource for training and validating machine learning algorithms, particularly in the domain of EMG-based human-computer interaction.

<p align="center">
<img width="800" height="448" alt="image" src="https://github.com/user-attachments/assets/573eb220-6f7c-4b62-832d-c648e043348f" />
</p>

## data collection

The data collection process began with a thorough selection of six distinct hand movements for analysis: Pronation, Like, Dislike, Grip, Supination, and Handshake.


<img width="349" alt="image" src="https://github.com/user-attachments/assets/10c432c5-9bcc-453f-ab5b-05e8975015b6">


The EMG recording session for each participant lasted 250 seconds and consisted of five cycles. 


<img width="318" alt="image" src="https://github.com/user-attachments/assets/aed95cd3-a928-4dc8-b2a5-4069f62d984a">

## Preprocess the EMG signals

The EMG signals were recorded at a 1 kHz sampling frequency in both raw and filtered formats. We conducted a Fourier Transform (FFT) analysis to identify the dominant frequency components of the signal, which allowed us to determine the appropriate cutoff frequencies for filtering. A 4thorder Butterworth bandpass filter with cutoff frequencies of 20 Hz and 450 Hz was designed and applied to eliminate unwanted frequencies and reduce noise, ensuring that only the frequencies of interest were retained.

<img width="305" alt="image" src="https://github.com/user-attachments/assets/1df18d11-fcbe-4a79-893f-0de051efd598">


## Contact

If you would like more information about this project, feel free to contact me at:  
**Email**: [bouchrasahel43@gmail.com](mailto:bouchrasahel43@gmail.com)


