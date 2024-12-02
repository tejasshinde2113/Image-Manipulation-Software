

# Image Processing Software

The Java-based Image Manipulation Application enables users to perform various operations on images, including loading, saving, and applying image processing techniques through a user-friendly interface. Here's a summary of the recent enhancements:

The source code of this project is in restricted mode, as per the instructor's guidelines to avoid one's code being misused.

Note: The code will be made available upon request. Email tejasshinde2113@gmail.com

## Demo


![8ih4ya](https://github.com/ameyagidh/ImageProcessingSoftware/assets/65457905/cd0f7c07-29dc-4cff-9ab2-8dc0cb949689)

**New Features:**
1. **Compression**: Supports creating compressed versions of images using the script command "compress percentage image-name dest-image-name".
2. **Histogram**: Generates an image representing the histogram of a given image, with size 256x256, including histograms for red, green, and blue channels as line graphs.
3. **Color Correction**: Allows color correction of an image by aligning meaningful peaks of its histogram.
4. **Levels Adjustment**: Supports adjusting levels of an image via the script command "levels-adjust b m w image-name dest-image-name", with parameters b, m, and w representing black, mid, and white values respectively.
5. **Split View**: Introduces split view functionality for blur, sharpen, sepia, greyscale, color correction, and levels adjustment operations. Users can preview changes before applying them.
6. **File Argument**: Accepts a script file as a command-line option ("-file name-of-script.txt") to run the script and exit. Allows interactive entry of script commands if no command-line options are provided.



**Exception Handling:**
Error conditions, such as misspelled commands or invalid arguments, are handled gracefully, providing informative feedback to users via pop-up messages.

**Overall Structure:**
Follows the Model-View-Controller (MVC) pattern, with enhancements based on Object-Oriented Programming (OOP) principles. The system retains support for all previous operations while accommodating new features seamlessly.

**Installation and Usage:**
Clone the repository, build the project, and run the application. The program accepts various commands for image manipulation and enhancement, allowing users to interactively execute operations or run scripts from provided files.

**Additional Notes:**
The GUI layout is designed to be reasonable, with components proportionally laid out for optimal user experience.

**Future Extensions:**
As the application evolves, it may introduce a dedicated view package for enhanced user interaction and additional features.
