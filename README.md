# Finite-Data-Acquisition-Analysis
This LabVIEW application is designed to generate a waveform consisting of 1000 data samples using basic function generator.vi and add noise with uniform white noise waveform.vi. It offers several features to configure, display, analyze, and manage data.

**Overview:**
This application uses basic function generator.vi to generate a waveform of 1000 data samples and uniform white noise waveform.vi to add noise to it.

**Features:**
**Configure Data:** Adjust waveform parameters such as Frequency, Signal Type, Offset, Amplitude, and Noise Amplitude.
**Acquire Data:** Display the configured data on waveform graph by pressing "Acquire Data."
**Analyze Data:** Use Mean.vi to calculate the mean value of the acquired data.
**Clear Graph:** Clear the generated waveform graph.
**Default Configurations:** Default settings are based on the data from the last program execution and stored in Configuration.ini.
If this file is deleted by any chance, default settings will be set as follows:
Signal Type: Sine Wave
Frequency: 15
Offset: 20
Amplitude: 2
Noise Amplitude: 1
**Save File:** Data is not saved automatically to prevent accidental storage. To save, press "Save File" and choose file format from txt, csv, or tdms.
**Open File Location?:** If this option is checked and followed by "Save File," the system file explorer will open and highlight the saved file..
**Read Data File:** Opens the system file explorer to select and read file.

**Additional Information:**
If the application crashes or is closed, the last acquired data will be displayed on the graph. Generated files are stored in Documents\Finite Data Acquisition and 
Analysis\Data files.
The application directory stores configuration.ini and recovery.bin files in the Configuration Files folder.
**Application Directory:** This refers to the location on the computer where the software is installed.

**Keyboard Shortcuts:**
Ctrl + O: Read Data File;
Ctrl + S: Save File;
Ctrl + Q: Quit;
Ctrl + I: Configure Data;
Ctrl + A: Acquire Data;
Ctrl + Shift + A: Analyze Data;
Ctrl + Shift + C: Clear Graph;
Ctrl + Shift + R: Default Configuration;
