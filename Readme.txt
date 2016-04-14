This is a large frame (1280x720) video of the simulated neural activity excited by repeated exposure to a short fractal video.

The Numenta NuPIC Cortical Learning Algorithm has many components. At the foundation is pattern input to the Spatial Pooler, which creates an output pattern of cortical neurons firing in response. The unsupervised learning of the neural model is an evolution of internal interconnections between the input and output patterns, starting from a random initialization. The intent is to simulate the neocortical workings of newborn mammal as it creates an organized response to unfamiliar perceptions.

These clips depict the learning behaviour of the Numenta NuPIC Spatial Pooler software in response to the gradual evolution of a complex pattern, a series of one hundred closely related Julia set fractal images, applied repeatedly to the input of the neocortical simulation software. The colorful fractal is the original image set, the black and white is a thresholded version that was the actual input data to the Spatial Pooler. The rapidly changing colored dots are the locations in the SP output where the simulated neurons are firing in response to each frame of the input.

Each time the SP "sees" the fractal images repeated again, it changes the pattern of neurons that fire as it "observes" more details about similarities and differences in the pattern sequence. The neurons that fire are initially clustered fairly closely toward the bottom of the frame, and gradually separate and move upward, ultimately adding firings in a horizontal region near the top of the frame for some sub-sequences of the input. This additional region moves vertically in a quasi-periodic manner at the end of the first clip.

The fractal input to the Spatial Pooler is a sequence of 100 images repeated cyclically fifty times, for a total of the 5000 frames in each video. The SP simulation is by no means finished changing at the end of the first clip, and longer sequences with the same input patterns continue to produce changing output behaviour for many, many frames. This abbreviated clip shows the beginning of the self-organizing behaviour of the NuPIC SP and gives a taste of quasi-periodic aspects of that behaviour that is common when repeating complex patterns. Toward the end of the first video there are definite differences in the neurons that fire during those parts of the input sequence that are visually different. Some of the beginning frames of the input continue to excite neurons at the bottom of the frame, throughout the evolution of learning. The neurons near the middle of the frame only begin to fire late in the sequence and are associated with greater discrimination between patterns at the height of complexity in the input sequence.

The second video does not pick up where the first one left off. Skipping 200 repeated cycles of the input fractal, the second clip starts at cycle 250 and runs again for 50 cycles. The patterns in the neural simulation have evolved and spread out. The pattern is still changing, but not as much or as quickly. At the beginning of the video there are two distinct horizontal lines in the formerly empty middle area, one near the bottom line, and one aproximately center. Slowly, as the sequence progresses the lower of the two gradually disintegrates as short segment move upward toward the center. Near the midpoint of the video the middle band contains only the one central line, with the waves from the top terminating with the line at the center. The very lowest line consolidates into a denser form as it moves upward. By the end of the video this stratification is much different from the beginning.

The third video is again 50 cycles through the input data, this time starting with cycle 550. There are few changes in the pattern, which now shows very strong visual correlation to the activity and complexity of the input variations. A wave of cell firings wash down from the top of the frame and are drawn back up as the input pattern peaks in complexity and the spirals expand and shrink. The bottom line has separated into three close horizontal lines, and the upper pattern that washes up and down is separating into a left and right pair of patterns. Although the cell firings are still changing, the essential organization is stable throughout this video.

The self-organization of the Spatial Pooler learning as it evolves toward a stable response is evident in these videos. The rapid rate of almost random change in the early stages is also clearly slowed at the end of 600 cycles. The visual synchronization of the neural response with the fractal input also becomes much stronger as the sequence progresses. Understanding based on examination of the lists of numbers representing the SP behaviour is greatly enhanced by a little dynamic graphical animation.

There are three spatial pooler runs that are depicted in these videos, hence the labels 01, 02, and 03.

SpTriImg* is the three combined images of the original color fractal, the thresholded black and white version of the fractal that was the actual input to the NuPIC Spatial Pooler, and the simulated neural response.

SpImg* is the Spatial Pooler output only, at a higher resolution, before it was combined with the input image.

The Img01 videos show the Spatial Pooler behaviour from the beginning, starting with the first exposure to the one hundred frame fractal. It ends at frame 5000, which is 50 cycles through the 100 frame fractal input pattern.

The Img02 videos are another sequence of 50 cycles through the fractal data, but starting at the 250th cycle.

The Img03 videos start at the 550th cycle and run through the 600th.

Cir01.mp4 is the original color video of the fractal input alone, and at higher resolution.

