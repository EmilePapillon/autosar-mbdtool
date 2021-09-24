# AUTOSAR MBD Tool
Graphical Model Based tool to create autosar applications 

Mock up repository: there is no implementation yet. This is to capture the idea and requirements.

## Case
There are no good modeling tools for AUTOSAR Adaptive applications. 

## Description
This tool should provide intuitive ways of creating and visualising AUTOSAR Adaptive Applications

- Provide model generation (ARXML) based on a visual representation of the system
- Support exporting applications and other parts of the system individually, to separate ARXML files
- Allow importing components (application, interfaces, etc.) from different format (main candidate: ARXML files, but also maybe simulink, etc.) 

## Approach
The artop project seems like a reasonable place to start looking, as it promises to keep libraries up to date with the latest AUTOSAR specifications, including Adaptive. 
