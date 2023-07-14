**Cadenza Task 1**: Personalized Audio Processing
This project aims to tackle an exciting challenge in the field of audio processing, a part of The Cadenza Challenge. The task requires us to use Spleeter for audio separation and then apply personalized hearing corrections on each separated stream. The personalized hearing corrections are based on listener characteristics defined by an audiogram. These steps allow us to generate a remixed version of a song tailored to an individual's unique hearing characteristics.

Work done
In this project, we have:

Used Spleeter for Audio Separation: Spleeter, developed by Deezer, is a state-of-the-art source separation library. We've used it to separate the input songs into their individual 'stems' (vocals, drums, bass, and other).

Applied Personalized Hearing Corrections: Based on the characteristics of different listeners (defined by their audiograms), we applied a unique set of corrections to each of these stems. The corrections were made using the NAL-R method implemented in the clarity tool (an open-source library for hearing aid algorithm research). The corrections were applied to match the gain-frequency response to each listener's hearing abilities.

Managed Audio File Handling: In order to handle audio signals, we used libraries like soundfile to read and write audio files and numpy for mathematical operations.

Handled Computational Limitations: We encountered computational limitations due to the high order of filters and large audio files. To handle these, we used techniques like downsampling to reduce the data size without compromising on quality.

Explored Using Google Colab: The code was developed and run on Google Colab, a fantastic resource for leveraging high-powered cloud resources.

Worked with Git and GitHub: We used Git for version control and GitHub for hosting our project. All our project files have been uploaded to our GitHub repository for easy access and version control.
