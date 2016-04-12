This is a large frame (1280x720) video of the simulated neural activity excited by repeated exposure to a short fractal video.

The Numenta NuPIC Cortical Learning Algorithm has many components. At the foundation is pattern input to the Spatial Pooler, which creates an output pattern of cortical neurons firing in response. The unsupervised learning of the neural model is an evolution of internal interconnections between the input and output patterns, starting from a random initialization. The intent is to simulate the neocortical workings of newborn mammal as it creates an organized response to unfamiliar perceptions.

This clip depicts the learning behaviour of the Numenta NuPIC Spatial Pooler software in response to the gradual evolution of a complex pattern, a series of one hundred closely related Julia set fractal images, applied repeatedly to the input of the neocortical simulation software. The colorful fractal is the original image set, the black and white is a thresholded version that was the actual input to the Spatial Pooler. The rapidly changing colored dots are the locations in the SP output where the simulated neurons are firing in response to each frame of the input.

Each time the SP "sees" the fractal images repeated again, it changes the pattern of neurons that fire as it "observes" more details about similarities and differences in the pattern sequence. The neurons that fire are initially clustered fairly closely toward the bottom of the frame, and gradually separate and move upward, ultimately adding firings in a horizontal region near the top of the frame for some sub-sequences of the input. This additional region moves vertically in a quasi-periodic manner at the end of the clip.

The fractal input is a sequence of 100 images repeated cyclically fifty times, for a total of the 5000 frames in this video. The SP simulation is by no means finished changing and longer sequences with the same input patterns continue to produce changing output behaviour for many, many frames. This abbreviated clip shows the beginning of the self-organizing behaviour of the NuPIC SP and gives a taste of quasi-periodic aspects of that behaviour that is common when repeating complex patterns. Toward the end of the video there are definite differences in the neurons that fire during parts of the input sequence that are visually different. Some of the beginning frames of the input continue to excite neurons at the bottom of the frame, throughout the evolution of learning. The neurons near the middle of the frame only begin to fire late in the sequence and are associated with greater discrimination between patterns at the height of complexity in the input sequence.

SpTriImg.1280x720.mp4 is the three combined images of the original color fractal, the thresholded black and white version of the fractal that was the actual input to the NuPIC Spatial Pooler, and the simulated neural response.

Cir01.mp4 is the original color video of the fractal input alone, and at higher resolution.

SpImg01.mp4 is the Spatial Pooler output video alone at a higher resolution.


