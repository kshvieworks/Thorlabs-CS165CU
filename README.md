# Thorlabs-CS165CU
Driving Thorlabs-CS165CU Scientific Camera using Windows SDK from Thorlabs and Python
- Prerequisite Environment: Python Interpreter Based on the Virtual Environment in the Project Directory
  - Tree Structure:
    - Thorlabs-CS165CU
        - python
            - venv
- Prerequisite Package: ```opencv-python``` ```numpy``` ```Pillow``` 
---
Step 1. Download and Install ```ThorCam``` from Thorlabs Web Site for Installing Thorlabs Camera Driver.
- https://www.thorlabs.com/software_pages/ViewSoftwarePage.cfm?Code=ThorCam
- File Name: ThorCam Software for 64-Bit Windows

Step 2. ```Download Windows SDK``` from the ```Programming Interfaces``` in the Tab of the Above Web Site.
- File Name: Windows SDK and Doc. for Scientific Camera

Step 3. Unzip the ```SDK Folder```.

Step 4. Open ```Terminal under Project venv``` and Change Current Path to the ```Python Toolkit Directory```
- Python Toolkit Location: ```Download Path```\Scientific_Camera_Interfaces_Windows-2.1\Scientific Camera Interfaces\SDK\Python Toolkit

Step 5. ```Install``` the Python Package.
- pip install thorlabs_tsi_camera_python_sdk_package.zip

Step 6. ```Copy``` the Directory Including Native DLL Files and ```Paste``` Them into the Installed Package Directory
- Native DLL Files Location: ```Download Path```\Scientific_Camera_Interfaces_Windows-2.1\Scientific Camera Interfaces\SDK\Native Toolkit\dlls\Native_64_lib
- The Package Directory:  ```Project Path```\python\venv\Lib\site-packages\thorlabs_tsi_sdk

Step 7. 