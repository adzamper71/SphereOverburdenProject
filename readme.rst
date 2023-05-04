SPHERE-OB Airborne EM modelling 
====

SPHERE-OB (sphere-overburden) is a python program developed to calculate and plot the airborne TDEM response of a sphere or ‘dipping sphere’ underlying conductive overburden. 
The response is calculated using the semi-analytic solution set presented in Desmerais & Smith (2016), this solution set is computationally efficient and allows the user to model a thin sheet by artificially restricting current flow to parallel planes within an anisotropic sphere.

Installation
====

SPHERE-OB can be installed with pip + git using::

	pip install git+https://github.com/adzamper71/SPHEREOB

Alternatively, the repository can be manually downloaded and installed using the install script, i.e., by navigating to the SPHERE-OB folder and running::

	python setup.py install

Once installed, the GUI can be launched from the command line as::

	SPHEREOB
	
If you are an anaconda user and do not have python added to path you can install the conda environment by downloading this directory, navigating to the directory in windows explorer and running the install_update.bat. After this, open an anaconda prompt and activate the environment with the following::
	
	conda activate sphereob
	
Next navigate to the SphereOverburdenProject directory in the anaconda prompt and run::

	python sphereob.py



Dependencies
====

* matplotlib
* numpy
* quadpy
* pyqt5
* pandas


Documentation
====

Documentation, including explanations of the model parameters and data importers is included in SPHERE-OB.pdf
