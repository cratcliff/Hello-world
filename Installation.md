Installation
------------
PAT is only available for the Windows platform and is not currently available in QGIS 3.

First download and install QGIS Long Term Release 2.18.26 [32bit](http://download.osgeo.org/qgis/win64/QGIS-OSGeo4W-2.18.26-1-Setup-x86.exe) or 
[64bit](http://download.osgeo.org/qgis/win64/QGIS-OSGeo4W-2.18.26-1-Setup-x86_64.exe).

If you would like to use PAT's VESPER Kriging tool, then you will also need to download and install
[VESPER](https://sydney.edu.au/agriculture/pal/software/vesper.shtml).

If you would like to use PAT's Whole-of-block analysis tool then you will also need to download and install [R](http://r-project.org/)


#### Install the Precision Agriculture Tools (PAT) Plugin.
Once you have downloaded and installed QGIS install PAT as follows:
1.  In QGIS open the plugin manager. (***Plugins Menu → Manage and Install
    Plugins***)
2.  Select the ***All*** or ***Not installed*** Section.
3.  Search for and select **Precision Agriculture Tools (PAT).**
    Click ***Install plugin***.

During installation a dependency check will be undertaken to ensure certain
python packages are installed. If this check fails a message box, and an ***Error
loading plugin*** dialog will appear warning you that the plugin is broken. This
is expected behaviour. Click ***No*** to dismiss this box and ***quit*** QGIS.

You will be provided a shortcut ***Install PrecisionAg Extras*** on your desktop.
**Run the shortcut** to install the missing components. On opening QGIS the
dependency check will be run again to ensure the installation occurred
correctly. If the PAT menu and toolbar are not present then reinstall
and/or check/activate it using the plugin manager. You should then see a PAT menu
and toolbar.
