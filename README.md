# Underwater_image_restoration

This project takes underwater image as the input and some restoration and enhancement techniques are applied to it and the result will be obtained as the final image.
Steps invloved:
1: Input is taken.
2. Blue-green channels are recovered via dehazing algorithm based on an extension and modification of Dark Channel Prior algorithm.
3. Then, red channel is corrected following the Gray-World assumption theory.
4. Finally, in order to resolve the problem which some recovered image regions may look too dim or too bright, an adaptive exposure map is built.


