# CVA
Cryospheric Visualization and Analysis

Research Problem: Understanding of the cryosphere and the complex processes driving every aspect involved requires a great deal of background knowledge.

Abstract: Create an educational web page and/or tool to delve into each segment of the cryosphere, and present information such as:
- Where is the segment on the globe?
- What scientific instruments are used to measure them?
  - What satellites they are on and links to other instruments on that sat
- Shortcomings and future plans for each aspect


* Model after NIA2: pages show output viz and explain what's being looked at

* available Jupyter Notebooks used to parse data
* available Jupyter Notebooks used to create visualization



6/12/21: its a command line tool! like sleap

* Use PyQt5 for frontend design
* extra commands open specific python notebooks using jupyter notebook



Libraries:
PyQt5

jupyter notebook

satellite viz stuff

gis stuff

analysis stuff

np, pd, mpl, scipy, etc.



File Tree:
CVA/
  /notebooks/
    /remote_sensing/
      /active/
      /passive/
      /microwave/
    /components/
      /solid/
      /snow/
      /sea/
      /lakeriver/
      /land/
      /permafrost/
    /data_cleaning/
      /satellite/
      /grounded/
      /other/
  /data/
    /gcw_datasets/ #

  /gui/
    /assets/
    /PyQt5/
  /main
