macOS version is on the branch *master*
## VS Code Plugin installs
- C/C++ Miscrosoft  (ms-vscode.cpptools)
- CMake Tools (vector-of-bool.cmake-tools)
- Native Debug

## Run it
1. cmd + p -> Tasks: Run Task -> cmake
2. cmd + p -> Tasks: Run Task -> cmake build Debug
3. Can be run with

With these tasks and exe file is created in the build/Debug folder. This exe can be run with either Debugger in VS Code or simply double click on it (old school windows way).

#### Debugger
Run the debugger "(Windows) Launch" from the VS Code.

## Ressources
https://medium.com/audelabs/c-development-using-visual-studio-code-cmake-and-lldb-d0f13d38c563

http://www.suodenjoki.dk/us/archive/2016/vscode-cpp-mac.htm

http://preshing.com/20170511/how-to-build-a-cmake-based-project/

(not sure I used that)
http://osxdaily.com/2014/08/14/add-new-path-to-path-command-line/

#### NOTES
The following command can also be used for build, but it is not used here.

```devenv /build Debug hello_vsc.sln```
