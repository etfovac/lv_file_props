# LabVIEW File Properties Editor 
[![DOI](https://zenodo.org/badge/536732123.svg)](https://zenodo.org/badge/latestdoi/536732123)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/etfovac/lv_file_props/blob/main/LICENSE) 

VI Scripting tool for reading and editing file properties (execution, reentrancy, filename, compiled code, etc).  
It filters files by selected property for selected folder and its subfolders.  
Supported files:  
- .vi 
- .ctl

Published also as an [NI Example](https://forums.ni.com/t5/Example-Code/LabVIEW-File-Properties-Editor/ta-p/4289814)

### Table of Contents (Wiki)
[Wiki Home](https://github.com/etfovac/lv_file_props/wiki)  
[Overview](https://github.com/etfovac/lv_file_props/wiki/Overview)  
[Notes](https://github.com/etfovac/lv_file_props/wiki/Notes)  
[Examples](https://github.com/etfovac/lv_file_props/wiki/Examples)  
[References](https://github.com/etfovac/lv_file_props/wiki/References)  

### Overview: Screenshots  
<img src="./graphics/Project.png" alt="Project"> 
<b>Main.vi</b> is an Example that targets the repo's folder and subfolders, including the test files.  
 
<img src="./graphics/Main FP.png" alt="Main FP">  
<img src="./graphics/Main BD.png" alt="Main BD">  
Use <b>Readout File Properties, Filtered.vi</b> to readout file properties of some other folder.  
<img src="./graphics/Readout Filtered None FP.png" alt="Readout Filtered None FP"> 
<img src="./graphics/Readout Filtered Modified FP.png" alt="Readout Filtered Modified FP">  
<img src="./graphics/Readout Filtered Not Sep Compiled Code FP.png" alt="Readout Filtered Not Sep Compiled Code FP">
<img src="./graphics/Readout Filtered Not Sep Compiled Code BD.png" alt="Readout Filtered Not Sep Compiled Code BD"> 
<img src="./graphics/Readout Filtered Prealloc Clones FP.png" alt="Readout Filtered Prealloc Clones FP">  
<img src="./graphics/Readout Filtered Prealloc Clones BD.png" alt="Readout Filtered Prealloc Clones BD">  

### Notes: Reentrancy  
To write (set) file's Reentrancy it needs to be loaded, recompiled and saved.    
<img src="./graphics/Write Reentrancy To VIs BD.png" alt="Write Reentrancy To VIs BD">  
<img src="./graphics/Write Reentrancy Type BD.png" alt="Write Reentrancy Type BD">  

[lv_file_props](https://github.com/etfovac/lv_file_props) is maintained by [etfovac](https://github.com/etfovac).
