# Launcher Qgis2

After install Qgis with Miniconda in home system, you can create the launcher to Qgis2 in order to run it in Ubuntu without open terminal.

1º) Create file Qgis2.desktop in your desktop

    cd /Desktop
    touch Qgis2.desktop

2º) Open it and add:

    [Desktop Entry]
    Name=Qgis2
    Comment=Qgis2
    Exec=bash -c 'export PATH="/home/{username}/miniconda2/bin:$PATH" && /home/{username}/miniconda2/bin/qgis'
    Icon=/home/{username}/miniconda2/share/qgis/images/icons/qgis-icon-60x60.png
    Terminal=false
    Type=Application
    Name[en_US]=Qgis2

3º) Go to Desktop and run Qgis

Or

1º) Create file Qgis2.desktop in /usr/share/applications

    cd /usr/share/applications
    touch Qgis2.desktop

2º) Open it and add:

    [Desktop Entry]
    Name=Qgis2
    Comment=Qgis2
    Exec=bash -c 'export PATH="/home/{username}/miniconda2/bin:$PATH" && /home/{username}/miniconda2/bin/qgis'
    Icon=/home/{username}/miniconda2/share/qgis/images/icons/qgis-icon-60x60.png
    Terminal=false
    Type=Application
    Name[en_US]=Qgis2

2º) Give permission to run it

    sudo chmod +x Qgis2.desktop

Now you can run using Application menu...







