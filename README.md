# Galactum

Serveur Discord: https://discord.gg/Jsc9qdR

Serveur Telegram: https://t.me/galactum

Do not hesitate to contact us : support@galactum.site
 
### On ubuntu:

Dependencies: GCC 4.9 or later, CMake 2.8.6 or later, and Boost 1.55.
You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/

Alternatively, it may be possible to install them using a package manager.

```
sudo apt-get install build-essential libboost-all-dev git cmake
git clone https://github.com/Sab-Barsoom/Galactum.git
export CXXFLAGS="-std=gnu++11"
cd Galactum
mkdir build && cd build
cmake -DCMAKE_BUILD_TYPE=Release .. && make
```

The resulting executables can be found in build/release/src.


### On Windows:
Dependencies: MSVC 2015 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:
* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run this commands:

```
md build && cd build
cmake -G "Visual Studio 15 Win64" .. -DCMAKE_BUILD_TYPE=Release
MSBuild Galactum.sln /p:Configuration=Release /m
```
OR you can open Galactum Solution in Visual Studio and then do Build.

Good luck!
