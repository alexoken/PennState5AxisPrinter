# PennState5AxisPrinter
The Penn State 3D Printing Club's & OpenBuild Club's 5 Axis Printer official repository

# Overview
The goal of this repository is to build the documentation for a 5 axis printer to make it easier for everyone to build a 5 axis printer with easier instructions. This is done by mainly reverse engineering a CAD file given by Daniel Brogan from his designs in colloboration with Fractal Robotics.

# Notice
This repository is mainly for tracking and working on documentation for a different repository. [This is the link to the Fractal-5-Pro](https://github.com/fractalrobotics/Fractal-5-Pro.) This repository will most likely be closed and combined with the Fractal repository once documentation is completed.

# Contributing & Pushing with Git & Git LFS
Because of the nature of 3D models and their large file size, we use Git LFS (Large File Storage) in order to be able to upload larger files. **Pull requests that do not use LFS will not be accepted.**
## Installation
1. If on Windows install Git LFS [here](https://git-lfs.com/)
   or if on Mac/Linux
```
brew install git-lfs          # macOS
sudo apt install git-lfs      # Debian/Ubuntu
```
3. Enable once per machine
```
git lfs install
```
5. Make sure to track all file types neccesary (.stl, .3mf, etc.)
```
git lfs track "*.filetype"
```
4. Push changes now like a regular commit
