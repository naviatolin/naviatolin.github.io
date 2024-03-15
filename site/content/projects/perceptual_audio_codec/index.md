+++
image = "window_image.jpg"
date = "2024-03-15"
title = "Perceptual Audio Codec"
type = "gallery"
tags = "Audio Codec"
+++
In this project, we created an audio codec to improve the audio quality for low bit rates (96 kbps and
128 kbps) by implementing transient detection and block switching. Transient detection and block switching should help us remove the presence of pre-echo in the transient blocks which was the most noticeable artifact present in our original coder. Since block switching and transient detection can be quite bit demanding, we attempted to implement different entropy coders (Huffman coding and Arithmetic coding) to reduce the number of bits needed to encode our audio files.

[(Paper)](https://github.com/Audrey-Lee88/Perceptual_Audio_Codec/blob/main/paper/MUSIC422_Final_Report.pdf)

[(Code)](https://github.com/Audrey-Lee88/Perceptual_Audio_Codec/tree/main)