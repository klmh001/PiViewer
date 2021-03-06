# PiViewer
PiViewer: an open-source tool for automated detection and display of pi-pi interactions.  
The aromatic ring perception and the pi-pi interaction identification is implemented by using Python, NumPy, and the Python wrapper library of OpenBabel. PyMOL is selected as the main GUI for the 3D display of protein/ligand molecular structures and the pi-pi interactions as it is a popular open-source molecular visualization system and supports python for module/plugin development. The entire function can be installed as a PyMOL plugin.

### Dependencies
- Python 2.x/3.x
- NumPy
- Openbabel and Pybel (Python wrapper)
- PyMOL (optional if GUI needed)

### Installation
To install this tool, firstly install all of its dependencies (Python 2.x/3.x, Numpy, Pybel, and PyMOL). Then, open PyMOL->Plugin and install the plugin file. After installation, restart PyMOL and run PiViewer from the "Plugin" menu.

### Preview
![Demo](https://github.com/klmh001/PiViewer/raw/master/Demo.png)

### How to cite

Liu Y, Ao X, Wang Q, Wang J, Ge H. PiViewer: An open-source tool for automated detection and display of π–π interactions. Chem Biol Drug Des. 2018;00:1–6. https://doi.org/10.1111/cbdd.13340

- Please cite the paper if you find the tool useful.
- Please send feedback to gehuchina*AT*gmail.com.
