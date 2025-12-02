# CMake  

### What is CMake?
CMake generates ```build files```.  

We only have to write one file ```CMakeLists.txt```, and then CMake turns that into **platform-specific build instructions.**    
CMake lets our project build on all platforms without rewriting build scripts.  

CMake can generate Makefiles (Linux/macOS), Ninja (Linux/ macOS/ Windows), Xcode (macOS), Visual Studio (Windows)  

### What is a build system?  
A build system knows how to call the compiler, track which files changed, rebuild only what is needed, set compiler flags, and handle dependencies.  

The build system does not compile code itself--it only runs the compiler with the right arguments.  

Common build systems: ```make``` program (reads Makefiles), ```ninja``` (build.ninja), ```msbuild```(Visual Studio)

### Difference between cmake and make  
```cmake```: Generates build rules (build files) --> produce a "build system"  
```make```: Uses those above build files to actually build the program. Builds code using rules. --> Produce a compiled program.  

### Feedback/ Contact  
chau.nguyen.dev@gmail.com
