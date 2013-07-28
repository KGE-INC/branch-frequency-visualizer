branch-frequency-visualizer
===========================

In this project I've created a some what 'fractal' of a 'line branch'. This was mainly inspired after reading Chaos: Making a New Science by James Gleick. I also added functionality to allow it to generate a range of images from an audio file. It does this by increasing the angle on branches corresponding to the value found in the FFT data, hence higher frequencies would increase the angle of 'smaller' branches. (You will need to process the song first to generate the FFT data and from that you can generate the range of images). It's kind of like an music visualizer. Although it's not that accurately represented I find. VirtualDub was used to create the video file. And the Bass audio library was used to get FFT data. 
