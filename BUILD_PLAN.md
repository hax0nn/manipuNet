# BUILD PLAN
On this document it'll give you an overwiev of the technical steps of how this tool structured and planned. 

For planned overwiev of planned features please check the SPECS.md file. 

## Who is this document for? 
Currently it's only for hax0nn(me). Only I work on this project and it'll mostly contain my ideas and way of doing this project. 

Later I might include some sort of dev log to keep the log of my thought process.

## BUILD_PLAN
Important note: Design the whole system in a modular way. Entry point of the project(main file that will be executed) needs to be seperate. And for each action it would be prefeble to work on 

### Network scan

1. Find way to scan the network and gather the details from the devices(Or maybe router. Need to do research on it.). Currently IP and MAC address and the name of the devices. 

 - Find a way to get details from devices with echo-request blocked. 

2. Implement outputting of results that captured after the scan. (currently only in csv)

### Port scan

1. Find a way to scan desired devices over IP address.
 
 - Find a way to do 2 main scan. One is for TCP ports and other is for UDP.
 - Find a way to how to get details from TCP protocol ports.
 - Find a way to how to get details from UDP protocol ports.

2. Save the resutls to an file for furthure references.
3. Add option to scan same ports from a saved file. 
 - Find reliable way to do that. Maybe DB might be needed? or using files would be enough. Might be few option needed


