# Awesome raylib

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome stuff for [raylib](https://raylib.com), Simple and easy-to-use library to enjoy videogames programming.

## List

- [Gists](#gists)
- [Homebrew Ports](#homebrew-ports)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Softwares](#softwares)
- [Bindings](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)
- [Deprecated/Removed/Unknown bindings](#deprecatedremovedunknown-bindings)
- [Libraries bindings/ports](#libraries-bindingsports)
- [Platforms supported by raylib](https://github.com/raysan5/raylib#building-raylib-on-multiple-platforms)
- [Tutorials](#tutorials)
- [Community Examples](#community-examples)
- [Templates](#templates)
- [Articles](#articles)
- [Videos](#videos)
- [What raylib uses?](https://github.com/raysan5/raylib/wiki/raylib-dependencies)
- [Promo Images](#promo-images)
- [Logos](#logos)
- [Stickers](#stickers)
- [Resources and Links](#resources-and-links)

### Gists

| Name                                                                                   | Author                                    | Description                                                                                                |
|----------------------------------------------------------------------------------------|-------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [sort.c][ohmree-dac78b36b736a71dc9a423d10b9509cc]                                      | [ohmree][ohmree-github]                   | C Sorting example that uses raylib.                                                                        |
| [bleed.c][satinxs-e55461da74ba378a09d813cb6767ffae]                                    | [satinxs][satinxs-github]                 | Bleed bug when drawing rectangles with raylib.                                                             |
| [agui.h][masterex1000-92c861eeef03e761d0addc6edc0b741f]                                | [masterex1000][masterex1000-github]       | Small UI helper library intended to be used with raylib.                                                   |
| [rpmd.c][SamyBencherif-00412fa24b411c07ad57176e64793fb5]                               | [SamyBencherif][SamyBencherif-github]     | Pixelated 2D lighting with shadows in raylib, software accelerated.                                        |
| [client_GUI.c][Goodguyr-284a262dc95ab0a35b498115c1cb3d41]                              | [Goodguyr][Goodguyr-github]               | raylib example of networking, Drawing circles for each player.                                             |
| [pan.c][JeffM2501-3c7da5c2b7e078e254d673f91489c78f]                                    | [JeffM2501][JeffM2501-github]             | raylib example of mouse drag panning for 2D camera.                                                        |
| [noisepl.c][Demizdor-e916ba765336c389af4ecd2c557a6be6]                                 | [Demizdor][Demizdor-github]               | Noise Planets example made with raylib.                                                                    |
| [RayCollisions.c][Pikachuxxxx-0dda4b70bf71b794b08923df34961844]                        | [Pikachuxxxx][Pikachuxxxx-github]         | Function to Detect Collisions Between a Ray and a Rectangle and Dynamic Rectangle and a Rectangle.         |
| [raylib_dpi_hack.c][mattj1-606a94527badb6ffa7d22245c9b745b1]                           | [mattj1][mattj1-github]                   | Function to get window DPI.                                                                                |
| [raynames.h][dotxnc-403caefa3bd1eae3b8e265e79d6508ad]                                  | [dotxnc][dotxnc-github]                   | Header that provides lowercase name aliases for types and functions of raylib, raymath, easings, And rnet. |
| [raylibvectors.c][AregevDev-737d14ce64be059ed2b6d0d973361985]                          | [AregevDev][AregevDev-github]             | raylib example for 2D Vectors.                                                                             |
| [maze.c][EdwardDowling-01a872cca79e1404bbc2]                                           | [EdwardDowling][EdwardDowling-github]     | Maze generation and raycasting example.                                                                    |
| [core_2d_camera_c-mera.lisp][pluckyporcupine-bbaa93b00e020c53faf27e5bde087374]         | [pluckyporcupine][pluckyporcupine-github] | raylib core_2d_camera example ported to [C-Mera][kiselgra-c-mera]!                                         |
| [core_split_screen.c][JeffM2501-85e3c3fa4c5296227ab91dd7d2dec471]                      | [JeffM2501][JeffM2501-github]             | Simple splitscreen implemntation for raylib.                                                               |
| [models_mesh_generation.c][JeffM2501-18964218591e5aa302f17f0ae5a45b77]                 | [JeffM2501][JeffM2501-github]             | Example shows that Mesh generation of quad with UV repeats in raylib.                                      |
| [imgui_docking_exmaple.cpp][JeffM2501-4c3a7e8a85302f743f8bd9dc1aae00ae]                | [JeffM2501][JeffM2501-github]             | Example of how to do editor style docking in [ImGui][ocornut-imgui] for raylib.                            |
| [varfps.c][JeffM2501-588d8b632d1bf49c7f010dde0a9dcbee]                                 | [JeffM2501][JeffM2501-github]             | raylib test showing how frame based motion can be problematic.                                             |
| [raylib worldspace panning with rotation][JeffM2501-703728379eb6e9d51d33201d1a1fe05d]  | [JeffM2501][JeffM2501-github]             | raylib example of worldspace panning with rotation.                                                        |
| [raylib worldspace panning][JeffM2501-edb5b8bbfd5a1744d4f97865ad4be989]                | [JeffM2501][JeffM2501-github]             | raylib example of worldspace panning without rotation.                                                     |
| [Model merge for raylib][JeffM2501-08d20cdd931456ad0e52905401cc34af]                   | [JeffM2501][JeffM2501-github]             | Example of model merge made with raylib.                                                                   |
| [raylib resize fullscreen example][JeffM2501-00cf5653f41337d8c9e8db40deb25656]         | [JeffM2501][JeffM2501-github]             | raylib resize fullscreen example.                                                                          |
| [orbitcamera.cpp][JeffM2501-000787070aef421a00c02ae4cf799ea1]                          | [JeffM2501][JeffM2501-github]             | Example of orbit camera made for raylib!                                                                   |
| [RLAssets.cpp][JeffM2501-bd1092ce0eaedd26fe3ca60e1743ce40]                             | [JeffM2501][JeffM2501-github]             | Basic platform independent asset folder management for raylib.                                             |
| [Basic Shot Animation raylib][JeffM2501-a6eb14d734f88a065a73adb729eed1f7]              | [JeffM2501][JeffM2501-github]             | Basic animation made with raylib.                                                                          |
| [Basic entity game][JeffM2501-a5987d2f4575e871f561197232ba0f60]                        | [JeffM2501][JeffM2501-github]             | Entity example made with raylib.                                                                           |
| [DrawTextureProZ][JeffM2501-1c4c9c8048cbb19d11c9807518196b69]                          | [JeffM2501][JeffM2501-github]             | Modified version of `DrawTexturePro` that adds Z Dimension/Depth!                                          |
| [raylib fullscreen toggle example][JeffM2501-6e4630a0e34c0c7dddf066f7192e342d]         | [JeffM2501][JeffM2501-github]             | fullscreen toggle example made with raylib.                                                                |

[ohmree-github]:                                    https://github.com/ohmree
[satinxs-github]:                                   https://github.com/satinxs
[masterex1000-github]:                              https://github.com/masterex1000
[SamyBencherif-github]:                             https://github.com/SamyBencherif
[Goodguyr-github]:                                  https://github.com/Goodguyr
[JeffM2501-github]:                                 https://github.com/JeffM2501
[Demizdor-github]:                                  https://github.com/Demizdor
[Pikachuxxxx-github]:                               https://github.com/Pikachuxxxx
[mattj1-github]:                                    https://github.com/mattj1
[dotxnc-github]:                                    https://github.com/dotxnc
[AregevDev-github]:                                 https://github.com/AregevDev
[EdwardDowling-github]:                             https://github.com/EdwardDowling
[pluckyporcupine-github]:                           https://github.com/pluckyporcupine

[ohmree-dac78b36b736a71dc9a423d10b9509cc]:          https://gist.github.com/ohmree/dac78b36b736a71dc9a423d10b9509cc
[satinxs-e55461da74ba378a09d813cb6767ffae]:         https://gist.github.com/satinxs/e55461da74ba378a09d813cb6767ffae
[masterex1000-92c861eeef03e761d0addc6edc0b741f]:    https://gist.github.com/masterex1000/92c861eeef03e761d0addc6edc0b741f
[SamyBencherif-00412fa24b411c07ad57176e64793fb5]:   https://gist.github.com/SamyBencherif/00412fa24b411c07ad57176e64793fb5
[Goodguyr-284a262dc95ab0a35b498115c1cb3d41]:        https://gist.github.com/Goodguyr/284a262dc95ab0a35b498115c1cb3d41
[JeffM2501-3c7da5c2b7e078e254d673f91489c78f]:       https://gist.github.com/JeffM2501/3c7da5c2b7e078e254d673f91489c78f
[Demizdor-e916ba765336c389af4ecd2c557a6be6]:        https://gist.github.com/Demizdor/e916ba765336c389af4ecd2c557a6be6
[Pikachuxxxx-0dda4b70bf71b794b08923df34961844]:     https://gist.github.com/Pikachuxxxx/0dda4b70bf71b794b08923df34961844
[mattj1-606a94527badb6ffa7d22245c9b745b1]:          https://gist.github.com/mattj1/606a94527badb6ffa7d22245c9b745b1
[dotxnc-403caefa3bd1eae3b8e265e79d6508ad]:          https://gist.github.com/dotxnc/403caefa3bd1eae3b8e265e79d6508ad
[AregevDev-737d14ce64be059ed2b6d0d973361985]:       https://gist.github.com/AregevDev/737d14ce64be059ed2b6d0d973361985
[EdwardDowling-01a872cca79e1404bbc2]:               https://gist.github.com/EdwardDowling/01a872cca79e1404bbc2
[pluckyporcupine-bbaa93b00e020c53faf27e5bde087374]: https://gist.github.com/pluckyporcupine/bbaa93b00e020c53faf27e5bde087374
[JeffM2501-85e3c3fa4c5296227ab91dd7d2dec471]:       https://gist.github.com/JeffM2501/85e3c3fa4c5296227ab91dd7d2dec471
[JeffM2501-18964218591e5aa302f17f0ae5a45b77]:       https://gist.github.com/JeffM2501/18964218591e5aa302f17f0ae5a45b77
[JeffM2501-4c3a7e8a85302f743f8bd9dc1aae00ae]:       https://gist.github.com/JeffM2501/4c3a7e8a85302f743f8bd9dc1aae00ae
[JeffM2501-588d8b632d1bf49c7f010dde0a9dcbee]:       https://gist.github.com/JeffM2501/588d8b632d1bf49c7f010dde0a9dcbee
[JeffM2501-703728379eb6e9d51d33201d1a1fe05d]:       https://gist.github.com/JeffM2501/703728379eb6e9d51d33201d1a1fe05d
[JeffM2501-edb5b8bbfd5a1744d4f97865ad4be989]:       https://gist.github.com/JeffM2501/edb5b8bbfd5a1744d4f97865ad4be989
[JeffM2501-08d20cdd931456ad0e52905401cc34af]:       https://gist.github.com/JeffM2501/08d20cdd931456ad0e52905401cc34af
[JeffM2501-00cf5653f41337d8c9e8db40deb25656]:       https://gist.github.com/JeffM2501/00cf5653f41337d8c9e8db40deb25656
[JeffM2501-000787070aef421a00c02ae4cf799ea1]:       https://gist.github.com/JeffM2501/000787070aef421a00c02ae4cf799ea1
[JeffM2501-bd1092ce0eaedd26fe3ca60e1743ce40]:       https://gist.github.com/JeffM2501/bd1092ce0eaedd26fe3ca60e1743ce40
[JeffM2501-a6eb14d734f88a065a73adb729eed1f7]:       https://gist.github.com/JeffM2501/a6eb14d734f88a065a73adb729eed1f7
[JeffM2501-a5987d2f4575e871f561197232ba0f60]:       https://gist.github.com/JeffM2501/a5987d2f4575e871f561197232ba0f60
[JeffM2501-1c4c9c8048cbb19d11c9807518196b69]:       https://gist.github.com/JeffM2501/1c4c9c8048cbb19d11c9807518196b69
[JeffM2501-6e4630a0e34c0c7dddf066f7192e342d]:       https://gist.github.com/JeffM2501/6e4630a0e34c0c7dddf066f7192e342d

[kiselgra-c-mera]:                                  https://github.com/kiselgra/c-mera
[ocornut-imgui]:                                    https://github.com/ocornut/imgui

### Homebrew Ports

| Name                                   | Author                        | Platform              |
|----------------------------------------|-------------------------------|-----------------------|
| [orbisdev-orbisGl2][orbisdev-orbisGL2] | [orbisdev][orbisdev-github]   | Sony PlayStation 4    |
| [raylib4Vita][psp2dev-raylib4Vita]     | [psp2dev][psp2dev-github]     | Sony PlayStation Vita |
| [3ds-raylib][Gota7-3ds-raylib]         | [Gota7][Gota7-github]         | Nintendo 3DS          |
| [raylib-nx][LucaSkyer-raylib-nx]       | [LucaSkyer][LucaSkyer-github] | Nintendo Switch       |

[orbisdev-github]:      https://github.com/orbisdev
[psp2dev-github]:       https://github.com/psp2dev
[Gota7-github]:         https://github.com/Gota7
[LucaSkyer-github]:     https://github.com/lucaskyer

[orbisdev-orbisGL2]:    https://github.com/orbisdev/orbisdev-orbisGl2
[psp2dev-raylib4Vita]:  https://github.com/psp2dev/raylib4Vita
[Gota7-3ds-raylib]:     https://github.com/Gota7/3ds-raylib
[LucaSkyer-raylib-nx]:  https://github.com/lucaskyer/raylib-nx

### Libraries and Frameworks

| Name                                                     | Author                                      | Description                                                                                                                     |
|----------------------------------------------------------|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| [rayfork][SasLuca-rayfork]                               | [SasLuca][SasLuca-github]                   | Single header and source, cross-platform, allocator-aware, C99 game libraries.                                                  |
| [raygui][raysan5-raygui]                                 | [raysan5][raysan5-github]                   | Simple and easy-to-use immediate-mode GUI library.                                                                              |
| [Physac][victorfisac-Physac]                             | [victorfisac][victorfisac-github]           | 2D physics header-only library for videogames developed in C using raylib library.                                              |
| [rpng][raysan5-rpng]                                     | [raysan5][raysan5-github]                   | Simple and easy-to-use library to manage png chunks.                                                                            | 
| [rres][raysan5-rres]                                     | [raysan5][raysan5-github]                   | Simple and easy-to-use file-format to package resources.                                                                        |
| [raudio][raysan5-raudio]                                 | [raysan5][raysan5-github]                   | Simple and easy-to-use audio library based on [miniaudio][miniaudio-site].                                                      |
| [ECSlib][firststef-ECSlib]                               | [firststef][firststef-github]               | Library with ECS classes in C++ using raylib.                                                                                   |
| [tbag][osom8979-tbag]                                    | [osom8979][osom8979-github]                 | Third party extension utility project.                                                                                          |
| [imgui-impl-raylib][oswjk-imgui-impl-raylib]             | [oswjk][oswjk-github]                       | raylib backend for Dear ImGui.                                                                                                  |
| [rlImGui][raylib-extras-rlImGui]                         | [raylib-extras][raylib-extras-github]       | [Dear ImGui][ocornut-imgui] immediate graphical user interface for raylib.                                                      |
| [Libre][haydenhigg-Libre]                                | [haydenhigg][haydenhigg-github]             | [Crystal][crystal-lang] graphics library that is built on raylib.                                                               |
| [GameSystemsInC][nezvers-GameSystemsInCs]                | [nezvers][nezvers-github]                   | TileMap & Sprite systems for raylib.                                                                                            |
| [raylib-aseprite][RobLoach-raylib-aseprite]              | [RobLoach][RobLoach-github]                 | Load [Aseprite][aseprite-site] files for animated sprites in raylib.                                                            |
| [raylib-nuklear][RobLoach-raylib-nuklear]                | [RobLoach][RobLoach-github]                 | [Nuklear][Immediate-Mode-UI-Nuklear] immediate mode GUI for raylib.                                                             |
| [zgui][zworld-apps-zgui]                                 | [zworld-apps][zworld-apps-zgui]             | GUI system based on Constraints for raylib, Written in [Go][go-lang].                                                           |
| [visual-go][Slixe-visual-go]                             | [Slixe][Slixe-github]                       | Framework to create simple application using raylib & Flex.                                                                     |
| [rlyeh][basp1-rlyeh]                                     | [basp1][basp1-github]                       | Simple and easy-to-use GUI API library for [raylib-go][gen2brain-raylib-go], Written in Go.                                     |
| [raycons][smthnspcl-raycons]                             | [smthnspcl][smthnspcl-github]               | Icons drawn by raylib, Written in C++.                                                                                          |
| [raygauge][smthnspcl-raygauge]                           | [smthnspcl][smthnspcl-github]               | Simple gauges to display values with raylib, Written in C++.                                                                    |
| [libpartikel][dbriemann-libpartikel]                     | [dbriemann][dbriemann-github]               | Simple particle system library made with and for raylib. Works as header only library.                                          |
| [spine-raylib-runtimes][WEREMSOFT-spine-raylib-runtimes] | [WEREMSOFT][WEREMSOFT-github]               | raylib implementation of the C spine runtimes.                                                                                  |
| [stl-loader-for-raylib][WEREMSOFT-stl-loader-for-raylib] | [WEREMSOFT][WEREMSOFT-github]               | STL loader for raylib, Allows to load 3dPrinter file types into raylib.                                                         |
| [Raylib-GBuffers][TheLumaio-Raylib-GBuffers]             | [TheLumaio][TheLumaio-github]               | GBuffer implementation for raylib.                                                                                              |
| [tofu][tofuengine-tofu]                                  | [tofuengine][tofuengine-github]             | Lightweight 2D framework with a lo-fi vibe, for fast game prototyping. Uses OpenGL through [GLFW3][glfw-site], Scripted in Lua. |
| [RaylibEX][Ferrohound-RaylibEX]                          | [Ferrohound][Ferrohound-github]             | raylib Extra incorporates more basic functionality to raylib while keeping the hands-on aspect!                                 |
| [MathX][JusticeShultz-MathX]                             | [JusticeShultz][JusticeShultz-github]       | Detailed custom math library programmed in C++ that includes demos that uses raylib.                                            |
| [RaylibCs-UI][LilySweetCat-RaylibCs-UI]                  | [LilySweetCat][LilySweetCat-github]         | Just a simple UI using raylib (Can be used as library), Written in C#.                                                          |
| [raylib-tmx][RobLoach-raylib-tmx]                        | [RobLoach][RobLoach-github]                 | Load and draw [Tiled][mapeditor-site] `.tmx` tile maps through the [TMX C Loader][baylej-tmx].                                  |
| [ruicf][nbdy-ruicf]                                      | [nbdy][nbdy-github]                         | C++ raylib UI controls framework.                                                                                               |
| [RLGameGui][JeffM2501-RLGameGui]                         | [JeffM2501][JeffM2501-github]               | Resolution independent GUI for raylib, Written in C++!                                                                          |
| [raylib-extensions][jackcarey-raylib-extensions]         | [jackcarey][jackcarey-github]               | Modifications/Additions to raylib and raygui.                                                                                   |
| [RayLibUtils][coolcoy12-RayLibUtils]                     | [coolcoy12][coolcoy12-github]               | Useful UI and effects for raylib written in C++!                                                                                |
| [raylib-barebones][moonsteal-raylib-barebones]           | [moonsteal][moonsteal-github]               | Stripped down version of raylib with Meson.                                                                                     |
| [RaylibSIMD][Doy-lee-RaylibSIMD]                         | [Doy-lee][Doy-lee-github]                   | SIMD Implementation of raylib's API.                                                                                            |
| [RTAudioGameLib][8bitPandaPlugins-RTAudioGameLib]        | [8bitPandaPlugins][8bitPandaPlugins-github] | C++ Game API built on raylib and [RTaudio][thestk-rtaudio] for latency critical implimentations.                                |
| [RayLib-Utilities][zzador-Raylib-Utilities]              | [zzador][zzador-github]                     | Some utility & helper functions for raylib and raygui.                                                                          |
| [libraygun][jozanza-libraygun]                           | [jozanza][jozanza-github]                   | Utils for raylib.                                                                                                               |
| [raylibExtras][JeffM2501-raylibExtras]                   | [JeffM2501][JeffM2501-github]               | C++ Utilities and common code for use with raylib.                                                                              |
| [raylibImGui][Ushio-raylibImGui]                         | [Ushio][Ushio-github]                       | C++ Dear ImGui integration for raylib.                                                                                          |
| [displayfx_raylib][nicholasimon-displayfx_raylib]        | [nicholasimon][nicholasimon-github]         | Few effects to use on top of your game screen, scanlines, noise lines and pixel noise, written in Go.                           |
| [rlgutils][JacobLondon-rlgutils]                         | [JacobLondon][JacobLondon-github]           | Go utilities for raylib.                                                                                                        |
| [PaperSDL][thyliverman-PaperSDL]                         | [thyliverman][thyliverman-github]           | Small software library, designed to make using [Raylib-cs][ChrisDill-Raylib-cs] simpler and more concise, Written in C#.        |
| [gtk-raylib][hbiblia-gtk-raylib]                         | [hbiblia][hbiblia-github]                   | [GTK][gtk-site] integration with raylib.                                                                                        |
| [gastar][impzero-gastar]                                 | [impzero][impzero-github]                   | Algorithm implemented in Go visualized using raylib.                                                                            |
| [raylib-physfs][RobLoach-raylib-physfs]                  | [RobLoach][RobLoach-github]                 | Provides integration with the virtual file system [PhysicsFS][physfs-site]                                                      |
| [raylib-assetsys][RobLoach-raylib-assetsys]              | [RobLoach][RobLoach-github]                 | Load raylib assets from .zip files with [assetsys.h][mattiasgustavsson-assetsys-h]                                              |
| [Paper][thyliverman-Paper]                               | [thyliverman][thyliverman-github]           | C++ rewrite of [PaperSDL][thyliverman-PaperSDL], dedicated to making raylib just a little easier to work with.                  |
| [Animator-For-Raylib][AliElSaleh-Animator-For-Raylib]    | [AliElSaleh][AliElSaleh-github]             | C/C++ Animator lib.                                                                                                             |
| [TestFrame][JeffM2501-TestFrame]                         | [JeffM2501][JeffM2501-github]               | Test framework that uses raylib and ImGui together to help test and develop concept and uses C++ classes for windows and views. |
| [ferox][c-krit-ferox]                                    | [c-krit][c-krit-github]                     | 2D collision detection and physics library written in C.                                                                        |
| [RaylibOpOverloads][ProfJski-RaylibOpOverloads]          | [ProfJski][ProfJski-github]                 | C++ Operator Overloads for raylib.                                                                                              |
| [rlzero][electronstudio-rlzero]                          | [electronstudio][electronstudio-github]     | Simplified API for raylib to enable beginners to create 3D games, Inspired by [Pygame Zero][lordmauve-pgzero].                  |
| [haxeui-raylib][haxeui-haxeui-raylib]                    | [haxeui][haxeui-github]                     | raylib backend for [HaxeUI][haxeui-site].                                                                                       |
| [rlobj][Not-Nik-rlobj]                                   | [Not-Nik][Not-Nik-github]                   | drop-in replacement for raylib's obj loader.                                                                                    |
| [Glui][Samerion-Glui]                                    | [Samerion][Samerion-github]                 | Declarative D user interface library for raylib.                                                                                |
| [raylib-api][RobLoach-raylib-api]                        | [RobLoach][RobLoach-github]                 | Exports of the raylib APIs in different formats (XML, JSON, Lua, etc)                                                           |
| [raylib-assert][RobLoach-raylib-assert]                  | [RobLoach][RobLoach-github]                 | Runtime assertion library for raylib                                                                                            |
| [dk_console][dkvilo-dk_console]                          | [dkvilo][dkvilo-github]                     | Drop in dev console for your raylib game/engine                                                                                 |
| [raylib-video][RicoP-raylib-video]                       | [RicoP][RicoP-github]                       | A multi-threaded realtime single header library to stream MPEG1 videos to textures                                              |

[raysan5-github]:                   https://github.com/raysan5
[SasLuca-github]:                   https://github.com/SasLuca
[victorfisac-github]:               https://github.com/victorfisac
[firststef-github]:                 https://github.com/firststef
[osom8979-github]:                  https://github.com/osom8979
[oswjk-github]:                     https://github.com/oswjk
[haydenhigg-github]:                https://github.com/haydenhigg
[nezvers-github]:                   https://github.com/nezvers
[RobLoach-github]:                  https://github.com/RobLoach
[zworld-apps-github]:               https://github.com/zworld-apps
[Slixe-github]:                     https://github.com/Slixe
[basp1-github]:                     https://github.com/basp1
[smthnspcl-github]:                 https://github.com/smthnspcl
[dbriemann-github]:                 https://github.com/dbriemann
[WEREMSOFT-github]:                 https://github.com/WEREMSOFT
[TheLumaio-github]:                 https://github.com/TheLumaio
[tofuengine-github]:                https://github.com/tofuengine
[Ferrohound-github]:                https://github.com/Ferrohound
[JusticeShultz-github]:             https://github.com/JusticeShultz
[LilySweetCat-github]:              https://github.com/LilySweetCat
[jackcarey-github]:                 https://github.com/jackcarey
[nbdy-github]:                      https://github.com/nbdy
[coolcoy12-github]:                 https://github.com/coolcoy12
[moonsteal-github]:                 https://github.com/moonsteal
[Doy-lee-github]:                   https://github.com/Doy-lee
[8bitPandaPlugins-github]:          https://github.com/8bitPandaPlugins
[zzador-github]:                    https://github.com/zzador
[jozanza-github]:                   https://github.com/jozanza
[Ushio-github]:                     https://github.com/Ushio
[nicholasimon-github]:              https://github.com/nicholasimon
[JacobLondon-github]:               https://github.com/JacobLondon
[thyliverman-github]:               https://github.com/thyliverman
[hbiblia-github]:                   https://github.com/hbiblia
[impzero-github]:                   https://github.com/impzero
[AliElSaleh-github]:                https://github.com/AliElSaleh
[c-krit-github]:                    https://github.com/c-krit
[ProfJski-github]:                  https://github.com/ProfJski
[electronstudio-github]:            https://github.com/electronstudio
[haxeui-github]:                    https://github.com/haxeui
[Not-Nik-github]:                   https://github.com/Not-Nik
[raylib-extras-github]:             https://github.com/raylib-extras
[Samerion-git]:                     https://git.samerion.com/Samerion
[dkvilo-github]:                    https://github.com/dkvilo
[RicoP-github]:                     https://github.com/RicoP

[SasLuca-rayfork]:                  https://github.com/SasLuca/rayfork
[raysan5-raygui]:                   https://github.com/raysan5/raygui
[victorfisac-Physac]:               https://github.com/victorfisac/Physac
[raysan5-rpng]:                     https://github.com/raysan5/rpng
[raysan5-rres]:                     https://github.com/raysan5/rres
[raysan-raudio]:                    https://github.com/raysan5/raudio
[firststef-ECSlib]:                 https://github.com/firststef/ECSlib
[osom8979-tbag]:                    https://github.com/osom8979/tbag
[raylib-extras-rlImGui]:            https://github.com/raylib-extras/rlImGui
[oswjk-imgui-impl-raylib]:          https://github.com/oswjk/imgui-impl-raylib
[haydenhigg-Libre]:                 https://github.com/haydenhigg/Libre
[nezvers-GameSystemsInC]:           https://github.com/nezvers/GameSystemsInC
[RobLoach-raylib-aseprite]:         https://github.com/RobLoach/raylib-aseprite
[RobLoach-raylib-nuklear]:          https://github.com/RobLoach/raylib-nuklear
[Immediate-Mode-UI-Nuklear]:        https://github.com/Immediate-Mode-UI/Nuklear
[zworld-apps-zgui]:                 https://github.com/zworld-apps/zgui
[Slixe-visual-go]:                  https://github.com/Slixe/visual-go
[basp1-rlyeh]:                      https://github.com/basp1/rlyeh
[gen2brain-raylib-go]:              https://github.com/gen2brain/raylib-go
[smthnspcl-raycons]:                https://github.com/smthnspcl/raycons
[smthnspcl-raygauge]:               https://github.com/smthnspcl/raygauge
[dbriemann-libpartikel]:            https://github.com/dbriemann/libpartikel
[WEREMSOFT-spine-raylib-runtimes]:  https://github.com/WEREMSOFT/spine-raylib-runtimes
[WEREMSOFT-stl-loader-for-raylib]:  https://github.com/WEREMSOFT/stl-loader-for-raylib
[TheLumaio-Raylib-GBuffers]:        https://github.com/TheLumaio/Raylib-GBuffers
[tofuengine-tofu]:                  https://github.com/tofuengine/tofu
[Ferrohound-RaylibEX]:              https://github.com/Ferrohound/RaylibEX
[JusticeShultz-MathX]:              https://github.com/JusticeShultz/MathX
[LilySweetCat-RaylibCs-UI]:         https://github.com/LilySweetCat/RaylibCs-UI
[RobLoach-raylib-tmx]:              https://github.com/RobLoach/raylib-tmx
[baylej-tmx]:                       https://github.com/baylej/tmx
[nbdy-ruicf]:                       https://github.com/nbdy/ruicf
[JeffM2501-RLGameGui]:              https://github.com/JeffM2501/RLGameGui
[jackcarey-raylib-extensions]:      https://github.com/jackcarey/raylib-extensions
[coolcoy12-RayLibUtils]:            https://github.com/coolcoy12/RayLibUtils
[moonsteal-raylib-barebones]:       https://github.com/moonsteal/raylib-barebones
[Doy-lee-RaylibSIMD]:               https://github.com/Doy-lee/RaylibSIMD
[8bitPandaPlugins-RTAudioGameLib]:  https://github.com/8bitPandaPlugins/RTAudioGameLib
[thestk-rtaudio]:                   https://github.com/thestk/rtaudio
[zzador-RayLib-Utilities]:          https://github.com/zzador/RayLib-Utilities
[jozanza-libraygun]:                https://github.com/jozanza/libraygun
[JeffM2501-raylibExtras]:           https://github.com/JeffM2501/raylibExtras
[Ushio-raylibImGui]:                https://github.com/Ushio/raylibImGui
[nicholasimon-displayfx_raylib]:    https://github.com/nicholasimon/displayfx_raylib
[JacobLondon-rlgutils]:             https://github.com/JacobLondon/rlgutils
[thyliverman-PaperSDL]:             https://github.com/thyliverman/PaperSDL
[ChrisDill-Raylib-cs]:              https://github.com/ChrisDill/Raylib-cs
[hbiblia-gtk-raylib]:               https://github.com/hbiblia/gtk-raylib
[impzero-gastar]:                   https://github.com/impzero/gastar
[RobLoach-raylib-physfs]:           https://github.com/RobLoach/raylib-physfs
[RobLoach-raylib-assetsys]:         https://github.com/RobLoach/raylib-assetsys
[thyliverman-Paper]:                https://github.com/thyliverman/Paper
[AliElSaleh-Animator-For-Raylib]:   https://github.com/AliElSaleh/Animator-For-Raylib
[JeffM2501-TestFrame]:              https://github.com/JeffM2501/TestFrame
[c-krit-ferox]:                     https://github.com/c-krit/ferox
[ProfJski-RaylibOpOverloads]:       https://github.com/ProfJski/RaylibOpOverloads
[electronstudio-rlzero]:            https://github.com/electronstudio/rlzero
[haxeui-haxeui-raylib]:             https://github.com/haxeui/haxeui-raylib
[Not-Nik-rlobj]:                    https://github.com/Not-Nik/rlobj
[Samerion-Glui]:                    https://git.samerion.com/Samerion/Glui
[RobLoach-raylib-api]:              https://github.com/RobLoach/raylib-api
[RobLoach-raylib-assert]:           https://github.com/RobLoach/raylib-assert
[dkvilo-dk_console]:                https://github.com/dkvilo/dk_console
[RicoP-raylib-video]:               https://github.com/RicoP/raylib-video

[mattiasgustavsson-assetsys-h]:     https://github.com/mattiasgustavsson/libs/blob/main/assetsys.h
[lordmauve-pgzero]:                 https://github.com/lordmauve/pgzero
<!--[pygame-zero-site]:             https://pygame-zero.readthedocs.io-->
  
[crystal-lang]:                     https://crystal-lang.org
[aseprite-site]:                    https://www.aseprite.org
[go-lang]:                          https://go.dev
[glfw-site]:                        https://www.glfw.org
[physfs-site]:                      https://www.icculus.org/physfs
[mapeditor-site]:                   https://www.mapeditor.org
[gtk-site]:                         https://www.gtk.org
[haxeui-site]:                      https://haxeui.org
[miniaudio-site]:                   https://miniaud.io

### Softwares

| Name                                                                       | Author                                                      | Description                                                                                                                                       |
|----------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| [gxarch][gtrxAC-gxarch]                                                    | [gtrxAC][gtrxAC-github]                                     | Simple fantasy computer architecture that uses raylib!                                                                                            |
| [gxSE][gtrxAC-gxSE]                                                        | [gtrxAC][gtrxAC-github]                                     | Command-based sprite/image editor.                                                                                                                |
| [3d-audio-producer][adct-the-experimenter-3d-audio-producer]               | [adct-the-experimenter][adct-the-experimenter-github]       | Fork of the [adct-the-experimenter/binaural-audio-editor][adct-the-experimenter-binaural-audio-editor] that uses replaced with raygui and raylib. |
| [chip8][Lockna-chip8]                                                      | [Lockna][Lockna-github]                                     | Very basic [CHIP-8][chip8-wikipedia] emulator that uses raylib for rendering.                                                                     |
| [SkyBoy][skylersaleh-SkyBoy]                                               | [skylersaleh][skylersaleh-github]                           | Game Boy and Game Boy Color Emulator powered by raylib!                                                                                           |
| [2D-CAD-Raylib][sparkskapil-2D-CAD-Raylib]                                 | [sparkskapil][sparkskapil-github]                           | 2D CAD viewer for raylib.                                                                                                                         |
| [raygui_calculator][sorykkk-raygui_calculator]                             | [sorykkk][sorykkk-github]                                   | Demonstrates simple and functional calculator gui written with raygui based on raylib library.                                                    |
| [FunWithEasings][MarcMDE-FunWithEasings]                                   | [MarcMDE][MarcMDE-github]                                   | Small and simple Easings visualizing tool developed in C with raylib and C easings.                                                               |
| [SharedBuff][Mudzii-SharedBuff]                                            | [Mudzii][Mudzii-github]                                     | Level editor using a shared buffer between an Maya API and raylib engine.                                                                         |
| [rFXGen][raysan5-rFXGen]                                                   | [raysan5][raysan5-github]                                   | Simple and easy-to-use fx sounds generator.                                                                                                       |
| [rPBR][victorfisac-rPBR]                                                   | [victorfisac][victorfisac-github]                           | 3D model viewer with PBR pipeline written using OpenGL with usage of raylib in pure C.                                                            |
| [raylib-libretro][RobLoach-raylib-libretro]                                | [RobLoach][RobLoach-github]                                 | [libretro][libretro-site] frontend using raylib.                                                                                                  |
| [FNode][victorfisac-FNode]                                                 | [victorfisac][victorfisac-github]                           | Tool based in nodes to build GLSL shaders without any programming knowledge written in C using OpenGL and GLFW.                                   |
| [RayTracer][MaximeHouis-RayTracer]                                         | [MaximeHouis][MaximeHouis-github]                           | Ray Tracer in C++ using raylib.                                                                                                                   |
| [GeldaEngine][fedqx-GeldaEngine]                                           | [fedqx][fedqx-github]                                       | C raylib game engine.                                                                                                                             |
| [rengfx][xdrie-rengfx]                                                     | [xdrie][xdrie-github]                                       | Lightweight, expressive, extensible 2D/3D game engine, Written in [D][dlang-lang].                                                                |
| [cbit-raylib][nurakmaljalil91-cbit-raylib]                                 | [nurakmaljalil91][nurakmaljalil91-github]                   | C++ Game Engine built on top of raylib.                                                                                                           |
| [PhysicsEngine][CarterPatterson-PhysicsEngine]                             | [CarterPatterson][CarterPatterson-github]                   | Simple physics engine built in raylib for [AIE][aie-au-site] CS 2019, Written in C++!                                                             |
| [Midday-Commander][Guevara-chan-Midday-Commander]                          | [Guevara-chan][Guevara-chan-github]                         | •Retrofuturistic file manager•, Written in [Nim][nim-lang].                                                                                       |
| [ttme][hfabre-ttme]                                                        | [hfabre][hfabre-github]                                     | Tiny tile map editor, Written in Go.                                                                                                              |
| [ArtColors][ProfJski-ArtColors]                                            | [ProfJski][ProfJski-github]                                 | Sort of color mixing tools built with raylib.                                                                                                     |
| [experimental-raygui-editor][Demizdor-experimental-raygui-editor]          | [Demizdor][Demizdor-github]                                 | Experimental GUI editor for raygui.                                                                                                               |
| [Raylib-Buildfiles][rfaile313-Raylib-Buildfiles]                           | [rfaile313][rfaile313-github]                               | Simple Makefile that incorporates raylib on OS: Windows && Platform: Desktop.                                                                     |
| [music-player][redsled84-music-player]                                     | [redsled84][redsled84-github]                               | Linked list music player using raylib.                                                                                                            |
| [riley-duper][ArnautDaniel-riley-duper]                                    | [ArnautDaniel][ArnautDaniel-github]                         | Iterative melancholy written in Factor.                                                                                                           |
| [raylib-vide-player][WEREMSOFT-raylib-vide-player]                         | [WEREMSOFT][WEREMSOFT-github]                               | Videoplayer using raylib. Play unsuported video format by the browser in the broswer.                                                             |
| [baslike-editor][TheLumaio-baslike-editor]                                 | [TheLumaio][TheLumaio-github]                               | Editor for [baslike][TheLumaio-baslike] written in raylib.                                                                                        |
| [PACKER][pkeckler-PACKER]                                                  | [pkeckler][pkeckler-github]                                 | raylib asset packer.                                                                                                                              |
| [Chip8-raylib][ComLarsic-Chip8-raylib]                                     | [ComLarsic][ComLarsic-github]                               | [CHIP-8][chip8-wikipedia] emulator written in C# using raylib.                                                                                    |
| [Chip8][LesFarrell-Chip8]                                                  | [LesFarrell][LesFarrell-github]                             | [CHIP-8][chip8-wikipedia] Emulator/Interpreter using written using C and the raylib library.                                                      |
| [cobra-py][ralsina-cobra-py]                                               | [ralsina][ralsina-github]                                   | 80s-style [Python][python-lang] environment.                                                                                                      |
| [Alien-raylib][athreef-Alien-raylib]                                       | [athreef][athreef-github]                                   | Alien distribution for raylib video game engine.                                                                                                  |
| [cpp-raylib-tilemap][JusticeShultz-cpp-raylib-tilemap]                     | [JusticeShultz][JusticeShultz-github]                       | Runtime tile map tool in the C++ raylib library.                                                                                                  |
| [MasterPlan][SolarLune-MasterPlan]                                         | [SolarLune][SolarLune-itchio]                               | easy-to-use graphical free-flow project management tool and idea board.                                                                           |
| [Cute Exporter][powerc9000-CuteAssetPipeline]                              | [Clay Murray][powerc9000-itchio]                            | The best PSD layers to PNG texture atlas exporter.                                                                                                |
| [MySprite][TonyButDead-MySprite]                                           | [TonyButDead][TonyButDead-itchio]                           | Free pixel art tool created in the Go programming language with raylib.                                                                           |
| [SeijiEmery's level editor][SeijiEmery-LevelEditor]                        | [SeijiEmery][SeijiEmery-itchio]                             | Quick experiment in building a small game/nice-ish level editor/platformer from scratch with raylib over a weekend.                               |
| [rTexPacker][raylibtech-rTexPacker]                                        | [raylib technologies][raylibtech-itchio]                    | Simple and easy-to-use textures packer and font atlas generator.                                                                                  |
| [rTexViewer][raylibtech-rTexViewer]                                        | [raylib technologies][raylibtech-itchio]                    | Simple and easy-to-use textures viewer and pixel formats converter.                                                                               |
| [rIconPacker][raylibtech-rIconPacker]                                      | [raylib technologies][raylibtech-itchio]                    | Simple and easy-to-use icons packer.                                                                                                              |
| [rGuiStyler][raylibtech-rGuiStyler]                                        | [raylib technologies][raylibtech-itchio]                    | Simple and easy-to-use raygui styles editor.                                                                                                      |
| [rGuiLayout][raylibtech-rGuiLayout]                                        | [raylib technologies][raylibtech-itchio]                    | Simple and easy-to-use raygui layouts editor.                                                                                                     |
| [rGuiIcons][raylibtech-rGuiIcons]                                          | [raylib technologies][raylibtech-itchio]                    | Simple and easy-to-use raygui icons editor.                                                                                                       |
| [graphingcalculator][obaodelana-graphingcalculator]                        | [obaodelana][obaodelana-github]                             | Graphing Calculator made with raylib using C.                                                                                                     |
| [LevelEditor-MayaPlugin][MadeleinNyblom-LevelEditor-MayaPlugin]            | [MadeleinNyblom][MadeleinNyblom-github]                     | Level editor that sends information from [Maya][autodesk-maya-site] to raylib using a circular buffer.                                            |
| [khkFramework-raylib][kenhyokun-khkFramework-raylib]                       | [kenhyokun][kenhyokun-github]                               | Experimental C/C++ 2D game framework with raylib.                                                                                                 |
| [abyss_engine][HurricaneInteractive-abyss_engine]                          | [HurricaneInteractive][HurricaneInteractive-github]         | Very simple game engine written in [Rust][rust-lang] and built on top of [raylib-rs][deltaphc-raylib-rs].                                         |
| [CopyCat][reidevries-CopyCat]                                              | [reidevries][reidevries-github]                             | C++ 17 Game engine based on raylib and [EnTT][258] libraries, end goal of creating a tactical RPG.                                                |
| [peryEngine][pery77-peryEngine]                                            | [pery77][pery77-github]                                     | C/C++ Retro game engine based on raylib.                                                                                                          |
| [Ungine][The-Italian-Coders-Group-Ungine]                                  | [The-Italian-Coders-Group][The-Italian-Coders-Group-github] | [Source][source-engine-site]-like raylib-based game engine for C++.                                                                               |
| [chat_from_scratch][senior-sigan-chat_from_scratch]                        | [senior-sigan][senior-sigan-github]                         | Code from the series of my streams where I work on creating Chat application absolutely from scratch, Written in C++.                             |
| [mmGame-Engine-Raylib-ECS][bayganik-mmGame-Engine-Raylib-ECS]              | [bayganik][bayganik-github]                                 | C# Game engine using Raylib-cs and [Entitas lite][268] as an ECS.                                                                                 |
| [ray-quake][xero1-ray-quake]                                               | [xero1][xero1-github]                                       | [.NET][dotnet-site] Core Quake source port built using raylib.                                                                                    |
| [raylibeditor][practicing01-raylibeditor]                                  | [practicing01][practicing01-github]                         | Editor made with raylib.                                                                                                                          |
| [tyro][parmaja-tyro]                                                       | [parmaja][parmaja-github]                                   | Simple graphical environment for kids and newbies, using raylib as small game engine to draw, Written in Pascal.                                  |
| [Raylibculator][Fakaaa-Raylibculator]                                      | [Fakaaa][Fakaaa-github]                                     | Calculator made with raylib.                                                                                                                      |
| [raylib_package][Elkantor-raylib_package]                                  | [Elkantor][Elkantor-github]                                 | [BSCXX][280] module for raylib C library.                                                                                                         |
| [clay][RafaelOliveira-clay]                                                | [RafaelOliveira][RafaelOliveira-github]                     | 2D game engine for raylib in C++.                                                                                                                 |
| [Quill][sparkskapil-Quill]                                                 | [sparkskapil][sparkskapil-github]                           | 2D CAD Application using raylib and C++.                                                                                                          |
| [RayLib-Keyboard-keycode-tester][jmorel33-RayLib-Keyboard-keycode-tester]  | [jmorel33][jmorel33-github]                                 | Keyboard tester made with raylib.                                                                                                                 |
| [sponGB][kugo12-sponGB]                                                    | [kugo12][kugo12-github]                                     | Gameboy emulator written using Rust and raylib.                                                                                                   |
| [BlobEditor][trikko-BlobEditor]                                            | [trikko][trikko-github]                                     | Simple raylib and Dlang project.                                                                                                                  |
| [nprof][Andre-LA-nprof]                                                    | [Andre-LA][Andre-LA-github]                                 | Very basic profiler for [raylib-nelua][Andre-LA-raylib-nelua], Written in [Nelua][nelua-lang].                                                    |
| [mc_rtc-raylib][gergondet-mc_rtc-raylib]                                   | [gergondet][gergondet-github]                               | Simple [mc_rtc][296] GUI client using raylib.                                                                                                     |
| [Red-Shell][KonPet-Red-Shell]                                              | [KonPet][KonPet-github]                                     | Level Editor for the Mario vs Luigi Python clone made in C++ using raylib.                                                                        |
| [XPROEngine][JonSnowbd-XPROEngine]                                         | [JonSnowbd][JonSnowbd-github]                               | build-inside C game engine that utilizes raylib/[Flecs][301]/[Binn][302] to create incredibly fast games with C/Lua.                              |
| [gargula][gilzoide-gargula]                                                | [gilzoide][gilzoide-github]                                 | Game engine based on nested structs and compile-time tree traversals powered by raylib and D compatible with better C.                            |
| [randevlper][rayoflight-randevlper]                                        | [rayoflight][rayoflight-github]                             | 2D Engine implementing [Box2D][box2d-site] and raylib.                                                                                            |
| [v2][notsnail-v2]                                                          | [notsnail][notsnail-github]                                 | Framework for games built with raylib.                                                                                                            |
| [particle_editor][Demizdor-particle_editor]                                | [Demizdor][Demizdor-github]                                 | Experimental particle editor!                                                                                                                     |
| [rlwm][gtrxAC-rlwm]                                                        | [gtrxAC][gtrxAC-github]                                     | Fake operating system/window manager.                                                                                                             |
| [HellRok][Taylor-HellRok]                                                  | [Taylor][Taylor-github]                                     | Simple game engine built using raylib and [MRuby][mruby-site].                                                                                    |
| [Sketch_Game_Engine][MallocStudio-Sketch_Game_Engine]                      | [MallocStudio][MallocStudio-github]                         | Simple game engine built on top of raylib that intended as personal hobby project.                                                                |
| [simple_raycasting][TheDarkBug-simple_raycasting]                          | [TheDarkBug][TheDarkBug-github]                             | Simple raycasting "engine" written in C with raylib for graphics.                                                                                 |
| [LunarViewer][LunaRyuko-LunarViewer]                                       | [LunaRyuko][LunaRyuko-github]                               | Model viewer for Quake 1 and Hexen 2.                                                                                                             |
| [mapviewer][myuce-mapviewer]                                               | [myuce][myuce-github]                                       | Very primitive map viewer for the Quake map format.                                                                                               |
| [minitile][catmanl-minitile]                                               | [catmanl][catmanl-github]                                   | A mini tilemap editor.                                                                                                                            |
| [PadCast][nantr0nic-PadCast]                                               | [nantr0nic][nantr0nic-github]                               | A simple gamepad display that shows controller activity, Written in C++ and geared towards streamers.                                             |

[gtrxAC-github]:                                 https://github.com/gtrxAC/gxarch
[adct-the-experimenter-github]:                  https://github.com/adct-the-experimenter
[Lockna-github]:                                 https://github.com/Lockna
[skylersaleh-github]:                            https://github.com/skylersaleh
[sparkskapil-github]:                            https://github.com/sparkskapil
[sorykkk-github]:                                https://github.com/sorykkk
[MarcMDE-github]:                                https://github.com/MarcMDE
[Mudzii-github]:                                 https://github.com/Mudzii
[MaximeHouis-github]:                            https://github.com/MaximeHouis
[fedqx-github]:                                  https://github.com/fedqx
[xdrie-github]:                                  https://github.com/xdrie
[TSnake41-github]:                               https://github.com/TSnake41
[nurakmaljalil91-github]:                        https://github.com/nurakmaljalil91
[CarterPatterson-github]:                        https://github.com/CarterPatterson
[Guevara-chan-github]:                           https://github.com/Guevara-chan
[hfabre-github]:                                 https://github.com/hfabre
[rfaile313-github]:                              https://github.com/rfaile313
[redsled84-github]:                              https://github.com/redsled84
[ArnautDaniel-github]:                           https://github.com/ArnautDaniel
[pkeckler-github]:                               https://github.com/pkeckler
[ComLarsic-github]:                              https://github.com/ComLarsic
[LesFarrell-github]:                             https://github.com/LesFarrell
[ralsina-github]:                                https://github.com/ralsina
[athreef-github]:                                https://github.com/athreef
[SolarLune-itchio]:                              https://solarlune.itch.io
[powerc9000-itchio]:                             https://powerc9000.itch.io
[TonyButDead-itchio]:                            https://tonybutdead.itch.io
[SeijiEmery-itchio]:                             https://seijiemery.itch.io
[raylibtech-itchio]:                             https://raylibtech.itch.io
[obaodelana-github]:                             https://github.com/obaodelana
[MadeleinNyblom-github]:                         https://github.com/MadeleinNyblom
[kenhyokun-github]:                              https://github.com/kenhyokun
[HurricaneInteractive-github]:                   https://github.com/HurricaneInteractive
[reidevries-github]:                             https://github.com/reidevries
[pery77-github]:                                 https://github.com/pery77
[Italian-Coders-Group-github]:                   https://github.com/Italian-Coders-Group
[senior-sigan-github]:                           https://github.com/senior-sigan
[bayganik-github]:                               https://github.com/bayganik
[xero1-github]:                                  https://github.com/xero1
[practicing01-github]:                           https://github.com/practicing01
[parmaja-github]:                                https://github.com/parmaja
[Fakaaa-github]:                                 https://github.com/Fakaaa
[Elkantor-github]:                               https://github.com/Elkantor
[RafaelOliveira-github]:                         https://github.com/RafaelOliveira
[jmorel33-github]:                               https://github.com/jmorel33
[kugo12-github]:                                 https://github.com/kugo12
[trikko-github]:                                 https://github.com/trikko
[Andre-LA-github]:                               https://github.com/Andre-LA
[gergondet-github]:                              https://github.com/gergondet
[KonPet-github]:                                 https://github.com/KonPet
[JonSnowbd-github]:                              https://github.com/JonSnowbd
[gilzoide-github]:                               https://github.com/gilzoide
[randevlper-github]:                             https://github.com/randevlper
[notsnail-github]:                               https://github.com/notsnail
[erikerlandson-github]:                          https://github.com/erikerlandson
[HellRok-github]:                                https://github.com/HellRok
[MallocStudio-github]:                           https://github.com/MallocStudio
[TheDarkBug-github]:                             https://github.com/TheDarkBug
[LunaRyuko-github]:                              https://github.com/LunaRyuko
[myuce-github]:                                  https://github.com/myuce
[catmanl-github]:                                https://github.com/catmanl
[nantr0nic-github]:                              https://github.com/nantr0nic

[gtrxAC-gxSE]:                                   https://github.com/gtrxAC/gxSE
[adct-the-experimenter-3d-audio-producer]:       https://github.com/adct-the-experimenter/3d-audio-producer
[adct-the-experimenter-binaural-audio-editor]:   https://github.com/adct-the-experimenter/binaural-audio-editor
[Lockna-chip8]:                                  https://github.com/Lockna/chip8
[skylersaleh-SkyBoy]:                            https://github.com/skylersaleh/SkyBoy
[sparkskapil-2D-CAD-Raylib]:                     https://github.com/sparkskapil/2D-CAD-Raylib
[sorykkk-raygui_calculator]:                     https://github.com/sorykkk/raygui_calculator
[MarcMDE-FunWithEasings]:                        https://github.com/MarcMDE/FunWithEasings
[Mudzii-SharedBuff]:                             https://github.com/Mudzii/SharedBuff
[raysan5-rfxgen]:                                https://github.com/raysan5/rfxgen
[victorfisac-rPBR]:                              https://github.com/victorfisac/rPBR
[RobLoach-raylib-libretro]:                      https://github.com/RobLoach/raylib-libretro
[victorfisac-FNode]:                             https://github.com/victorfisac/FNode
[MaximeHouis-RayTracer]:                         https://github.com/MaximeHouis/RayTracer
[fedqx-GeldaEngine]:                             https://github.com/fedqx/GeldaEngine
[xdrie-rengfx]:                                  https://github.com/xdrie/rengfx
[TSnake41-raylib-lua]:                           https://github.com/TSnake41/raylib-lua
[nurakmaljalil91-cbit-raylib]:                   https://github.com/nurakmaljalil91/cbit-raylib
[CarterPatterson-PhysicsEngine]:                 https://github.com/CarterPatterson/PhysicsEngine
[Guevara-chan-Midday-Commander]:                 https://github.com/Guevara-chan/Midday-Commander
[hfabre-ttme]:                                   https://github.com/hfabre/ttme
[ProfJski-ArtColors]:                            https://github.com/ProfJski/ArtColors
[Demizdor-experimental-raygui-editor]:           https://github.com/Demizdor/experimental-raygui-editor
[rfaile313-Raylib-Buildfiles]:                   https://github.com/rfaile313/Raylib-Buildfiles
[redsled84-music-player]:                        https://github.com/redsled84/music-player
[ArnautDaniel-riley-duper]:                      https://github.com/ArnautDaniel/riley-duper
[WEREMSOFT-c99-raylib-vide-player]:              https://github.com/WEREMSOFT/c99-raylib-vide-player
[TheLumaio-baslike-editor]:                      https://github.com/TheLumaio/baslike-editor
[TheLumaio-baslike]:                             https://github.com/TheLumaio/baslike
[pkeckler-PACKER]:                               https://github.com/pkeckler/PACKER
[ComLarsic-Chip8-raylib]:                        https://github.com/ComLarsic/Chip8-raylib
[LesFarrell-Chip8]:                              https://github.com/LesFarrell/Chip8
[ralsina-cobra-py]:                              https://github.com/ralsina/cobra-py
[athreef-Alien-raylib]:                          https://github.com/athreef/Alien-raylib
[JusticeShultz-cpp-raylib-tilemap]:              https://github.com/JusticeShultz/cpp-raylib-tilemap
[SolarLune-MasterPlan]:                          https://solarlune.itch.io/masterplan
[powerc9000-CuteAssetPipeline]:                  https://powerc9000.itch.io/cute-asset-pipeline
[TonyButDead-MySprite]:                          https://tonybutdead.itch.io/mysprite
[SeijiEmery-LevelEditor]:                        https://seijiemery.itch.io/agj-level-editor-in-a-weekend
[raylibtech-rtexpacker]:                         https://raylibtech.itch.io/rtexpacker
[raylibtech-rtexviewer]:                         https://raylibtech.itch.io/rtexviewer
[raylibtech-riconpacker]:                        https://raylibtech.itch.io/riconpacker
[raylibtech-rguistyler]:                         https://raylibtech.itch.io/rguistyler
[raylibtech-rguilayout]:                         https://raylibtech.itch.io/rguilayout
[raylibtech-rguiicons]:                          https://raylibtech.itch.io/rguiicons
[obaodelana-graphingcalculator]:                 https://github.com/obaodelana/graphingcalculator
[MadeleinNyblom-LevelEditor-MayaPlugin]:         https://github.com/MadeleinNyblom/LevelEditor-MayaPlugin
[kenhyokun-khkFramework-raylib]:                 https://github.com/kenhyokun/khkFramework-raylib
[HurricaneInteractive-abyss_engine]:             https://github.com/HurricaneInteractive/abyss_engine
[deltaphc-raylib-rs]:                            https://github.com/deltaphc/raylib-rs
[reidevries-CopyCat]:                            https://github.com/reidevries/CopyCat
[skypjack-entt]:                                 https://github.com/skypjack/entt
[pery77-peryEngine]:                             https://github.com/pery77/peryEngine
[Italian-Coders-Group-Ungine]:                   https://github.com/Italian-Coders-Group/Ungine
[senior-sigan-chat_from_scratch]:                https://github.com/senior-sigan/chat_from_scratch
[bayganik-mmGame-Engine-Raylib-ECS]:             https://github.com/bayganik/mmGame-Engine-Raylib-ECS
[rocwood-Entitas-Lite]:                          https://github.com/rocwood/Entitas-Lite
[xero1-ray-quake]:                               https://github.com/xero1/ray-quake
[practicing01-raylibeditor]:                     https://github.com/practicing01/raylibeditor
[parmaja-tyro]:                                  https://github.com/parmaja/tyro
[Fakaaa-Raylibculator]:                          https://github.com/Fakaaa/Raylibculator
[Elkantor-raylib_package]:                       https://github.com/Elkantor/raylib_package
[Elkantor-bscxx]:                                https://github.com/Elkantor/bscxx
[RafaelOliveira-clay]:                           https://github.com/RafaelOliveira/clay
[sparkskapil-Quill]:                             https://github.com/sparkskapil/Quill
[jmorel33-RayLib-Keyboard-keycode-tester]:       https://github.com/jmorel33/RayLib-Keyboard-keycode-tester
[kugo12-sponGB]:                                 https://github.com/kugo12/sponGB
[trikko-BlobEditor]:                             https://github.com/trikko/BlobEditor
[Andre-LA-nprof]:                                https://github.com/Andre-LA/nprof
[Andre-LA-raylib-nelua]:                         https://github.com/Andre-LA/raylib-nelua
[gergondet-mc_rtc-raylib]:                       https://github.com/gergondet/mc_rtc-raylib
[jrl-umi3218-mc_rtc]:                            https://github.com/jrl-umi3218/mc_rtc
[KonPet-Red-Shell]:                              https://github.com/KonPet/Red-Shell
[JonSnowbd-XPROEngine]:                          https://github.com/JonSnowbd/XPROEngine
[SanderMertens-flecs]:                           https://github.com/SanderMertens/flecs
[liteserver-binn]:                               https://github.com/liteserver/binn
[gilzoide-gargula]:                              https://github.com/gilzoide/gargula
[randevlper-rayoflight]:                         https://github.com/randevlper/rayoflight
[notsnail-v2]:                                   https://github.com/notsnail/v2
[erikerlandson-ray-ubi]:                         https://github.com/erikerlandson/ray-ubi
[Demizdor-particle_editor]:                      https://github.com/Demizdor/particle_editor
[gtrxAC-rlwm]:                                   https://github.com/gtrxAC/rlwm
[HellRok-Taylor]:                                https://github.com/HellRok/Taylor
[MallocStudio-Sketch_Game_Engine]:               https://github.com/MallocStudio/Sketch_Game_Engine
[TheDarkBug-simple_raycasting]:                  https://github.com/TheDarkBug/simple_raycasting
[LunaRyuko-LunarViewer]:                         https://github.com/LunaRyuko/LunarViewer
[myuce-mapviewer]:                               https://github.com/myuce/mapviewer
[catmanl-minitile]:                              https://github.com/catmanl/minitile
[nantr0nic-PadCast]:                             https://github.com/nantr0nic/PadCast

[chip8-wikiedia]:                                https://en.wikipedia.org/wiki/CHIP-8
[libretro-site]:                                 https://www.libretro.com
[dlang-lang]:                                    https://dlang.org
[lua-lang]:                                      https://lua.org
[aie-au-site]:                                   https://aieinstitute.edu.au
[nim-lang]:                                      https://nim-lang.org
[python-lang]:                                   https://python.org
[autodesk-maya-site]:                            https://www.autodesk.com/products/maya/overview
[rust-lang]:                                     https://www.rust-lang.org
[source-engine-site]:                            https://developer.valvesoftware.com/wiki/Source
[dotnet-site]:                                   https://dotnet.microsoft.com
[nelua-lang]:                                    https://nelua.io
[box2d-site]:                                    https://box2d.org
[rhel-ubi-site]:                                 https://developers.redhat.com/products/rhel/ubi
[mruby-site]:                                    https://mruby.org

### Deprecated/Removed/Unknown bindings

| Name                                                 | Author                                | Language                          |
|------------------------------------------------------|---------------------------------------|-----------------------------------|
| [Raylib-J][CreedVI-Raylib-J]                         | [CreedVI][CreedVI-github]             | Java ([LWJGL3][lwjgl3-java-lang]) |
| [rust_raylib_bindings][DevJac-rust_raylib_bindings]  | [DevJac][DevJac-github]               | Rust                              |
| [raylib-rust][dtcristo-raylib-rust]                  | [dtcristo][dtcristo-github]           | Rust                              |
| [Raylib-for-GLBasic][SliverLIVE-Raylib-for-GLBasic]  | [SliverLIVE][SliverLIVE-github]       | [GLBasic][glbasic-lang]           |
| [fb-raylib][glasyalabolas-fb-raylib]                 | [glasyalabolas][glasyalabolas-github] | [FreeBASIC][freebasic-lang]       |
| [raylib-haxe][haxeui-raylib-haxe]                    | [haxeui][haxeui-github]               | [Haxe][haxe-lang]                 |
| [rayex][shiryel-rayex]                               | [shiryel][shiryel-github]             | [Elixir][elixir-lang]             |

[CreedVI-github]:                 https://github.com/CreedVI
[DevJac-github]:                  https://github.com/DevJac
[dtcristo-github]:                https://github.com/dtcristo
[SliverLIVE-github]:              https://github.com/SliverLIVE
[glasyalabolas-github]:           https://github.com/glasyalabolas
[shiryel-github]:                 https://github.com/shiryel

[CreedVI-Raylib-J]:               https://github.com/CreedVI/Raylib-J
[DevJac-rust_raylib_bindings]:    https://github.com/DevJac/rust_raylib_bindings
[dtcristo-raylib-rust]:           https://github.com/dtcristo/raylib-rust
[SliverLIVE-Raylib-for-GLBasic]:  https://github.com/SliverLIVE/Raylib-for-GLBasic
[glasyalabolas-fb-raylib]:        https://github.com/glasyalabolas/fb-raylib
[haxeui-raylib-haxe]:             https://github.com/haxeui/raylib-haxe
[shiryel-rayex]:                  https://github.com/shiryel/rayex

[lwjgl3-java-lang]:               https://www.lwjgl.org
[glbasic-lang]:                   https://www.glbasic.com
[freebasic-lang]:                 https://www.freebasic.net
[haxe-lang]:                      https://haxe.org
[elixir-lang]:                    https://elixir-lang.org

> NOTE: You won't find these bindings in [BINDINGS.md](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)!

### Libraries bindings/ports

| Name                                                      | Author                      | Description              |
|-----------------------------------------------------------|-----------------------------|--------------------------|
| [rayfork-rs][Dacode45-rayfork-rs]                         | [Dacode45][Dacode45-github] | Port of rayfork to Rust. |
| [Animator-For-Raylib-CS][EMoore13-Animator-For-Raylib-CS] | [EMoore13][EMoore13-github] | Modified version of AliElSaleh's Animator-For-Raylib that uses raylib-cs! |

[Dacode45-github]:                 https://github.com/Dacode45
[EMoore13-github]:                 https://github.com/EMoore13

[Dacode45-rayfork-rs]:             https://github.com/Dacode45/rayfork-rs
[EMoore13-Animator-for-Raylib-CS]: https://github.com/EMoore13/Animator-For-Raylib-CS

### Community Examples

<!-- TODO refactor readability -->

| Name                    | Author          | Description                |
|-------------------------|-----------------|----------------------------|
| [WaveEquationDemo][351] | [ProfJski][151] | intuitive approach to introducing the [Schrodinger][352] wave equation using a classical particle. |
| [IndieStudio][353] | [antwxne][354] | [Epitech][355] 2nd year end year 3D graphical project in C++. |
| [raylib-instancing][358] | [ChrisDill][359] | Instanced rendering examples using raylib. |
| [AIEYear1Samples][360] | [AcademyOfInteractiveEntertainment][361] | Sample and tutorial code for AIE's Diploma of Digital and Interactive Games. |
| [raylibShadowmap][362] | [GoldenThumbs][363] | Shadowmapping with raylib! |
| [raylibvscodeexample][364] | [Lightnet][365] | [VSCode][366] project sample for raylib. |
| [RayWorld3D][367] | [jpike][368] | Playing around with raylib's 3D stuff. |
| [Cosmic-Hell][369] | [AliElSaleh][146] | AIE Holiday Coding Challenge. A Bullet-Hell game that implements flocking in C/C++ using raylib. |
| [Game-of-Life-in-Multiple-Languages][370] | [Skaruts][371] | Game of Life implemented in multiple languages and has version for raylib. |
| [CHUCK][372] | [I3uckwheat][373] | Allows tiled maps to be used with raylib with little trouble. |
| [2d-physics-engine-test][374] | [machinbrol][375] | 2D-physics-engine test with Go port of raylib. |
| [nim-raylib-forever-raylib-audio-bug][376] | [Ryan1729][377] | Example shows audio bug in [raylib-forever][378] Nim bindings. |
| [ray-lib-example][379] | [kebbbnnn][380] | raylib example for MacOS. |
| [raylib-physics-example][381] | [Dacode45][348] | Rust example of physics specs and raylib all coming together. |
| [EmscriptenHelloRaylib][382] | [aaronrcox][383] | Emscripten (Web) Starter repo for raylib projects. Web builds are automaticly triggered via Github actions and Deployed to Github Pages. |
| [raylib-3rdPersonCameraWallDetection][384] | [chbdev][385] | Third person camera wall detection example. |
| [ThreadLab][386] | [gabriellm1][387] | Multi-thread copy and paste program with graphic interface for raylib. |
| [permadi-port][388] | [jacmoe][389] | [Permadi][390]'s Raycaster code ported to C++ and raylib. |
| [BinaryTree][391] | [MitchellRB][392] | Visual representation of a binary tree in raylib. |
| [Clock][393] | [xav1t0][394] | Clock Made With raylib in C. |
| [rMandelbrotset][395] | [JRAM0012][396] | Mandelbrot set visualizer made in raylib. |
| [opencv_raylib][397] | [danimartin82][398] | Tests for mixing [OpenCV][399] (4.2.0) with raylib (3.0). |
| [RaylibTest][400] | [Lisoph][401] | Examples of messing up with raylib. |
| [raylib-practices][402] | [ianpan870102][403] | Some personal practices with raylib and [raylib-cpp][404] in C++. |
| [cellular_automata][405] | [zmontross][406] | First foray into using raylib as an excuse to practice C programming. No planning, and lots of spaghetti code. |
| [simulation][407] | [Elkantor][279] | Flow simulation. |
| [Wolf3DClone][408] | [albertnadal][409] | Implementation of the "Wolfenstein 3D"(1992) game engine from scratch using vanilla C and raylib. |
| [ccleste-raylib][410] | [kawa-yoiko][411] | Adaptation of [ccleste][412] to raylib with software rendering. |
| [LearningRaylib][413] | [EdSwordsmith][414] | Small projects made with raylib. |
| [raylib-bench-go][415] | [nikki93][416] | Benchmark written in Go. |
| [ca-particle-system][417] | [rurush47][418] | Particle system for university project written in C++ using raylib. |
| [RayLib-Examples][419] | [ProfJski][151] | Some fun math or physics demos made easy with raylib and written in C++. |
| [orbisGl2samples][420] | [orbisdev][46] | orbisGl2 raylib samples for liborbis (For PlayStation 4). |
| [RaylibErosionStandalone][421] | [Delvix000][422] | Graphics demo with that features a procedural tropical island and some cool stuff! |
| [Raylib-Examples][423] | [Pakz001][424] | Collection of raylib code examples - For learning the C language with 2D and 3D games. |
| [Raylib-cs-Examples][425] | [ChrisDill][359] | C# examples for raylib-cs. |
| [rayfork-tests][426] | [SasLuca][52] | Collection of examples written in rayfork that also serve as tests. |
| [cray-examples][427] | [dtcristo][428] | raylib examples ported to Crystal. |
| [raylib-games][429] | [raysan5][56] | raysan5's collection of games made with raylib. |
| [c99-raylib-car-physics][431] | [WEREMSOFT][93] | Car physiscs made with raylib. |
| [c99-raylib-shadowmap][432] | [WEREMSOFT][93] | Shadowmap implementation in raylib. |
| [Dlang-Game-Dev][433] | [rillk500][434] | Games created with D programming language. |
| [Learn-Dlang-game-dev][435] | [rillk500][434] | Learn D programming language by creating games! |
| [clang-game-dev][436] | [rillk500][434] | Games created with C programming language. |
| [zig-raylib-experiments][437] | [BitPuffin][438] | Some classic game implementations in [Zig][439] using raylib. |
| [Dnkvw-Raylib-Example][440] | [DaNiKhan-GbR][441] | Virtual window raylib 3D Example. |
| [rlexp][442] | [Demizdor][14] | Experiments using the raylib library. |
| [tic-tac-toe-ai][443] | [fr3fou][444] | Tic-Tac-Toe implementation and AI, using Raylib for the GUI and Minimax + Alpha-Beta pruning for the AI. |
| [raylib-line-triangulator][445] | [petuzk][446] | Line triangulation algorithm for raylib. |
| [SmurfInvaders][447] | [ThePituLegend][448] | Technical Demo as an explorative project of raylib. Random game based on Space Invaders and alike. |
| [recursive-sudoku-viz][449] | [riadafridishibly][450] | Recursive sudoku solver visualizer in raylib, Written in C++. |
| [RaylibCSGraphs][451] | [GheorgheMorari][452] | Practical implementation of Linear Transfromation, Written in C#. |
| [critter_comforts][453] | [Sepheus][454] | Source code of hit first game from legendary studio Vat O'Coffee. Coded for the V&A Operas & Bridges GameJam, Written in D. |
| [VoronoiDiagram][455] | [DavinderMaverick][456] | Voronoi Diagrams using Fortune's Algo, Written in C++. |
| [corosim][457] | [apahl][458] | Simple infection simulator, written in [Swift][459] using raylib. |
| [baylej tmx raylib examples][460] | [baylej][461] | Example of C tmx map loader that uses raylib. |
| [MandelbrotGoLang][462] | [albertnadal][409] | Distributed computing Mandelbrot implementation using Go, [gRPC][463] and raylib. |
| [raylib_tiled_import_with_tmx][464] | [OnACoffeeBreak][465] | Example of how to use raylib to import and display a Tiled map editor file. |
| [Raylib-shaders][466] | [MrOneTwo][467] | Having fun with shaders. |
| [Demo-Paradox][468] | [anatagawa][469] | Demo with raylib. |
| [Demo-Interpole][470] | [anatagawa][469] | Demo with raylib. |
| [Demo-Awesome][471] | [anatagawa][469] | Demo with raylib. |
| [raylib nbnet examples][472] | [nathhB][473] | raylib example for [nbnet][474], single-header C network library to implement client-server network code for games. |
| [Raygui_Helloworld][475] | [edomin][476] | Example of using raygui library with [tigr][477] graphics library. |
| [evaluate-raylib][478] | [badlydrawnrod][479] | Few short and cross-platform raylib demos. Known to work on Windows, Raspberry Pi 400 (desktop + native), Web (emscripten). |
| [RayLib-Video-Modes][480] | [jmorel33][285] | Example of getting list of monitor's video modes from GLFW3 with raylib! |
| [Raylib-Joystick][481] | [TheCatOverlord][482] | Example implementing Joystick input for raylib using `<linux/joystick.h>` Linux module! |
| [dvd_screensaver][483] | [tomxmm0][484] | DVD Screensaver made with raylib. |
| [raylib-qrcode][485] | [Razikus][486] | QR Code generator for raylib using [nayuki/QR-Code-generator][487] lib. |
| [keyListener][488] | [zvoskars][489] | Program that follows key inputs using C++ and raylib for [Trackmania][490]. |
| [simple_games][491] | [senior-sigan][265] | Games created during live-streams by Ilya Siganov. |
| [FPS-engine-raylib][492] | [ValiantInteractive][493] | FPS game engine and simple First Person Shooter created with raylib using the C language. |
| [Chrome-Dino-game-ripoff-][494] | [PixelPhobicGames][495] | Chrome Dinosaur game written in C using raylib. |
| [raylib_projects][496] | [nas-programmer][497] | Things made with raylib and C++. |
| [Spirograph][498] | [NevilleJS][499] | Spirograph made in C++ using raylib. |
| [Worley-noise-raylib][500] | [someone-existing][501] | Extremely slow and buggy implementation of [Worley noise][502] done in raylib and C++. |
| [PathFinding][503] | [Rledrin][504] | C++ PathFinding example for raylib. |
| [RayCasting2D][505] | [Rledrin][504] | C++ Raycasting example for raylib. |
| [Raylib_TrueTileCollision][506] | [nezvers][73] | Retro platformer collision paired with modern approach utilizing delta time. |
| [raylib-raycaster][507] | [justinac0][508] | Basic raycaster implementation in C using raylib for rendering. |
| [raylib-bunnymark][509] | [RafaelOliveira][510] | Simple Bunnymark test with raylib. |
| [webcam_raylib][511] | [henriquel1997][512] | Test program that displays a webcam feed into a window and uses ESCAPI and raylib. |
| [match-three][513] | [yaram][514] | C++ Simple match-three prototype using raylib. |
| [ray-odh-demo][515] | [erikerlandson][311] | Prototype an integration of ray with Open Data Hub, using a singleuser profile to provision a ray cluster. |
| [metro][516] | [neonmoe][517] | Raymarched exploration of floating-point errors in a metro tunnel. |
| [RLSolarSystem][518] | [arinal][519] | Solar system simulation based on [arinal/WPFSolarSystem][520] but via raylib-cs in C#. |
| [raylib-demo][521] | [Adobe-Android][522] | raylib demo project using C++ and CMake. |
| [Caption][523] | [PHILLIPGATLIN][524] | Image captioning program made with raylib. |
| [raylib_examples_to_learn][525] | [gihadmecha][526] | Some raylib examples. |
| [rayMaschine][527] | [danimartin82][398] | Project for the raylib 32x32 Competition. |
| [RaylibPhysics][528] | [JusticeShultz][529] | Physics in C++. |
| [my-awesome-project][530] | [pintertamas][531] | Programming homework that uses the raylib library for graphics. |
| [bruhmoment3124/raylib][532] | [bruhmoment3124][533] | Things made with raylib. |
| [gamedev-experiments][534] | [feihong][535] | [Feihong][535]'s raylib quickstart.|
| [raylib-particles][536] | [creikey][537] | Particles life made in raylib. |
| [Raylib-3d-Test][538] | [t0rre][539]  | Test with 3D in raylib. |
| [GravitationalAcceleration][540] | [JohnLins][541] | Example(s) for gravity with acceleration! |
| [Altair8800][542] | [DoctorAkula][543] | Front panel emulation of the MITS Altair 8800 written in C using raylib. |
| [rsim][544] | [fullnitrous][545] | Cross platform rocket simulation software package written in C with raylib. |
| [Pepper-s-Pi-Cone][546] | [jessp][547] | WIP repository to adapt Roxanne Luo's Pepper's cone into C with raylib with the intention of running it off a Raspberry Pi. |
| [Nachasic][548] | [vicarious-rs][549] | Gamedev experiments with raylib and Rust. |
| [raylib-rs-play_sound_multi][550] | [buribalazs][551] | Example to demonstrate a crash on Windows 10 written in Rust. |
| [rts][552] | [teh-cmc][553] | Building an RTS the old way, with Rust, raylib & Emscripten. |
| [raylib_ffi_bug][554] | [jestarray][555] | Incorrect FFI call which turning bool to a random number, Written in Rust. |
| [raylib-bubbles][630] | [magnetrwn][631] | C++11 Raylib bubble shooter example, with thorough documentation. |

[351]: https://github.com/ProfJski/WaveEquationDemo
[352]: https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation
[353]: https://github.com/antwxne/IndieStudio
[354]: https://github.com/antwxne
[355]: https://www.epitech.eu/en
[356]: https://github.com/Armapillow/bezier
[357]: https://github.com/Armapillow
[358]: https://github.com/ChrisDill/raylib-instancing
[359]: https://github.com/ChrisDill
[360]: https://github.com/AcademyOfInteractiveEntertainment/AIEYear1Samples
[361]: https://github.com/AcademyOfInteractiveEntertainment
[362]: https://github.com/GoldenThumbs/raylibShadowmap
[363]: https://github.com/GoldenThumbs
[364]: https://github.com/Lightnet/raylibvscodeexample
[365]: https://github.com/Lightnet
[366]: https://code.visualstudio.com
[367]: https://github.com/jpike/RayWorld3D
[368]: https://github.com/jpike
[369]: https://github.com/AliElSaleh/Cosmic-Hell
[370]: https://github.com/Skaruts/Game-of-Life-in-Multiple-Languages
[371]: https://github.com/Skaruts
[372]: https://github.com/I3uckwheat/CHUCK
[373]: https://github.com/I3uckwheat
[374]: https://github.com/machinbrol/2d-physics-engine-test
[375]: https://github.com/machinbrol
[376]: https://github.com/Ryan1729/nim-raylib-forever-raylib-audio-bug
[377]: https://github.com/Ryan1729
[378]: https://github.com/Guevara-chan/Raylib-Forever
[379]: https://github.com/kebbbnnn/ray-lib-example
[380]: https://github.com/kebbbnnn
[381]: https://github.com/Dacode45/raylib-physics-example
[382]: https://github.com/aaronrcox/EmscriptenHelloRaylib
[383]: https://github.com/aaronrcox
[384]: https://github.com/chbdev/raylib-3rdPersonCameraWallDetection
[385]: https://github.com/chbdev
[386]: https://github.com/gabriellm1/ThreadLab
[387]: https://github.com/gabriellm1
[388]: https://github.com/jacmoe/permadi-port
[389]: https://github.com/jacmoe
[390]: https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents
[391]: https://github.com/MitchellRB/BinaryTree
[392]: https://github.com/MitchellRB
[393]: https://github.com/xav1t0/Clock
[394]: https://github.com/xav1t0
[395]: https://github.com/JRAM0012/rMandelbrotset
[396]: https://github.com/JRAM0012
[397]: https://github.com/danimartin82/opencv_raylib
[398]: https://github.com/danimartin82
[399]: https://opencv.org
[400]: https://github.com/Lisoph/RaylibTest
[401]: https://github.com/Lisoph
[402]: https://github.com/ianpan870102/raylib-practices
[403]: https://github.com/ianpan870102
[404]: https://github.com/RobLoach/raylib-cpp
[405]: https://github.com/zmontross/cellular_automata
[406]: https://github.com/zmontross
[407]: https://github.com/Elkantor/simulation
[408]: https://github.com/albertnadal/Wolf3DClone
[409]: https://github.com/albertnadal
[410]: https://github.com/kawa-yoiko/ccleste-raylib
[411]: https://github.com/kawa-yoiko
[412]: https://github.com/lemon32767/ccleste
[413]: https://github.com/EdSwordsmith/LearningRaylib
[414]: https://github.com/EdSwordsmith
[415]: https://github.com/nikki93/raylib-bench-go
[416]: https://github.com/nikki93
[417]: https://github.com/rurush47/ca-particle-system
[418]: https://github.com/rurush47
[419]: https://github.com/ProfJski/RayLib-Examples
[420]: https://github.com/orbisdev/orbisGl2samples
[421]: https://github.com/Delvix000/RaylibErosionStandalone
[422]: https://github.com/Delvix000
[423]: https://github.com/Pakz001/Raylib-Examples
[424]: https://github.com/Pakz001
[425]: https://github.com/ChrisDill/Raylib-cs-Examples
[426]: https://github.com/SasLuca/rayfork-tests
[427]: https://github.com/dtcristo/cray-examples
[428]: https://github.com/dtcristo
[429]: https://github.com/raysan5/raylib-games
[431]: https://github.com/WEREMSOFT/c99-raylib-car-physics
[432]: https://github.com/WEREMSOFT/c99-raylib-shadowmap
[433]: https://github.com/rillk500/Dlang-Game-Dev
[434]: https://github.com/rillk500
[435]: https://github.com/rillk500/Learn-Dlang-game-dev
[436]: https://github.com/rillk500/clang-game-dev
[437]: https://github.com/BitPuffin/zig-raylib-experiments
[438]: https://github.com/BitPuffin
[439]: https://ziglang.org
[440]: https://github.com/DaNiKhan-GbR/Dnkvw-Raylib-Example
[441]: https://github.com/DaNiKhan-GbR
[442]: https://github.com/Demizdor/rlexp
[443]: https://github.com/fr3fou/tic-tac-toe-ai
[444]: https://github.com/fr3fou
[445]: https://github.com/petuzk/raylib-line-triangulator
[446]: https://github.com/petuzk
[447]: https://github.com/ThePituLegend/SmurfInvaders
[448]: https://github.com/ThePituLegend
[449]: https://github.com/riadafridishibly/recursive-sudoku-viz
[450]: https://github.com/riadafridishibly
[451]: https://github.com/GheorgheMorari/RaylibCSGraphs
[452]: https://github.com/GheorgheMorari
[453]: https://github.com/Sepheus/critter_comforts
[454]: https://github.com/Sepheus
[455]: https://github.com/DavinderMaverick/VoronoiDiagram
[456]: https://github.com/DavinderMaverick
[457]: https://github.com/apahl/corosim
[458]: https://github.com/apahl
[459]: https://swift.org
[460]: https://github.com/baylej/tmx/tree/master/examples/raylib
[461]: https://github.com/baylej
[462]: https://github.com/albertnadal/MandelbrotGoLang
[463]: https://grpc.io
[464]: https://github.com/OnACoffeeBreak/raylib_tiled_import_with_tmx
[465]: https://github.com/OnACoffeeBreak
[466]: https://github.com/MrOneTwo/Raylib-shaders
[467]: https://github.com/MrOneTwo
[468]: https://github.com/anatagawa/Demo-Paradox
[469]: https://github.com/anatagawa
[470]: https://github.com/anatagawa/Demo-Interpole
[471]: https://github.com/anatagawa/Demo-Awesome
[472]: https://github.com/nathhB/nbnet/tree/master/examples/raylib
[473]: https://github.com/nathhB
[474]: https://github.com/nathhB/nbnet
[475]: https://github.com/edomin/Raygui_Helloworld
[476]: https://github.com/edomin
[477]: https://github.com/erkkah/tigr
[478]: https://github.com/badlydrawnrod/evaluate-raylib
[479]: https://github.com/badlydrawnrod
[480]: https://github.com/jmorel33/RayLib-Video-Modes
[481]: https://github.com/TheCatOverlord/Raylib-Joystick
[482]: https://github.com/TheCatOverlord
[483]: https://github.com/tomxmm0/dvd_screensaver
[484]: https://github.com/tomxmm0
[485]: https://github.com/Razikus/raylib-qrcode
[486]: https://github.com/Razikus
[487]: https://github.com/nayuki/QR-Code-generator
[488]: https://github.com/zvoskars/keyListener
[489]: https://github.com/zvoskars
[490]: https://www.trackmania.com
[491]: https://github.com/senior-sigan/simple_games
[492]: https://github.com/ValiantInteractive/FPS-engine-raylib
[493]: https://github.com/ValiantInteractive
[494]: https://github.com/PixelPhobicGames/Chrome-Dino-game-ripoff-
[495]: https://github.com/PixelPhobicGames
[496]: https://github.com/nas-programmer/raylib_projects
[497]: https://github.com/nas-programmer
[498]: https://github.com/NevilleJS/spirograph
[499]: https://github.com/NevilleJS
[500]: https://github.com/someone-existing/Worley-noise-raylib
[501]: https://github.com/someone-existing
[502]: https://en.wikipedia.org/wiki/Worley_noise
[503]: https://github.com/Rledrin/PathFinding
[504]: https://github.com/Rledrin
[505]: https://github.com/Rledrin/RayCasting2D
[506]: https://github.com/nezvers/Raylib_TrueTileCollision
[507]: https://github.com/justinac0/raylib-raycaster
[508]: https://github.com/justinac0
[509]: https://github.com/RafaelOliveira/raylib-bunnymark
[510]: https://github.com/RafaelOliveira
[511]: https://github.com/henriquel1997/webcam_raylib
[512]: https://github.com/henriquel1997
[513]: https://github.com/yaram/match-three
[514]: https://github.com/yaram
[515]: https://github.com/erikerlandson/ray-odh-demo
[516]: https://github.com/neonmoe/metro
[517]: https://github.com/neonmoe
[518]: https://github.com/afreytes/RLSolarSystem
[519]: https://github.com/afreytes
[520]: https://github.com/arinal/WpfSolarSystem
[521]: https://github.com/Adobe-Android/raylib-demo
[522]: https://github.com/Adobe-Android
[523]: https://github.com/PHILLIPGATLIN/Caption
[524]: https://github.com/PHILLIPGATLIN
[525]: https://github.com/gihadmecha/raylib_examples_to_learn
[526]: https://github.com/gihadmecha
[527]: https://github.com/danimartin82/rayMaschine
[528]: https://github.com/JusticeShultz/RaylibPhysics
[529]: https://github.com/JusticeShultz
[530]: https://github.com/pintertamas/my-awesome-project
[531]: https://github.com/pintertamas
[532]: https://github.com/bruhmoment3124/raylib
[533]: https://github.com/bruhmoment3124
[534]: https://github.com/feihong/gamedev-experiments
[535]: https://github.com/feihong
[536]: https://github.com/creikey/raylib-particles
[537]: https://github.com/creikey
[538]: https://github.com/t0rre/Raylib-3d-Test
[539]: https://github.com/t0rre
[540]: https://github.com/JohnLins/GravitationalAcceleration
[541]: https://github.com/JohnLins
[542]: https://github.com/DoctorAkula/Altair8800
[543]: https://github.com/DoctorAkula
[544]: https://github.com/fullnitrous/rsim
[545]: https://github.com/fullnitrous
[546]: https://github.com/jessp/Pepper-s-Pi-Cone
[547]: https://github.com/jessp
[548]: https://github.com/Nachasic/vicarious-rs
[549]: https://github.com/Nachasic
[550]: https://github.com/buribalazs/raylib-rs-play_sound_multi
[551]: https://github.com/buribalazs
[552]: https://github.com/teh-cmc/rts
[553]: https://github.com/teh-cmc
[554]: https://github.com/jestarray/raylib_ffi_bug
[555]: https://github.com/jestarray
[630]: https://github.com/magnetrwn/raylib-bubbles
[631]: https://github.com/magnetrwn

### Templates

<!-- TODO refactor readability -->

| Name                  | Author          | Description                                 |
|-----------------------|-----------------|---------------------------------------------|
| [raylib_starter][556] | [tducasse][557] | Simple raylib template for Windows and Web targets. |
| [rbpi400raylib][558] | [daandruff][559] | Simple raylib template for Raspberry Pi 400. |
| [raylibtest][560] | [irskep][561] | raylib Nim bindings test example. |
| [ray-starter][562] | [jamiltron][563] | Skeleton of a raylib project with CMake. |
| [raylib-template][564] | [benweidig][565] | Linux template for raylib. |
| [raylib-cpp-starter][566] | [CapsCollective][567] | Portable and automated template for raylib projects with C++ bindings. |
| [simple_raylib_template][568] | [inque][569] | This is a simple raylib boilerplate that can be used as a starting point for raylib, It has also utility to build for Web! |
| [raylib-imgui-template][570] | [oswjk][68] | Basic raylib + Dear ImGui template. |
| [raygame][571] | [AIE-Seattle-Prog][572] | Sample C++ project setup with raylib for Visual Studio 2017. |
| [raygame][573] | [AIE-Seattle-Prog][572] | Sample C# project setup with raylib-cs for Visual Studio 2017. |
| [Dnkvw-Raylib-Minimal-Example][574] | [DaNiKhan-GbR][441] | Minimal example that demonstrates the usage of Dnkvw with raylib, Can be used as a project template. |
| [RaylibHotReloadTemplate][575] | [krzosa][576] | Template for hot reload code in raylib. |
| [c99-raylib-template][577] |  [WEREMSOFT][93] | Starting template to work with raylib, Uses make for build. |
| [c99-raylib-cimgui-template][578] |  [WEREMSOFT][93] | Simple template to integrate raylib with imgui on C99, Uses [cimgui][579] bindings. |
| [raylib-network-template][580] |  [WEREMSOFT][93] | Kinda serverless multiplayer template. It can be used to make a very basic multiplayer game. |
| [raylib-cmake-template][581] | [SasLuca][52] | Very minimal project template for raylib using CMake that works well in CLion & Visual Studio. |
| [rayfork-sokol-template][582] | [SasLuca][52] | Simple rayfork project template with sokol-app and CMake. |
| [go-raylib-template][583] | [RaniSputnik][584] | Starter template for building games with the raylib Golang bindings. |
| [raylib-starter-kit][585] | [Hidden-Pixel][586] | This repository is to raylib starter kit to help get up and running quickly after installing MSVC, clang or gcc, and emcc. |
| [rayskeleton][587] | [oswjk][68] | Skeleton project template for raylib. Uses CMake. |
| [RaylibStarterProjectXcode][588] | [braedenf][589] | Basic window implemented with raylib in XCode. |
| [raystart][590] | [jacmoe][389] | Quick CMake based project template for exploratory graphics programming using raylib. |
| [RaylibVSTemplate][591] | [JamieMair][592] | Template Visual Studio 2019 C++ project for the raylib library. |
| [raylib-boilerplate][593] | [Yrds][594] | out-of-box environment to develop raylib games. |
| [raylib_graphic_template][595] | [Qinbeans][596] | Template for future use and has working adjustable resolution. |
| [tempraylib][597] | [CodingCor][598] | Simple C++ template to use raylib in Linux and Windows. |
| [Raylib-Scons-boilerplate][599] | [MrOneTwo][467] | Boilerplate for raylib with Scons as build system. |
| [raylib-meson-template][600] | [gilzoide][304] | Minimal template project for C/C++ applications using raylib built using Meson. |
| [raylibMinimumVS][601] | [Ushio][129] | Simple C++ template for raylib for use with Visual Studio 2017. |
| [raylib_template][602] | [janderkkotlarski][603] | C++ Simple raylib template that should works when raylib is correctly installed. |
| [raylib-lsk][604] | [Lattay][605] | [Lattay][605]'s Starter Kit for raylib, small boiler plate for raylib projects. |
| [vscode-raylib-base][606] | [charlesmartinreed][607] | Setup used by GamesFromScratch when he made tutorials for raylib. |
| [RaylibCSharpStarter][608] | [AIESydProgYr12021][609] | raylib C# game starter kit. |
| [RaylibStarterCPP][610] | [LodisAIE][611] | raylib C++ game starter kit. |
| [Raylib-with-Flecs-Template][612] | [HeatXD][613] | Template for raylib with a custom flecs pipline for raylib. |
| [parsec_raylib_template][614] | [underscorenygren][615] | Starter project for the parsec and raylib integration article series, Use this as a base from which to create your own games. |
| [kotlin-native-raylib-starter][616] | [LeHaine][617] | Base projected configured to link, build, and run raylib with Kotlin Native. |
| [Raylib-C-starterProj][618] | [JustinKatic][619] | Basic startup setup for raylib with a clear Start and Update function. |
| [raylib-scaffold][620] | [waruqi][621] | Minimal raylib project template that uses XMake. |
| [RayTemplateC][622] | [GoldenbergDaniel][623] | Template for the raylib library in C. |
| [Raylib Screensaver][628] | [RicoP][629] | Template for windows 3D screensavers made in raylib. |

[556]: https://github.com/tducasse/raylib_starter
[557]: https://github.com/tducasse
[558]: https://github.com/daandruff/rbpi400raylib
[559]: https://github.com/daandruff
[560]: https://github.com/irskep/raylibtest
[561]: https://github.com/irskep
[562]: https://github.com/jamiltron/ray-starter
[563]: https://github.com/jamiltron
[564]: https://github.com/benweidig/raylib-template
[565]: https://github.com/benweidig
[566]: https://github.com/CapsCollective/raylib-cpp-starter
[567]: https://github.com/CapsCollective
[568]: https://gitlab.com/inque/simple_raylib_template
[569]: https://gitlab.com/inque
[570]: https://github.com/oswjk/raylib-imgui-template
[571]: https://github.com/AIE-Seattle-Prog/raygame
[572]: https://github.com/AIE-Seattle-Prog
[573]: https://github.com/AIE-Seattle-Prog/raygamecsharp
[574]: https://github.com/DaNiKhan-GbR/Dnkvw-Raylib-Minimal-Example
[575]: https://github.com/krzosa/RaylibHotReloadTemplate
[576]: https://github.com/krzosa
[577]: https://github.com/WEREMSOFT/c99-raylib-template
[578]: https://github.com/WEREMSOFT/c99-raylib-cimgui-template
[579]: https://github.com/cimgui/cimgui
[580]: https://github.com/WEREMSOFT/raylib-network-template
[581]: https://github.com/SasLuca/raylib-cmake-template
[582]: https://github.com/SasLuca/rayfork-sokol-template
[583]: https://github.com/RaniSputnik/go-raylib-template
[584]: https://github.com/RaniSputnik
[585]: https://github.com/Hidden-Pixel/raylib-starter-kit
[586]: https://github.com/Hidden-Pixel
[587]: https://github.com/oswjk/rayskeleton
[588]: https://github.com/braedenf/RaylibStarterProjectXcode
[589]: https://github.com/braedenf
[590]: https://github.com/jacmoe/raystart
[591]: https://github.com/JamieMair/RaylibVSTemplate
[592]: https://github.com/JamieMair
[593]: https://github.com/Yrds/raylib-boilerplate
[594]: https://github.com/Yrds
[595]: https://github.com/Qinbeans/raylib_graphic_template
[596]: https://github.com/Qinbeans
[597]: https://github.com/CodingCor/tempraylib
[598]: https://github.com/CodingCor
[599]: https://github.com/MrOneTwo/Raylib-Scons-boilerplate
[600]: https://github.com/gilzoide/raylib-meson-template
[601]: https://github.com/Ushio/raylibMinimumVS
[602]: https://github.com/janderkkotlarski/raylib_template
[603]: https://github.com/janderkkotlarski
[604]: https://github.com/Lattay/raylib-lsk
[605]: https://github.com/Lattay
[606]: https://github.com/charlesmartinreed/vscode-raylib-base
[607]: https://github.com/charlesmartinreed
[608]: https://github.com/AIESydProgYr12021/RaylibCSharpStarter
[609]: https://github.com/AIESydProgYr12021
[610]: https://github.com/LodisAIE/RaylibStarterCPP
[611]: https://github.com/LodisAIE
[612]: https://github.com/HeatXD/Raylib-with-Flecs-Template
[613]: https://github.com/HeatXD
[614]: https://github.com/underscorenygren/parsec_raylib_template
[615]: https://github.com/underscorenygren
[616]: https://github.com/LeHaine/kotlin-native-raylib-starter
[617]: https://github.com/LeHaine
[618]: https://github.com/JustinKatic/Raylib-C-starterProj
[619]: https://github.com/JustinKatic
[620]: https://github.com/waruqi/raylib-scaffold
[621]: https://github.com/waruqi
[622]: https://github.com/GoldenbergDaniel/RayTemplateC
[623]: https://github.com/GoldenbergDaniel
[628]: https://github.com/RicoP/raylib-screensaver
[629]: https://github.com/RicoP/

### Articles

- [Game Porting Adventures (by raysan5)](https://gist.github.com/raysan5/fdefbe1b8184e0fa80676156bb86964f)
- [Joint Limits with raylib (by Daniel Holden)](https://theorangeduck.com/page/joint-limits)
- [How to add hot reload when using raylib?](https://www.developing-stuff.com/how-to-add-hot-reload-when-using-raylib)
- [How to add hot reload to your raylib project (in C) ?](https://medium.com/@TheElkantor/how-to-add-hot-reload-to-your-raylib-proj-in-c-698caa33eb74)
- [raylib Game Tutorial : Space Invaders using VSCode](https://monsterbraininc.com/2018/12/raylib-game-tutorial-space-invaders-using-vscode)
- [Easy Blitzmax Streaming realtime audio with raylib](https://www.syntaxbomb.com/index.php?topic=5807.0)
- [Advanced Matrix transforms with raylib](https://bedroomcoders.co.uk/advanced-matrix-transforms-with-raylib)
- [Drawing textured 2D polygons with rlgl (raylib)](https://bedroomcoders.co.uk/drawing-textured-2d-polygons-with-rlgl-raylib)
- [What About Making Games Without Engines?](https://medium.com/@thelukaswils/what-about-making-games-without-engines-188c65f16672)
- [deepsource.io - Spotlight: Ramon Santamaria](https://deepsource.io/spotlight/ramon-santamaria)
- [Simple PHP Game in PHP using raylib: Snake (with source code)](https://thephp.website/en/issue/games-with-php)
- [Compiling raylib programs with SCons](http://ciesie.com/post/building_raylib_with_scons)
- [raylib game coding library for C](http://bedroomcoders.co.uk/raylib-game-coding-library-for-c)
- [raylib novices guide for creating a simple game](http://bedroomcoders.co.uk/raylib-a-novices-guide-for-creating-a-simple-game)
- [Creating a simple game (part 2)](http://bedroomcoders.co.uk/creating-a-simple-game-part-2)
- [Creating a simple game (part 3)](http://bedroomcoders.co.uk/creating-a-simple-game-part-3)
- [Creating a simple game (part 4)](http://bedroomcoders.co.uk/creating-a-simple-game-part-4)
- [Creating a simple game (part 5) finishing up](http://bedroomcoders.co.uk/creating-a-simple-game-part-5-finishing-up)
- [Complete Template for Raylib](http://bedroomcoders.co.uk/complete-template-for-raylib)
- [3d Physics with raylib and ODE](http://bedroomcoders.co.uk/3d-physics-with-libray-and-ode)
- [raylib adding a static terrain (ODE)](http://bedroomcoders.co.uk/raylib-adding-a-static-terrain-ode)
- [Looking again at compiling a Windows raylib app](http://bedroomcoders.co.uk/looking-again-at-compiling-a-windows-raylib-app)
- [Creating a 64 bit executable with raylib on windows](http://bedroomcoders.co.uk/creating-a-64-bit-executable-with-raylib-on-windows)
- [Aiming at moving targets…](http://bedroomcoders.co.uk/aiming-at-moving-targets)
- [Aiming at 3d moving targets](http://bedroomcoders.co.uk/aiming-at-3d-moving-targets)
- [Painting on a 3d Mesh with raylib](http://bedroomcoders.co.uk/painting-on-a-3d-mesh-with-raylib)
- [Raylib, projecting 3D onto 2D handy for debugging](http://bedroomcoders.co.uk/raylib-projecting-3d-onto-2d-handy-for-debugging)
- [Raylib and Chipmunk2d](http://bedroomcoders.co.uk/raylib-and-chipmunk2d)
- [PhysFS and raylib](http://bedroomcoders.co.uk/physfs-and-raylib)
- [Using libmpeg2 with raylib](http://bedroomcoders.co.uk/using-libmpeg2-with-raylib)
- [Aligning a model with a terrain (raylib)](http://bedroomcoders.co.uk/aligning-a-model-with-a-terrain-raylib)
- [A simple maze creation algorithm (C99 and raylib)](http://bedroomcoders.co.uk/a-simple-maze-creation-algorithm-c99-and-raylib)
- [Using RayLib with an ECS](http://bedroomcoders.co.uk/using-raylib-with-an-ecs)
- [Animating sky with raylib](http://bedroomcoders.co.uk/animating-sky-with-raylib)
- [raylib Fog](http://bedroomcoders.co.uk/raylib-fog)
- [Sprite Sheets with rayLib](http://bedroomcoders.co.uk/sprite-sheets-with-raylib)
- [Shaders with raylib](http://bedroomcoders.co.uk/shaders-with-raylib)
- [Lighting with raylib](http://bedroomcoders.co.uk/lighting-with-raylib)
- [2D Spotlight shader with rayLib](http://bedroomcoders.co.uk/2d-spotlight-shader-with-raylib)
- [Implementing a 3d GUI with raylib](http://bedroomcoders.co.uk/implementing-a-3d-gui-with-raylib)
- [Creating Raspberry Pi applications with raylib and Ruby (Part 1)](https://medium.com/@avik.das/creating-raspberry-pi-applications-with-raylib-and-ruby-fba3d35b2877)
- [Creating Raspberry Pi applications with raylib and Ruby (Part 2)](https://medium.com/@avik.das/creating-raspberry-pi-applications-with-raylib-and-ruby-part-ii-edc47680157b)
- [Ubuntu 18.04 için raylib kurulumu (Turkish)](https://medium.com/@msoygen/ubuntu-18-04-raylib-kurulumu-8ff9c4274b91)
- [raylib: 6 years of fun](https://gist.github.com/raysan5/04a2daf02aa2a6e79010331f77bf983f)
- [rGuiIcons Making Of Diary](https://gist.github.com/raysan5/fe769f77b43b6c612600166498ce3640)

### Tutorials

- [Learn X in Y minutes, Where X=raylib](https://learnxinyminutes.com/docs/raylib)
- [Raylib 2.0 Tutorial Series by SkyVaultGames](https://www.youtube.com/playlist?list=PL5gRzHmN4Dg3ubcneVFkHPm0mTGYTUHDn)
- [List of raylib tutorials by HE360](https://www.youtube.com/playlist?list=PLZBVMzyySalVhcWEJcnG-HK8OXQli_tcV)
- [How to create a game with 'raylib' in C](https://www.youtube.com/watch?v=kBky9_X8j3Y)
- [How to get started with Raylib 3.0 in C# - Tutorial](https://www.youtube.com/watch?v=SoXD5y24WQw)
- [Let's learn D programming Game Dev!](https://www.youtube.com/playlist?list=PLgM-lc_kSqFQPF0UXgmFZpZalqcrSofe-)
- [Coding a Breakout Arcade clone in C with Raylib](https://www.youtube.com/watch?v=UKecFbu61Oc)
- [Graphics programming challenges by raysan5 (GitHub repository)](https://github.com/raysan5/challenges)
- [Raylib Game Tutorial : Space Invaders using VSCode](https://monsterbraininc.com/2018/12/raylib-game-tutorial-space-invaders-using-vscode)
- [raylib -- A C++ Game Library That's Perfect For Beginners](https://www.youtube.com/watch?v=xGPF3Gn-yhA)
- [How to build & set up raylib for Visual studio](https://www.youtube.com/watch?v=mfj0JG2LdVM)
- [Create Videos Games in PHP (With RayLib)](https://www.youtube.com/watch?v=q1X_6TYd030)
- [Compiler Raylib sur Windows (French)](https://www.youtube.com/watch?v=XEpmMBM01Zg)
- [Raylib setup on Codeblocks](https://www.youtube.com/watch?v=a2IUxJFr8sg)
- [Tile maps en Raylib con Tileson (Spanish)](https://www.youtube.com/watch?v=Gq9sTaeHtj4)
- [윈도우 10에서 Visual Studio Code로 raylib 개발 환경 구축하기 (Korean)](https://jdeokkim.github.io/setting-up-raylib-with-vscode-on-windows)
- [raylib에서 한글 글꼴 사용하기 (Korean)](https://jdeokkim.github.io/using-korean-fonts-with-raylib)

### Videos

- [iqm animation raylib 4.0 example - Tutorial](https://www.youtube.com/watch?v=_EurjoraotA)
- [RayLib Review / Open source free game library / Game Engine / Delphi, Pascal, Lazarus, C, C++, C#](https://www.youtube.com/watch?v=Z6Eg9UfC_6U&t=616s)
- [RayLib / Обзор игровой библиотеки / Pascal, Delphi, Lazarus, C++, C#, Java, JavaScript, Python, Perl(Russian)](https://www.youtube.com/watch?v=GUDzyXlmpVk&t=74s)
- [Making a Game With Trash](https://www.youtube.com/watch?v=sKlcCplUODw)
- [Best C++ Game Wins $1000 - Game Making Challenge](https://www.youtube.com/watch?v=_yyKYl1LAHM)
- [9ª QIDV (8/11) : Ramón Santamaría presenta su RayLib (Spanish)](https://www.youtube.com/watch?v=LKdqM8Wv6qk)
- [QIDV 12 (03) - Ramón Santamaría nos presenta la nueva versión de su Raylib (Spanish)](https://www.youtube.com/watch?v=tKq9mpEBQFg)
- [raylib events automation](https://www.youtube.com/watch?v=3dZenkpmRzM)
- [path following raylib and ODE vehicles](https://www.youtube.com/watch?v=p7kU5SmBZ3M)
- [ODE Vehicle Raylib](https://www.youtube.com/watch?v=LjsKEO105Dw)
- [Raylib 3.7 - raylib4Vita](https://www.youtube.com/watch?v=ISPID_2XBDs)
- [C64 demo raylib mock-up](https://www.youtube.com/watch?v=SegPe1kgILA)
- [Making a game WITHOUT a GAME ENGINE](https://www.youtube.com/watch?v=MPMELcP8-RM)
- [Learning C++ and making a GAME WITHOUT A GAME ENGINE](https://www.youtube.com/watch?v=kc4AhROG05g)
- [Bad Apple!! but its 7600 ReCT and Raylib Logos](https://www.youtube.com/watch?v=8LnQ1A0rJ9s)
- [Why I'm Glad I Didn't Use a Game Engine](https://www.youtube.com/watch?v=nBaCRp9UzDw)
- [raylib C - Simple sand game](https://www.youtube.com/watch?v=o8QOWVHaMsg)
- [Using Android's sensor with Raylib](https://www.youtube.com/watch?v=2woi4NR7xPA)
- [Raylib SpriteEngine](https://www.youtube.com/watch?v=mMPtnHUiZbM)
- [C++ Sorting Algorithms Visualized (Raylib Library)](https://www.youtube.com/watch?v=E2Brnev0Olc)
- [Test of synchronize video and audio with OpenGL (powered by raylib)](https://www.youtube.com/watch?v=KGcC-d19-lg)
- [Traduzindo e estudando exemplos do Raylib](https://www.youtube.com/watch?v=3KKLh3W0III) (Portuguese)
- [Rayblade 2d Game Devlog using Raylib-C](https://www.youtube.com/watch?v=AmWc9qoD4UA)
- [2D Raylib Experiments Livestream (Part 1) - Making the Player Bleed](https://www.youtube.com/watch?v=N2ytx3Awt8c)
- [2D Raylib Experiments Livestream (Part 2) - Slime Time](https://www.youtube.com/watch?v=-oup057X4xw)
- [Raylib Raspberry Pi Sound Demo](https://www.youtube.com/watch?v=_vQ7PDqziO0)
- [Odin-Raylib Game Programming #000: Windows Environment Setup](https://www.youtube.com/watch?v=CDlYQtxyhPs)
- [Raylib works with Neatbeans and mac os x](https://www.youtube.com/watch?v=GFFgt1zxeck)
- [EPIC raylib c++ rpg game dev](https://www.youtube.com/watch?v=VqQDkz0t7lE)
- [Quick sort in raylib. Oh yeah.](https://www.youtube.com/watch?v=psede2nHvRE)
- [Randomness RNG vs Perlin Noise with Raylib 3.0](https://www.youtube.com/watch?v=6NLolZ-aiVA)
- [raylib - 3rd anniversary](https://www.youtube.com/watch?v=o8T9oNfsCOs)
- [Raylib oLd SkOoL 2](https://www.youtube.com/watch?v=M2WYWYQNjYg)
- [Pangea Demo - Editing Heightmaps With Raylib](https://www.youtube.com/watch?v=fWWUG9VMoQw)
- [raylib on Mobian PinePhone](https://www.youtube.com/watch?v=Vi4TXnrnExo)
- [Coding a Synthesizer in C (episode #1)](https://www.youtube.com/watch?v=p1VQuMziTek)
- [Coding a Synthesizer in C (episode #2)](https://www.youtube.com/watch?v=jZSnH33Vkh4)
- [Coding a Synthesizer in C (episode #3)](https://www.youtube.com/watch?v=WXoyF5jYujE)
- [Coding a Synthesizer in C (episode #4)](https://www.youtube.com/watch?v=SmKYWmQQmsk)
- [Coding a Synthesizer in C (episode #5)](https://www.youtube.com/watch?v=fqUbYIhLTqw)
- [How To Use Raylib With C++ And VSCode](https://www.youtube.com/watch?v=u6LXRF-iMg8)
- [Digital Crafters #2 - Ramon Santamaria](https://www.youtube.com/watch?v=wnbJpdjAHg8)
- [Interview with @imakefoss curator and Ramon Santamaria about raylib](https://www.youtube.com/watch?v=NM1gMvHwDwA)
- [Official raylib 2.5 presentation](https://www.youtube.com/watch?v=78aa2wuiGmI)
- [raylib 4.0 Released -- The Easiest C/C++ Game Library Just Got Even Better](https://www.youtube.com/watch?v=H_Oe82SqQ8Y)
- [raylib 3.7 Released](https://www.youtube.com/watch?v=c8hUF75f0kk)
- [RayLib 3.5 Released -- C/C++ GameDev Easy Mode](https://www.youtube.com/watch?v=RZJ-Z--6uxY)
- [Raylib 3.0 Released -- The Best Way to Learn C or C++ Game Development*](https://www.youtube.com/watch?v=xx9ntuvA1t0)
- [Raylib 2.0 Released -- C/C++ Game Framework Perfect For Beginners](https://www.youtube.com/watch?v=QwLHHasIO6k)
- [Raylib 1.8 Released -- Easiest C Game Framework I've Ever Found](https://www.youtube.com/watch?v=FDbIQZBar7g)
- [RayLib Receives An Epic MegaGrant!](https://www.youtube.com/watch?v=jZWwisQn76A)
- [Raylib Terrain Erosion Demo](https://www.youtube.com/watch?v=jYCSkodrg6w)
- [Checking out raylib](https://www.youtube.com/watch?v=fHojJ9Nxb0E)
- [Checking out Raylib — Part 2 — 3D Game Development](https://www.youtube.com/watch?v=QqravLVpoI8)
- [raylib -- A C++ Game Library That's Perfect For Beginners](https://www.youtube.com/watch?v=xGPF3Gn-yhA)
- [C++ | Implementing Boid: 0 Visualization | Raylib 3.0](https://www.youtube.com/watch?v=GM3TM5Hi16w)
- [How to compile Raylib from scratch and set up your first projects (Windows / C ) in 15 minutes](https://www.youtube.com/watch?v=HPDLTQ4J_zQ)
- [Making a Game for FIVE Different Consoles - Ludum Dare 46](https://www.youtube.com/watch?v=mE6_A1hRcQk)
- [Totally Not Failing at Making a Game in Raylib and C During AP Exam Week.. Retro Game Jam 2020](https://www.youtube.com/watch?v=aK_m-1wtr3A)
- [Raymarched Mandelbulb with Raylib](https://www.youtube.com/watch?v=dxOUef36bK4)
- [Particle System using RayLib | C++ GameDev | C++ Particle System](https://www.youtube.com/watch?v=j5dVx0LTtAs)
- [CRT scan line retro shader with RayLib](https://www.youtube.com/watch?v=Custpsdpgj4)
- [Using RayLib on a 32x32 "screen"](https://www.youtube.com/watch?v=DxbikNW6zN4)
- [LIVE : Raylib, une lib C / C++ idéale pour débuter ?](https://www.youtube.com/watch?v=PZi-Z9XyJo8) (French)
- [C++ | BubbleSort with RayLib 2.6 Speed Coding](https://www.youtube.com/watch?v=T-pNv6BewC8)
- [FPS game written in C](https://www.youtube.com/watch?v=xE1MG1-Yh6s)
- [Raylib Voronoi Map Generation](https://www.youtube.com/watch?v=HTZFXYpu-G0)
- [raylib and open dynamics engine](https://www.youtube.com/watch?v=sjsPUW12WYE)
- [Distributed computing of the Mandelbrot Set using Go, gRPC and Raylib](https://www.youtube.com/watch?v=pDbuClfEAIY)
- [raylib on 32x32 LED](https://www.youtube.com/watch?v=u1BzNAJORN8)
- [Procedural Island Gen and A* Pathfinding Demo](https://www.youtube.com/watch?v=vpzFoRA6Y3Q)
- [Install RayLib in LazarusIDE](https://www.youtube.com/watch?v=lAFWOgDahtk)
- [Raylib c'est bien !](https://www.youtube.com/watch?v=aaIBSuymo0Y) (French)
- [QIDV12 (03) - Ramón Santamaría nos presenta la nueva versión de su Raylib](https://www.youtube.com/watch?v=tKq9mpEBQFg) (Spanish)
- [Borak Buat Game - Belajar Raylib](https://www.youtube.com/watch?v=tMPBdjP0dp8) (Malay)
- [Belajar Raylib Part 2 - 3D Camera dan Simple Collision](https://www.youtube.com/watch?v=rMNVXFpAkg8) (Malay)
- [How to install raylib on a chromebook (OpenGl 2.1)](https://www.youtube.com/watch?v=R0jsXG4xahM)
- [Compiler Raylib sur Windows](https://www.youtube.com/watch?v=XEpmMBM01Zg) (French)
- [RayLib-PHP DevLog Fonts & Tiled Support](https://www.youtube.com/watch?v=JYGtt0sfbzw)
- [C | Implementing Epicycloid with Raylib 3.0 Speed Coding](https://www.youtube.com/watch?v=wZDEkIwkyFk)
- [C | Implementing Fractal Tree with Raylib 3.0 Speed Coding](https://www.youtube.com/watch?v=WdPnUAJW3YM)
- [Coding a Breakout Arcade clone in C with Raylib](https://www.youtube.com/watch?v=UKecFbu61Oc)
- [A brief introduction to Raylib](https://www.youtube.com/watch?v=J4eLE9YYQp0)
- [How to get started with Raylib 3.0 in C# - Tutorial](https://www.youtube.com/watch?v=SoXD5y24WQw)
- [Raylib - adventure in shaders - ep00](https://www.youtube.com/watch?v=siosc2B1bA4)
- [Raylib - adventure in shaders - ep01](https://www.youtube.com/watch?v=8205iyicv5k)
- [Raylib - Fixing the "Skipping Incompatible ../src\libraylib.a When Searching For -lraylib" Error](https://www.youtube.com/watch?v=rgV9AoVdFlA)

### Promo Images

- [Overview](https://github.com/raysan5/raylib)

![raylib overview](promos/banner13.png)

- [Overview (Wide)](https://github.com/raysan5/raylib)

![raylib overview (wide)](promos/banner7.png)

- [Last 6 years of raylib](https://twitter.com/raysan5/status/1174631716734013440)

![last 6 years of raylib](promos/banner0.png)

- [Game development is about to explode!](https://twitter.com/raysan5/status/1083782102653587456)

![raylib gamedev is about to explode](promos/banner10.png)

- [raylib 2.5 architecture](https://twitter.com/raysan5/status/1141349399316115458)

![raylib 2.5 architecture](promos/banner45.png)

- [Current raylib architecture](https://github.com/raysan5/raylib/wiki/raylib-architecture)

![raylib architecture](promos/banner1.png)

- Difference between raylib 3.5 architecture and raylib 3.7 architecture

![Difference between raylib 3.5 architecture and raylib 3.7 architecture](promos/banner57.png)

- [raylib 4.0 architecture](https://twitter.com/hmans/status/1472571560544411653)

![raylib 4.0 architecture](promos/banner61.png)

- [raylib 5th anniversary](https://twitter.com/raysan5/status/1064139050704089089)

![raylib 5th anniversary](promos/banner8.jpg)

- [raylib 6th anniversary](https://twitter.com/raysan5/status/1190963229171814401)

![raylib 6th anniversary](promos/banner2.png)

- [6 years of fun](https://gist.github.com/raysan5/04a2daf02aa2a6e79010331f77bf983f)

![raylib 6 years of fun](promos/banner4.png)

- [raylib 1.5](https://twitter.com/raysan5/status/755364768052019200)

![raylib 1.5 is ready](promos/banner25.jpg)

- [raylib 1.7](https://twitter.com/raysan5/status/865513349450129408)

![raylib 1.7](promos/banner31.jpg)

- [raylib 1.8](https://twitter.com/raysan5/status/922373390039703552)

![raylib 1.8 is out!](promos/banner26.jpg)

- [raylib 2.0 #1](https://twitter.com/raysan5/status/1020768415802380289)

![raylib 2.0 #1](promos/banner9.png)

- [raylib 2.0 #2](https://twitter.com/raysan5/status/1015222845494956033)

![raylib 2.0 #2](promos/banner29.jpg)

- [raylib 2.5](https://twitter.com/raysan5/status/1134429674472452097)

![raylib 2.5](promos/banner33.png)

- [raylib 3.0](https://twitter.com/raysan5/status/1245314287037530112)

![raylib 3.0](promos/banner6.png)

- [raylib 3.5](https://twitter.com/raysan5/status/1319036064804331521)

![raylib 3.5](promos/banner5.png)

- [raylib 3.7](https://twitter.com/raysan5/status/1386728711131734017)

![raylib 3.7](promos/banner58.png)

- [raylib parser](https://twitter.com/raysan5/status/1398948422913343488)

![raylib parser](promos/raylib_parser_info.png)

- [raylib 4.0](https://twitter.com/raysan5/status/1456359846920458240)

![raylib 4.0](promos/banner60.png)

- [raylib 5k gamejam #1](https://twitter.com/raysan5/status/1481322244982906880)

![raylib 5k gamejam](promos/banner62.jpg)

- [raylib 5k gamejam #2](https://itch.io/jam/raylib-5k-gamejam)

![raylib 5k gamejam](promos/banner63.png)

- [raylib 5k gamejam - 1st Prize](https://itch.io/jam/raylib-5k-gamejam)

![raylib 5k gamejam - 1st Prize](promos/banner65.png)

- [raylib 5k gamejam - 2nd Prize](https://itch.io/jam/raylib-5k-gamejam)

![raylib 5k gamejam - 2nd Prize](promos/banner66.png)

- [raylib 5k gamejam - 3rd Prize](https://itch.io/jam/raylib-5k-gamejam)

![raylib 5k gamejam - 3rd Prize](promos/banner67.png)

- [raylib - Happy New Year!](https://twitter.com/raysan5/status/1477074126884020225)

![raylib - Happy New Year!](promos/banner67.jpg)

- [raylib receives an Epic MegaGrant](https://twitter.com/raysan5/status/1291690021221736450)

![raylib received epic megagrant](promos/banner3.png)

- [raygui](https://github.com/raysan5/raygui)

![raygui](promos/banner14.png)

- [rGuiIcons](https://raylibtech.itch.io/rguiicons)

![rGuiIcons](promos/banner16.png)

- [rfxgen](https://github.com/raysan5/rfxgen)

![rfxgen](promos/banner15.png)

- [raylib technologies's tools Linux support](https://twitter.com/raylibtech/status/1180878350782533632)

![raylib technologies's tools Linux support](promos/banner12.png)

- [raylib custom build flags](https://twitter.com/raysan5/status/1298956174071664640)

![raylib build flags](promos/banner11.png)

- [raylib on Handmade Seattle](https://twitter.com/raysan5/status/1193866190126551041)

![raylib on handmade seattle](promos/banner18.png)

- [raylib 200 contributors](https://twitter.com/raysan5/status/1375789665219977217)

![raylib contributors](promos/banner19.png)

- [raylib API usage analysis](https://gist.github.com/raysan5/7c0c9fff1b6c19af24bb4a51b7383f1e)

![raylib API usage analysis](promos/banner59.png)

- [raylib in numbers](https://gist.github.com/raysan5/1e34df90dfbcef3c55b19d37d2d5ab2a)

![raylib in numbers](promos/banner20.png)

- [raylib on Wikipedia](https://twitter.com/raysan5/status/1285157701589360640)

![raylib on Wikipedia!](promos/banner27.png)

- [raylib and WebAssembly](https://twitter.com/raysan5/status/1226837835770142720)

![raylib and WebAssembly!](promos/banner28.jpg)

- [raylib FreeBSD support](https://twitter.com/raysan5/status/924913149094060032)

![raylib supports FreeBSD!](promos/banner30.jpg)

- [raylib and Global Game Jam 2018](https://twitter.com/raysan5/status/956681310239641602)

![raylib on GGJ2018!](promos/banner40.jpg)

- [raylib and Global Game Jam 2019](https://twitter.com/raysan5/status/1087728261608759299)

![raylib on GGJ2019!](promos/banner36.jpg)

- [raylib and Global Game Jam 2020](https://twitter.com/raysan5/status/1222869512984371200)

![raylib on GGJ2020!](promos/banner34.jpg)

- [raylib is simple and easy-to-use!](https://twitter.com/raysan5/status/1324789207844458496)

![raylib is simple and easy-to-use](promos/banner35.png)

- [raylib standalone modules](https://twitter.com/raysan5/status/1141354483391303681)

![raylib standalone modules](promos/banner38.png)

- [raylib social networks](https://twitter.com/raysan5/status/1141352450789711872)

![raylib social networks](promos/banner39.png)

- [raylib Discord server](https://twitter.com/raysan5/status/1019992500868657152)

![raylib discord server](promos/banner37.jpg)

- [raylib on NiceOneBarcelona](https://twitter.com/raysan5/status/1198945957293043713)

![raylib on N1B](promos/banner41.png)

- [raylib technologies's CLI study](https://twitter.com/raylibtech/status/1043097789843087361)

![raylib technologies - command line study](promos/banner42.jpg)

- [rPBR release!](https://twitter.com/elfisac/status/856882503948398592)

![rPBR released!](promos/banner43.jpg)

- [raylib supported platforms #1](https://twitter.com/raysan5/status/943880148922912768)

![raylib platforms support #1](promos/banner44.jpg)

- [raylib supported platforms #2](https://twitter.com/raysan5/status/1141350297308147721)

![raylib platforms support #2](promos/banner46.png)

- [raylib got over 30 bindings!](https://twitter.com/raysan5/status/1141350977695559681)

![raylib 30 bindings!](promos/banner47.png)

- [raylib got over 40 bindings!](https://twitter.com/raysan5/status/1162759633532063744)

![raylib 40 bindings!](promos/banner49.png)

- [Choose your flavor #1](https://twitter.com/raysan5/status/825652171425378304)

![raylib - choose your flavor #1](promos/banner51.jpg)

- [Choose your flavor #2](https://twitter.com/raysan5/status/1050346893388210178)

![raylib - choose your flavor #2](promos/banner50.jpg)

- [raylib technologies tools](https://twitter.com/raysan5/status/1141355911115681792)

![raylib technologies tools](promos/banner48.png)

- [raylib GitHub Actions build table](https://twitter.com/raysan5/status/1296148718488518656)

![raylib GitHub Actions build table](promos/banner52.jpg)

- [raylib modules](https://twitter.com/raysan5/status/840901794050002944)

![raylib modules](promos/banner53.png)

- [raylib's Google Open Source Peer Bonus](https://twitter.com/raysan5/status/1141348566167896065)

![raylib - Google Open Source Peer Bonus](promos/banner54.png)

- [Let's talk (raylib technologies)](https://twitter.com/raylibtech/status/1029061605634531329)

![raylib technologies - let's talk!](promos/banner21.jpg)

- [Working hard on the best tools!](https://twitter.com/raysan5/status/1052639309508038656)

![raylib - working hard on the best tools!](promos/banner17.jpg)

- [raylib coding examples](https://twitter.com/raysan5/status/1141353212320059392)

![raylib - +95 coding examples!](promos/banner55.png)

### Logos

[![raysan5/raylib](logos/raylib.png)](https://github.com/raysan5/raylib "raysan5/raylib")
[![SasLuca/rayfork](logos/rayfork.png)](https://github.com/SasLuca/rayfork "SasLuca/rayfork")
[![RobLoach/raylib-cpp](logos/raylib-cpp.png)](https://github.com/robloach/raylib-cpp "RobLoach/raylib-cpp")
[![ChrisDill/Raylib-cs](logos/raylib-cs.png)](https://github.com/ChrisDill/Raylib-cs "ChrisDill/Raylib-cs")
[![gen2brain/raylib-go](logos/raylib-go.png)](https://github.com/gen2brain/raylib-go "gen2brain/raylib-go")
[![Lachee/raylib-goplus](logos/raylib-go-plus.png)](https://github.com/Lachee/raylib-goplus "Lachee/raylib-goplus")
[![deltaphc/raylib-rs](logos/raylib-rust.png)](https://github.com/deltaphc/raylib-rs "deltaphc/raylib-rs")
[![raysan5/raylib-lua](logos/raylib-lua.png)](https://github.com/raysan5/raylib-lua "raysan5/raylib-lua")
[![RobLoach/raylib-lua-sol](logos/raylib-lua-sol.png)](https://github.com/RobLoach/raylib-lua-sol "RobLoach/raylib-lua-sol")
[![TSnake41/raylib-lua](logos/tsnake41-raylib-lua.png)](https://github.com/TSnake41/raylib-lua "TSnake41/raylib-lua")
[![HDPLocust/raylib-luamore](logos/raylib-luamore.png)](https://github.com/HDPLocust/raylib-luamore "HDPLocust/raylib-luamore")
[![Andre-LA/raylib-nelua](logos/raylib-nelua.png)](https://github.com/Andre-LA/raylib-nelua "Andre-LA/raylib-nelua")
[![AregevDev/raylib-cr](logos/raylib-cr.png)](https://github.com/AregevDev/raylib-cr "AregevDev/raylib-cr")
[![drezgames/raylib-pascal](logos/raylib-pascal.png)](https://github.com/drezgames/raylib-pascal "drezgames/raylib-pascal")
[![GuvaCode/Ray4Laz](logos/ray4laz.png)](https://github.com/GuvaCode/Ray4Laz "GuvaCode/Ray4Laz")
[![overdev/raylib-py](logos/raylib-py.png)](https://github.com/overdev/raylib-py "overdev/raylib-py")
[![RobLoach/node-raylib](logos/node-raylib.png)](https://github.com/RobLoach/node-raylib "RobLoach/node-raylib")
[![RobLoach/raylib-chaiscript](logos/raylib-chaiscript.png)](https://github.com/RobLoach/raylib-chaiscript "RobLoach/raylib-chaiscript")
[![ArnautDaniel/raylib-factor](logos/raylib-factor.png)](https://github.com/ArnautDaniel/raylib-factor "ArnautDaniel/raylib-factor")
[![ArnautDaniel/gforth-raylib](logos/gforth-raylib.png)](https://github.com/ArnautDaniel/gforth-raylib "ArnautDaniel/gforth-raylib")
[![TSnake41/raylib-wren](logos/raylib-wren.png)](https://github.com/TSnake41/raylib-wren "TSnake41/raylib-wren")
[![Not-Nik/raylib-zig](logos/raylib-zig.png)](https://github.com/Not-Nik/raylib-zig "Not-Nik/raylib-zig")
[![bmx-ng/ray.mod](logos/raylib-blitzmax.png)](https://github.com/bmx-ng/ray.mod "bmx-ng/ray.mod")
[![tjammer/raylib-ocaml](logos/raylib-ocaml.png)](https://github.com/tjammer/raylib-ocaml "tjammer/raylib-ocaml")
[![D-a-n-i-l-o/raylib-purebasic](logos/raylib-purebasic.png)](https://github.com/D-a-n-i-l-o/raylib-purebasic "D-a-n-i-l-o/raylib-purebasic")
[![M0n7y5/raylib-beef](logos/raylib-beef.png)](https://github.com/M0n7y5/raylib-beef "M0n7y5/raylib-beef")
[![RedCubeDev-ByteSpace/Relib](logos/relib.png)](https://github.com/RedCubeDev-ByteSpace/Relib "RedCubeDev-ByteSpace/Relib")
[![CreedVI/Raylib-J](logos/raylib-j.png)](https://github.com/CreedVI/Raylib-J "CreedVI/Raylib-J")
[![victorfisac/Physac](logos/physac.png)](https://github.com/victorfisac/Physac "victorfisac/Physac")
[![raysan5/raygui](logos/raygui.png)](https://github.com/raysan5/raygui "raysan5/raygui")
[![raysan5/rpng](logos/rpng.png)](https://github.com/raysan5/rpng "raysan5/rpng")
[![raysan5/rres](logos/rres.png)](https://github.com/raysan5/rres "raysan5/rres")
[![raysan5/rfxgen](logos/rfxgen.png)](https://github.com/raysan5/rfxgen "raysan5/rfxgen")
[![victorfisac/FNode](logos/fnode.png)](https://github.com/victorfisac/FNode "victorfisac/FNode")
[![SliverLIVE/Raylib-for-GLBasic](logos/raylib-glbasic.png)](https://github.com/SliverLIVE/Raylib-for-GLBasic "SliverLIVE/Raylib-for-GLBasic")
[![ForeignSasquatch/hxRaylib](logos/hxraylib.png)](https://github.com/ForeignSasquatch/hxRaylib "ForeignSasquatch/hxRaylib")

### Stickers

- [Mobile](https://twitter.com/raysan5/status/1233460424114364418)

![raylib mobile sticker](promos/banner56.jpg)

- [Bag](https://twitter.com/raysan5/status/1121527359801262094)

![raylib bag sticker](promos/banner24.jpg)

### Resources and Links

- [What raylib uses?](https://github.com/raysan5/raylib/wiki/raylib-dependencies)
- [raylib Official Cheatsheet](https://www.raylib.com/cheatsheet/cheatsheet.html)
- [raylib Official examples](https://www.raylib.com/examples.html)
- [raylib Official Wiki](https://github.com/raysan5/raylib/wiki)
- [raylib on Wikipedia](https://en.wikipedia.org/wiki/Raylib)
- [raylib website](https://raylib.com)
- [raylib YouTube channel](https://www.youtube.com/channel/UC8WIBkhYb5sBNqXO1mZ7WSQ)
- [raylib Discord channel](https://discord.gg/VkzNHUE)
- [raylib on Reddit](https://www.reddit.com/r/raylib)
- [raylib on Handmade](https://raylib.handmade.network)
- [raylib page on itch.io](https://raysan5.itch.io/raylib)

> Can't find your awesome stuff or you want to improve the list? Make issue or pull request for that!

