# MRI Image Explorer for Medical Diagnosis

This project is designed to provide a user-friendly interface to explore MRI (Magnetic Resonance Imaging) images and their corresponding labels. The primary goal is to facilitate a better understanding of the medical images for clinicians and researchers. The project employs a simple but effective interactive interface where users can choose different slices and channels of the MRI images, helping in the diagnosis and study of conditions like tumours. The project uses Python specifically Jupyter Notebook and some of the libraries used are specific Jupyter Notebook usage so be sure to download the software to run the program as intended. 

The imaging data was obtained from the following website (https://decathlon-10.grand-challenge.org/), specifically the "Task01_BrainTumour.tar" file and is credited to the following academic paper: https://doi.org/10.1038/s41467-022-30695-9. 

I only included 2 of the files in each "Images" and "Label" folder because of the large size of each folder in its originality. 


Features
Interactive UI: Allows users to select specific files, layers, and channels for both MRI images and their corresponding labels.
Visual Insights: Renders the selected MRI image slice alongside its labeled version for immediate visual comparison.
Customizable: Can easily be extended to include more features like segmentation algorithms, statistical metrics, etc.
Technical Stack
Python: The core logic is written in Python.
Nibabel: For reading the NIfTI-1 format MRI images.
Matplotlib: For rendering the MRI image slices.
Ipywidgets: To create an interactive UI with sliders and dropdowns.
Glob: For file handling.
Prerequisites
Python 3.x
Nibabel
Matplotlib
Ipywidgets
Glob
Installation

Screenshots

<img width="882" alt="Screen Shot 2023-10-13 at 10 30 31 PM" src="https://github.com/AshishSara/Visualize-MRI-Data/assets/79825659/e8ea439b-3ac2-4c6a-aed1-d59c69bfc527">


Future Work
Add machine learning models for feature extraction and prediction.
Implement more advanced segmentation algorithms.

Contributing
Feel free to fork the project and submit a pull request with your changes!

License
This project is licensed under the MIT License 



Thank you!
