# DBMS Assignment on Rtree implementation

## Required Files for Submission <a name="copy"></a>
  the following files (taken from repo [here](https://github.com/ankit-1517/dbms_rTree)):
- buffer_manager.cpp
- constants.h  
- file_manager.cpp
- buffer_manager.h
- errors.h
- file_manager.h
In order to use file system ( to store all node data on page not in program execution)
### make <a name="make"></a>

Runs the Makefile from the toplevel folder in the directory.  

### run.sh <a name="check"></a>

This script executes the rtree file with the following format -  
```./rtree query.txt maxCap dimensionality output.txt```  
Things to note here -  

- `query.txt` represents the **absolute path** of the query file as well as the relative path.
