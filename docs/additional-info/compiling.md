---
search:
  exclude: true
---

# Compiling SuperSlicer

---
## Windows

save this as a batch file in the root directory. ie path `C:\dev_superSlicer\git_repo_branch_name` put the repo files in the above directory. open x64 Native Tools Command Prompt for VS 20xx navigate to the above dir and run the batch file below. depending how how fast your computer is.. it could take up to a hour to build the project, then another 30 minutes once opened in visual studio and rebuilding the solution.

```sh
cd C:\*dir*\SuperSlicer\deps 
mkdir build 
cd build 
cmake .. -G "Visual Studio 17 2022" -DDESTDIR="C:\*dir*\SuperSlicer-deps" 
msbuild /m ALL_BUILD.vcxproj  
cd C:\*dir*\SuperSlicer 
mkdir build 
cd build 
cmake .. -G "Visual Studio 17 2022" -DCMAKE_PREFIX_PATH="C:\*dir*\SuperSlicer-deps\usr\local" 
cd C:\*dir*
```

you must have at least 8 Gigs of free RAM, so a computer with 8 Gigs is in total is not enough, it needs to be free.

Thanks to legend069 on Discord for the above steps

---
