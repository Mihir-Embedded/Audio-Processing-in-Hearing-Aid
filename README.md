# Audio-Processing-in-Hearing-Aid
   - Designed and implemented Digital Signal Processing (DSP) algorithms to filter and amplify sound signals.
   - Evaluated various audio processing techniques to enhance clarity and reduce noise.
   - Conducted extensive testing to ensure the hearing aid's reliability and effectiveness under different environmental conditions.
Audio-Processing-in-Hearing-Aid-using-MATLAB
Audio Processing in Hearing Aid This project enhances audio clarity for hearing-impaired users using Digital Signal Processing (DSP) techniques. It includes noise reduction and signal amplification, implemented in Embedded C on a microcontroller. MATLAB was used for DSP algorithm simulation and real-time testing for improved speech clarity.

Block Schematic
![image](https://github.com/user-attachments/assets/30515c22-2f0e-40ac-bb7c-c6c327d84dff)

The above figure is the block diagram for the MATLAB implementation of Digital Hearing Aid System. The input speech signal takes the form of human voice. The input speech signal will pass through several functions i.e., noise addition, noise reduction filter, frequency shaper and amplitude compression before producing an adjusted output speech signal which is audible to the hearing-impaired person. As described in the flow chart the incoming signal is amplified with a gain required for the impaired individual then the signal is de-noised using low pass filter then passed through process of frequency shaping and amplitude compressor to keep the amplitude within the limit.
