# Qualisys PAF – Excel example

## Getting started
To download this example project to your computer, you can either:

* [Click here](https://github.com/qualisys/paf-excel-example/archive/refs/heads/main.zip) to download it as a zip file.
<br>_— or —_
* Clone this repository to your computer.

##  Preparing Qualisys data for Excel processing

1. In QTM, in Project Options > Processing > TSV Export: 
    - In Data type, activate 3D
    - In Genral Settings, activate "Include TSV Header", "Export time data for every frame", "Write column header" 
2. Set Project Options > Miscellaneous > Folder Options for "VB Script" to C:\Windows\System32\wscript.exe (adapt if wscript is located elsewhere on your computer).
3. In the PAF pane, click on Start Processing. An excel document automatically opens including a sheet with a graph and multiple sheets with marker data  
Note: If you do not see any curve in the graph, it can be related to the default separator set in Excel. In this case '.' should be used as the separator for numbers. You can set it in Excel->Option->Advanced->Use system separators

## Resources for using the Qualisys Project Automation Framework (PAF)

The purpose of the ***Project Automation Framework*** (PAF) is to streamline the motion capture process from data collection to the final report. This repository contains an example project that illustrate how PAF can be used to implement custom automated data collection in [Qualisys Track Manager (QTM)](http://www.qualisys.com/software/qualisys-track-manager/), and how QTM can be connected to a processing engine. 

### PAF Documentation

The full documentation for PAF development is available here: [PAF Documentation](https://github.com/qualisys/paf-documentation).


### PAF Examples

Our official examples for various processing engines:

- [AnyBody](https://github.com/qualisys/paf-anybody-example)
- [Excel](https://github.com/qualisys/paf-excel-example)
- [Matlab](https://github.com/qualisys/paf-matlab-example)
- [OpenSim](https://github.com/qualisys/paf-opensim-example)
- [Python](https://github.com/qualisys/paf-python-example)
- [Theia Markerless](https://github.com/qualisys/paf-theia-markerless-example)
- [Theia Markerless Comparison](https://github.com/qualisys/paf-theia-markerless-comparison-example)
- [Theia Markerless True Hybrid](https://github.com/qualisys/paf-theia-markerless-true-hybrid-example)
- [Visual3D](https://github.com/qualisys/paf-visual3d-example)

_As of QTM version 2.17, the official Qualisys PAF examples can be used without any additional license. Note that some more advanced analysis types require a license for the "PAF Framework Developer kit" (Article number 150300)._
