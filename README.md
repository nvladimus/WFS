# Control tools for a Shack-Hartmann wavefront sensor

## System requirements
Windows 7 or later, 32 or 64 bit.

LabView 2016 32-bit

[Jupyter Notebook](http://jupyter.org/install), recommended installation: Anaconda, Python 2.7, 32-bit.

[Thorlabs WFS150-7AR sensor software](https://www.thorlabs.de/software_pages/viewsoftwarepage.cfm?code=WFS), for drivers.

## Installation
Clone or download the repo to your local computer. Launch the LabView project file `WFS-control.lvproj`.
The Thorlabs drivers file `WFS_32.dll` should be already added to system path if you successfully installed Thorlabs software for the instrument.

For LabView project, run the `WFS_Thorlabs_testPanel.VI`, see below
![WFS_Thorlabs_testPanel.VI]("/screenshots/LV-tree.png")

For python control code, start with Jupyter notebook `Thorlabs-WFS-HelloWorld.ipynb`.

## Screenshot
![LabView front panel]("/screenshots/WFS_Thorlabs_testPanel.png")


## Acknowledgements
Thanks to John Taranto and Egbert Krause for help with calling the driver's DLL functions from Python.