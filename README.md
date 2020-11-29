# TLRC
Project Tracking App
This python package was created for individual independant contractor to have the 
ability to document and track projects that you have worked on. Once you have gathered enough 
information this data is presented in visual graphs that help you visualize performance and 
see where you are getting most of your work from. This does a couple of things for you.
***Has been tested on Ubuntu 20.04***

1. Track and Log Projects
2. Geo Locate Project Locations
3. Visual Graphs of Projects
4. Calculate Mileage Compensation 

Many of the setting can be customized to fit your profession
just edit the tlrc.py

1. Install the Prerequisites - instructions here

2. Clone TLRC from the GitHub repo:

        git clone https://github.com/bobbyd01001/BWITTLRC.git
        
        cd BWITTLRC
        
        unzip file

3. [Optional] Create a virtual environment for testing. Skip this step if you want to install it globaly on your system.

        python3 -m venv tlrcenv

        Activate the virtual environment:

        source tlrcenv/bin/activate

4. Run Setup

        To install with setuptools:

        cd tlrc_app_package

        python3 setup.py install --user
        
        At this point LXDUI should be installed and ready to start.



5. Start Application
        
        To start the app run: sudo python3 tlrc.py

        The app will open a gui window showing other options to choose



Created by JC Beasley
for questions contact beaswork@gmail.com
