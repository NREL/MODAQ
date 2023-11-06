# Conversion Report
You have converted your project from LabVIEW NXG Web Module to G Web Development Software. The following report details the changes made to the original project to complete the conversion.


## Removed Documents
Since G Web Development supports only WebVI, GVI, JSLI, Palette file, and Control Definition file documents and requires all code to be in components, the following documents have been removed from the project and/or components:
1. HMI Global to Cluster.gvi
2. JSON Waveform Converter.gvi


## Removed Package Dependencies
Incompatible Package/Installer file dependencies have been removed. To add dependencies in your converted project, use the Package/Installer document in G Web Development Software. Any dependencies you added manually to your original project will need to be re-added in the converted project.
