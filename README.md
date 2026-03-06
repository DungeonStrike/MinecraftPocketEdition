# MIRROR OF https://gitea.sffempire.ru/Kolyah35/minecraft-pe-0.6.1 JUST TO MAKE EVERYONE EASIER TO FIND IT
I do not own this code and the @Kolyah35's improvements, please consider using https://gitea.sffempire.ru/Kolyah35/minecraft-pe-0.6.1 in case this gets DMCA

# MinecraftPE

This is leaked source code of Minecraft PE 0.6.1 with my own impovements :sunglasses:

First of all I made it build with CMake (w/o VS2012). Also I fixed some compile errors. And finally I ported it to GLFW to make it run on several platforms and remove binary dependencies.

# TODO
- [x] Add platform GLFW
- [x] Compile for Linux
- [ ] Compile for android aarch64
- [ ] Rewrite platform logic
- [ ] Fix sound
- [ ] Do a server connection gui

# Build
## CMake
```
mkdir build && cd build
cmake .. -B .
make -j4
```
