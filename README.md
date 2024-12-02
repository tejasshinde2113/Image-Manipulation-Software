

# Image Processing Software

The Java-based Image Manipulation Application enables users to perform various operations on images, including loading, saving, and applying image processing techniques through a user-friendly interface. Here's a summary of the recent enhancements:

The source code of this project is in restricted mode, as per the instructor's guidelines to avoid one's code being misused.

Note: The code will be made available upon request. Email tejasshinde2113@gmail.com

## Demo


![Alt Text](https://github.com/tejasshinde2113/Image-Manipulation-Software/raw/main/Manipulated%20Images/GUI1.jpg)

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



How to use our program -

Our program incorporates 3 ways to use it.
There is a Program.jar file present in the res folder along with the boat.jpg image.
Please download it and load these 2 files into a folder.
Open the terminal there to run the jar file.

1. To open interactive mode, type command 'java -jar Program.jar -text'
   This will open the interactive mode and you can type the command as mentioned in the useme.txt
   file to do the manipulations. Type 'quit' to exit from the interactive mode.
2. To run a script file, type command 'java -jar Program.jar -file [script-file-name.extension]'
   This will execute the entire script file.
3. To open the GUI, type command 'java -jar Program.jar'


How to use our GUI -

There 3 main buttons and one dropdown on our GUI.

1. Button 1 - Load
   This will open the fileopener in which you need to find the path of your image and select it
   inorder for you to open it. Our current GUI supports images with extension .jpg, .png, .ppm
   files. Once a image is loaded, you can see the image and it's corresponding histogram on the
   screen.
   If you load a file and apply some manipulations on it, if you try to load a another file without
   saving the current file, If the currently shown image is not saved,
   the program should prompt the user accordingly.

2. Button 2 - Save
   This will open the fileopener in which you need to find the path of your image where you wish to
   save it.
   Below you will need to add a file name and extension of the image before saving it.
   Our current GUI supports images with extension .jpg, .png, .ppm files.

3. Button 3 - Apply
   This button will apply the manipulation selected from the dropdown. If the parameters provided
   are invalid, the GUI will abort the manipulation and display a appropriate message to the user.
   On the successful execution of the image, the image and the histogram on the GUI will be updated
   accordingly.

4. Dropdown
   This dropdown contains all the manipulation that our current GUI supports. A user needs to select a
   appropriate manipulation from the dropdown before pressing on the apply button to see the changes.
   If a specific manipulation requires more input fields from the user, appropriate test fields will
   be displayed to it's right. Eg : on selecting adjust levels, 3 b,m,w fields will be populated on the
   screen.

5. Split % text field.
   For the manipulations that support split, in order to preview the split the user need to enter a
   split integer percentage ranging from 0 to 100
   To view the split preview of a manipulation, click on the image populated on the screen and
   press "s" keyword. Once the "s" key is released, the image will exit from the split view.
   If a manipulation does not support split view, appropriate error will be displayed to the user.

