# PreviousWork
A bit of code that I have used in a previous project.

The MP4 file is a video of the dissolution process of one of the tablets used in the project. The dissolution was imaged using SDi2 apparatus, in 3 different media, at two different wavelengths. The frames obtained were converted to 3D numpy arrays
containing R/G/B values of particular pixels, and finally fed into different CNN architectures, including a VGGNet-inspired architecture as well as a GoogleNet-inspired architecture (Python scripts provided for these two in the repository).

The models were developed with the intention to use the image data to predict In Vivo blood concentration of a specific drug, after oral administration.
