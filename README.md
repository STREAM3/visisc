# visisc
A visualisation library for event data analysed using the pyISC anomaly detection framework.

##Prerequisite

Install pyisc (including all prerequisites) : https://github.com/STREAM3/pyisc/

Notice, pyisc must be placed in the same folder as visisc so that visisc can find the source code. The pyisc folder must be named "pyisc".

Install Mayavi and wxPython (version 2.8.1 is preferred, otherwise if it does not exists as for Mac OS X choose 3.0)

Windows:
`>> conda install --channel https://conda.anaconda.org/krisvanneste wxpython==2.8.12`

Other:
`>> conda install wxpython`

All:

`>> conda install mayavi`

Notice: The latest version (4.0.5) of Anaconda is more restrictive to conflicting library version so that when installing Mayavi (version 4.4), numpy is most likly downgraded to 1.9.3 and cannot be upgraded again. In that case, if you not already downgraded numpy before installing pyISC, you have to reinstall pyISC after installing Mayavi. 

##Installation
`>> git clone https://github.com/STREAM3/visisc`

`>> cd visisc`

`>> python setup.py install`

##Run tutorial

`>> cd docs`

`>> jupyter notebook visISC_tutorial.ipynb`

If not opened automatically, click  on `visISC_tutorial.ipynb` in the web page that was opened in the web browser.
