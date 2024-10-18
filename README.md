# Hyperspectral-Image-Simulation-Application-for-Alaska
__About the Application__   
True hyperspectral imagery, which captures a wide range of the electromagnetic spectrum with narrow spectral bands, is not as readily available as multispectral data. Satellites capable of capturing hyperspectral data are limited, making it challenging for researchers to access this valuable data regularly.

This application leverages Google Earth Engine to generate low-cost hyperspectral simulated Data from Sentinel-2 multispectral imagery, focusing on enhancing users ability to access hyperspectral data. Users can interactively select areas of interest within Alaska, adjust parameters such as cloud coverage, and choose specific image dates for detailed examination. The interface has tools for area of interest, sliders for filtering images based on cloud cover, and dropdowns for selecting dates. The application supports downloading and exporting of both Sentinel and Hyperspectral images and includes advanced functionalities like RGB and False Color Composite (FCC) visualizations download options. It’s designed to provide researchers, educators, and environmental scientists with a powerful tool for remote sensing and environmental monitoring, directly from their web browsers.

__Application URL__ : https://abadola.users.earthengine.app/view/hysim  

![image](https://github.com/user-attachments/assets/23516356-d1d9-4909-b67d-78577a4807ac)

For detailed instructions on using the application, refer to the [Hysim documentation.pdf](https://github.com/user-attachments/files/17289974/Hysim.documentation.pdf)    
The repository includes two files: Application.js and Access to code.js, which are designed to be executed in the Google Earth Engine Code Editor.
For setup instructions and guidance on running these files after download, please see the [Hysim_Application_Set_up_guide.docx](https://github.com/user-attachments/files/17422815/Hysim_Application_Set_up_guide.docx)

Link to the GEE Code Editor : https://code.earthengine.google.com/
To use the Google Earth Engine (GEE) Code Editor, you need to have an active account. You can register for an account using this link : https://code.earthengine.google.com/register.

Alternatively ,You can directly download the folder Alaska_Hysim (which contains the above two files) on your local machine by running the following the command on your git bash.    
__git clone https://earthengine.googlesource.com/users/abadola/HySim__  
To do this, navigate to the directory where you'd like to download the folder in Git Bash, and then run the command.  
For example, if you want to download it to your Desktop, you can move to the Desktop by using the command:  
~cd Desktop  
After you're in the desired location, simply run the clone command above to download the repository.
Once downloaded follow the instrcutions in Google Earth Engine Application setup guide : [Hysim_Application_Set_up_guide.docx](https://github.com/user-attachments/files/17422816/Hysim_Application_Set_up_guide.docx)
