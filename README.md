# 3D-Statistical-Texture-Analysis-Toolbox-v1.3
A package providing MATLAB programming tools and GUI for 3D statistical texture analysis

Texture analysis methods: Histogram, Gray-level Co-occurrence Matrix, Gray-level Run-Length Matrix

===========================================================================

Instruction for Installation

Texture_Analysis_Toolbox Executable : Please dowlload it following this link:

- Please double click the Texture_Analysis_Toolbox_Installer.exe file and follow the instruction to install the texture analysis tool.

  Note: Version 9.4 (R2018a) of the MATLAB Runtime will be installed following software Texture_Analysis_Toolbox_v1.3


Definitions

For information on deployment terminology, go to
http://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.

==========================================================================

Instructions for Use:

Step-1: Upload Image data converted in Nifty format (.nii/.nii.gz) after pressing the 'Select Image' button. 
        If the image is 4-dimensional, please enter the value (1/2/3) for the 4th dimension to be processed.
        Press the 'Show Image' button to display the image. 
        Next, press the 'Select Mask' button to browse the corresponding Mask (ROI) file (in .nii/.nii.gz format).
        The mask will be displayed. You can scroll through the slices by moving the scrollbar.   

Step-2: Select the denoising method as required. The message stating completion of processing will be displayed in the adjacent text box. 

Step-3: Enter the values (in mm) for the slice in-plane resolution, slice-gap for isotropic voxelization and 
        the number of gray levels for intensity discretization.
        Then press the 'Prepare Volume' button. The message stating completion of processing will be displayed in the adjacent text box. 

Step-4: Select the Texture analysis methods to evaluate the features. The message stating completion of processing will be displayed in the adjacent text box.
        The textural features under each method will be saved in a separate Excel file in the same directory (folder) as the data file.
        after processing a data set, you can press 'Clear All' button to clear the previously entered data and upload new data for processing.


Disclaimer: This toolbox can be used only for research or non-commercial 
purposes. Authors are not liable for any clinical use of it, authors could 
not be held responsible.

If you have any queries or suggestions about this package, kindly contact 
Dr. Amit Mehndiratta, Indian Institute of Technology Delhi, India.
E-mail: amehndiratta@cbme.iitd.ac.in, amit.mehndiratta@keble.oxon.org.

Copyright © 2024 IIT Delhi, India
Built on code by: @EshaBaidyaKayal

==========================================================================



