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

| Name         | Author             | Description                                    |
|--------------|--------------------|------------------------------------------------|
| [sort.c][1]  | [ohmree][2]        | C Sorting example that uses raylib.            |
| [bleed.c][3] | [satinxs][4]       | Bleed bug when drawing rectangles with raylib. |
| [agui.h][5]  | [masterex1000][6]  | Small UI helper library intended to be used with raylib. |
| [rpmd.c][7]  | [SamyBencherif][8] | Pixelated 2D lighting with shadows in raylib, software accelerated.  |
| [client_GUI.c][9] | [Goodguyr][10] | raylib example of networking, Drawing circles for each player.   |
| [pan.c][11]  | [JeffM2501][12] | raylib example of mouse drag panning for 2D camera. |
| [noisepl.c][13] | [Demizdor][14] | Noise Planets example made with raylib. |
| [RayCollisions.c][15] | [Pikachuxxxx][16] | Function to Detect Collisions Between a Ray and a Rectangle and Dynamic Rectangle and a Rectangle. |
| [raylib_dpi_hack.c][17] | [mattj1][18] | Function to get window DPI. |
<!--| [DrawTexturePro3D.c][19] | [Rabios][20] | Draw 2D texture with raylib in 3D space! |-->
| [raynames.h][21] | [dotxnc][22] | Header that provides lowercase name aliases for types and functions of raylib, raymath, easings, And rnet. |
| [raylibvectors.c][23] | [AregevDev][24] | raylib example for 2D Vectors. |
| [maze.c][25] | [EdwardDowling][26] | Maze generation and raycasting example. |
| [core_2d_camera_c-mera.lisp][27] | [pluckyporcupine][28] | raylib core_2d_camera example ported to [C-Mera][29]! |
| [core_split_screen.c][30] | [JeffM2501][12] | Simple splitscreen implemntation for raylib. |
| [models_mesh_generation.c][31] | [JeffM2501][12] | Example shows that Mesh generation of quad with UV repeats in raylib. |
| [imgui_docking_exmaple.cpp][32] | [JeffM2501][12] | Example of how to do editor style docking in [ImGui][33] for raylib. |
| [varfps.c][34] | [JeffM2501][12] | raylib test showing how frame based motion can be problematic. |
| [raylib worldspace panning with rotation][35] | [JeffM2501][12] | raylib example of worldspace panning with rotation. |
| [raylib worldspace panning][36] | [JeffM2501][12] | raylib example of worldspace panning without rotation. |
| [Model merge for raylib][37] | [JeffM2501][12] | Example of model merge made with raylib. |
| [raylib resize fullscreen example][38] | [JeffM2501][12] | raylib resize fullscreen example. |
| [orbitcamera.cpp][39] | [JeffM2501][12] | Example of orbit camera made for raylib! |
| [RLAssets.cpp][40] | [JeffM2501][12] | Basic platform independent asset folder management for raylib. |
| [Basic Shot Animation raylib][41] | [JeffM2501][12] | Basic animation made with raylib. |
| [Basic entity game][42] | [JeffM2501][12] | Entity example made with raylib. |
| [DrawTextureProZ][43] | [JeffM2501][12] | Modified version of `DrawTexturePro` that adds Z Dimension/Depth! |
| [raylib fullscreen toggle example][44] | [JeffM2501][12] | fullscreen toggle example made with raylib. |

[1]: https://gist.github.com/ohmree/dac78b36b736a71dc9a423d10b9509cc
[2]: https://github.com/ohmree
[3]: https://gist.github.com/satinxs/e55461da74ba378a09d813cb6767ffae
[4]: https://github.com/satinxs
[5]: https://gist.github.com/masterex1000/92c861eeef03e761d0addc6edc0b741f
[6]: https://github.com/masterex1000
[7]: https://gist.github.com/SamyBencherif/00412fa24b411c07ad57176e64793fb5
[8]: https://github.com/SamyBencherif
[9]: https://gist.github.com/Goodguyr/284a262dc95ab0a35b498115c1cb3d41
[10]: https://github.com/Goodguyr
[11]: https://gist.github.com/JeffM2501/3c7da5c2b7e078e254d673f91489c78f
[12]: https://github.com/JeffM2501
[13]: https://gist.github.com/Demizdor/e916ba765336c389af4ecd2c557a6be6
[14]: https://github.com/Demizdor
[15]: https://gist.github.com/Pikachuxxxx/0dda4b70bf71b794b08923df34961844
[16]: https://github.com/Pikachuxxxx
[17]: https://gist.github.com/mattj1/606a94527badb6ffa7d22245c9b745b1
[18]: https://github.com/mattj1
<!--[19]: https://gist.github.com/Rabios/ccbb08d7ff4f41af19d53bf02d803815-->
<!--[20]: https://github.com/Rabios-->
[21]: https://gist.github.com/dotxnc/403caefa3bd1eae3b8e265e79d6508ad
[22]: https://github.com/dotxnc
[23]: https://gist.github.com/AregevDev/737d14ce64be059ed2b6d0d973361985
[24]: https://github.com/AregevDev
[25]: https://gist.github.com/EdwardDowling/01a872cca79e1404bbc2
[26]: https://github.com/EdwardDowling
[27]: https://gist.github.com/pluckyporcupine/bbaa93b00e020c53faf27e5bde087374
[28]: https://github.com/pluckyporcupine
[29]: https://github.com/kiselgra/c-mera
[30]: https://gist.github.com/JeffM2501/85e3c3fa4c5296227ab91dd7d2dec471
[31]: https://gist.github.com/JeffM2501/18964218591e5aa302f17f0ae5a45b77
[32]: https://gist.github.com/JeffM2501/4c3a7e8a85302f743f8bd9dc1aae00ae
[33]: https://github.com/ocornut/imgui
[34]: https://gist.github.com/JeffM2501/588d8b632d1bf49c7f010dde0a9dcbee
[35]: https://gist.github.com/JeffM2501/703728379eb6e9d51d33201d1a1fe05d
[36]: https://gist.github.com/JeffM2501/edb5b8bbfd5a1744d4f97865ad4be989
[37]: https://gist.github.com/JeffM2501/08d20cdd931456ad0e52905401cc34af
[38]: https://gist.github.com/JeffM2501/00cf5653f41337d8c9e8db40deb25656
[39]: https://gist.github.com/JeffM2501/000787070aef421a00c02ae4cf799ea1
[40]: https://gist.github.com/JeffM2501/bd1092ce0eaedd26fe3ca60e1743ce40
[41]: https://gist.github.com/JeffM2501/a6eb14d734f88a065a73adb729eed1f7
[42]: https://gist.github.com/JeffM2501/a5987d2f4575e871f561197232ba0f60
[43]: https://gist.github.com/JeffM2501/1c4c9c8048cbb19d11c9807518196b69
[44]: https://gist.github.com/JeffM2501/6e4630a0e34c0c7dddf066f7192e342d

### Homebrew Ports

| Name                    | Author         | Platform              |
|-------------------------|----------------|-----------------------|
| [orbisdev-orbisGl2][45] | [orbisdev][46] | Sony PlayStation 4    |
| [raylib4Vita][47]       | [psp2dev][48]  | Sony PlayStation Vita |
| [3ds-raylib][49]        | [Gota7][50]    | Nintendo 3DS          |
| [raylib-nx][626]        | [LucaSkyer][627] | Nintendo Switch     |

[45]: https://github.com/orbisdev/orbisdev-orbisGl2
[46]: https://github.com/orbisdev
[47]: https://github.com/psp2dev/raylib4Vita
[48]: https://github.com/psp2dev
[49]: https://github.com/Gota7/3ds-raylib
[50]: https://github.com/Gota7
[626]: https://github.com/lucaskyer/raylib-nx
[627]: https://github.com/lucaskyer

### Libraries and Frameworks

| Name          | Author           | Description                                   |
|---------------|------------------|-----------------------------------------------|
| [rayfork][51] | [SasLuca][52]    | Single header and source, cross-platform, allocator-aware, C99 game libraries. |
<!--| [rayport][53] | [Rabios][20]     | Awesome C99, Header-Only, rayfork wrapper for raylib! |-->
| [rayutils][54] | [Rabios][20]    | Single-Header library that extends raylib with some awesome functionality! |
| [raygui][55] | [raysan5][56]     | Simple and easy-to-use immediate-mode GUI library. |
| [Physac][57] | [victorfisac][58] | 2D physics header-only library for videogames developed in C using raylib library. |
| [rpng][59] | [raysan5][56] | Simple and easy-to-use library to manage png chunks. | 
| [rres][60] | [raysan5][56] | Simple and easy-to-use file-format to package resources. |
| [raudio][61] | [raysan5][56] | Simple and easy-to-use audio library based on [miniaudio][62]. |
| [ECSlib][63] | [firststef][64] | Library with ECS classes in C++ using raylib. |
| [tbag][65] | [osom8979][66] | Third party extension utility project. |
| [imgui-impl-raylib][67] | [oswjk][68] | raylib backend for Dear ImGui. |
| [rlImGui](https://github.com/raylib-extras/rlImGui) | [raylib-extras](https://github.com/raylib-extras) | [Dear ImGui](https://github.com/ocornut/imgui) immediate graphical user interface for raylib. |
| [Libre][69] | [haydenhigg][70] | [Crystal][71] graphics library that is built on raylib. |
| [GameSystemsInC][72] | [nezvers][73] | TileMap & Sprite systems for raylib. |
| [raylib-asprite][74] | [RobLoach][75] | Load [Aseprite][76] files for animated sprites in raylib. |
| [raylib-nuklear][77] | [RobLoach][75] | [Nuklear][78] immediate mode GUI for raylib. |
| [zgui][79] | [zworld-apps][80] | GUI system based on Constraints for raylib, Written in [Go][81]. |
| [visual-go][82] | [Slixe][83] | Framework to create simple application using raylib & Flex. |
| [rlyeh][84] | [basp1][85] | Simple and easy-to-use GUI API library for [raylib-go][86], Written in Go. |
| [raycons][87] | [smthnspcl][88] | Icons drawn by raylib, Written in C++. |
| [raygauge][89] | [smthnspcl][88] | Simple gauges to display values with raylib, Written in C++. |
| [libpartikel][90] | [dbriemann][91] | Simple particle system library made with and for raylib. Works as header only library. |
| [spine-raylib-runtimes][92] | [WEREMSOFT][93] | raylib implementation of the C spine runtimes. |
| [stl-loader-for-raylib][94] | [WEREMSOFT][93] | STL loader for raylib, Allows to load 3dPrinter file types into raylib. |
| [Raylib-GBuffers][95] | [TheLumaio][96] | GBuffer implementation for raylib. |
| [tofu][97] | [tofuengine][98] | Lightweight 2D framework with a lo-fi vibe, for fast game prototyping. Uses OpenGL through [GLFW3][99], Scripted in Lua. |
| [RaylibEX][100] | [Ferrohound][101] | raylib Extra incorporates more basic functionality to raylib while keeping the hands-on aspect! |
| [MathX][102] | [JusticeShultz][103] | Detailed custom math library programmed in C++ that includes demos that uses raylib. |
| [LilySweetCat][104] | [RaylibCs-UI][105] | Just a simple UI using raylib (Can be used as library), Written in C#. |
| [raylib-tmx][106] | [RobLoach][75] | Load and draw [Tiled][107] `.tmx` tile maps through the [TMX C Loader][108]. |
| [ruicf][109] | [nbdy][110] | C++ raylib UI controls framework. |
| [RLGameGui][111] | [JeffM2501][12] | Resolution independent GUI for raylib, Written in C++! |
| [raylib-extensions][112] | [jackcarey][113] | Modifications/Additions to raylib and raygui. |
| [RayLibUtils][114] | [coolcoy12][115] | Useful UI and effects for raylib written in C++! |
| [raylib-barebones][116] | [moonsteal][117] | Stripped down version of raylib with Meson. |
| [RaylibSIMD][118] | [Doy-lee][119] | SIMD Implementation of raylib's API. |
| [RTAudioGameLib][120] | [8bitPandaPlugins][121] | C++ Game API built on raylib and [RTaudio][122] for latency critical implimentations. |
| [RayLib-Utilities][123] | [zzador][124] | Some utility & helper functions for raylib and raygui. |
| [libraygun][125] | [jozanza][126] | Utils for raylib. |
| [raylibExtras][127] | [JeffM2501][12] | C++ Utilities and common code for use with raylib. |
| [raylibImGui][128] | [Ushio][129] | C++ Dear ImGui integration for raylib. |
| [displayfx_raylib][130] | [nicholasimon][131] | Few effects to use on top of your game screen, scanlines, noise lines and pixel noise, written in Go. |
| [rlgutils][132] | [JacobLondon][133] | Go utilities for raylib. |
| [PaperSDL][134] | [thyliverman][135] | Small software library, designed to make using [raylib-cs][136] simpler and more concise, Written in C#. |
| [gtk-raylib][137] | [hbiblia][138] | [GTK][139] integration with raylib. |
| [gastar][140] | [impzero][141] | Algorithm implemented in Go visualized using raylib. |
| [raylib-physfs][142] | [RobLoach][75] | Provides integration with the virtual file system [PhysicsFS][143] |
| [raylib-assetsys](https://github.com/RobLoach/raylib-assetsys) | [RobLoach][75] | Load raylib assets from .zip files with [assetsys.h](https://github.com/mattiasgustavsson/libs/blob/main/assetsys.h) |
| [Paper][144] | [thyliverman][135] | C++ rewrite of [PaperSDL][134], dedicated to making raylib just a little easier to work with. |
| [Animator-For-Raylib][145] | [AliElSaleh][146] | C/C++ Animator lib. |
| [TestFrame][147] | [JeffM2501][12] | Test framework that uses raylib and ImGui together to help test and develop concept and uses C++ classes for windows and views. |
| [ferox][148] | [c-krit][149] | 2D collision detection and physics library written in C. |
| [RaylibOpOverloads][150] | [ProfJski][151] | C++ Operator Overloads for raylib. |
| [rlzero][152] | [electronstudio][153] | Simplified API for raylib to enable beginners to create 3D games, Inspired by [Pygame Zero][154]. |
| [haxeui-raylib][155] | [haxeui][156] | raylib backend for [HaxeUI][157]. |
| [rlobj][158] | [Not-Nik][159] | drop-in replacement for raylib's obj loader. |
| [Glui][624] | [Samerion][625] | Declarative D user interface library for raylib. |
| [raylib-api](https://github.com/RobLoach/raylib-api) | [RobLoach](https://github.com/robloach) | Exports of the raylib APIs in different formats (XML, JSON, Lua, etc) |
| [raylib-assert](https://github.com/RobLoach/raylib-assert) | [RobLoach](https://github.com/robloach) | Runtime assertion library for raylib |
| [dk_console](https://github.com/dkvilo/dk_console) | [dkvilo](https://github.com/dkvilo) | Drop in dev console for your raylib game/engine |
| [raylib-video](https://github.com/RicoP/raylib-video) | [RicoP](https://github.com/RicoP/raylib-video) | A multi-threaded realtime single header library to stream MPEG1 videos to textures |

[51]: https://github.com/SasLuca/rayfork
[52]: https://github.com/SasLuca
<!--[53]: https://github.com/Rabios/rayport-->
<!--[54]: https://github.com/Rabios/rayutils-->
[55]: https://github.com/raysan5/raygui
[56]: https://github.com/raysan5
[57]: https://github.com/victorfisac/Physac
[58]: https://github.com/victorfisac
[59]: https://github.com/raysan5/rpng
[60]: https://github.com/raysan5/rres
[61]: https://github.com/raysan5/raudio
[62]: https://miniaud.io
[63]: https://github.com/firststef/ECSlib
[64]: https://github.com/firststef
[65]: https://github.com/osom8979/tbag
[66]: https://github.com/osom8979
[67]: https://github.com/oswjk/imgui-impl-raylib
[68]: https://github.com/oswjk
[69]: https://github.com/haydenhigg/Libre
[70]: https://github.com/haydenhigg
[71]: https://crystal-lang.org
[72]: https://github.com/nezvers/GameSystemsInC
[73]: https://github.com/nezvers
[74]: https://github.com/RobLoach/raylib-aseprite
[75]: https://github.com/RobLoach
[76]: https://www.aseprite.org
[77]: https://github.com/RobLoach/raylib-nuklear
[78]: https://github.com/Immediate-Mode-UI/Nuklear
[79]: https://github.com/zworld-apps/zgui
[80]: https://github.com/zworld-apps
[81]: https://go.dev
[82]: https://github.com/Slixe/visual-go
[83]: https://github.com/Slixe
[84]: https://github.com/basp1/rlyeh
[85]: https://github.com/basp1
[86]: https://github.com/gen2brain/raylib-go
[87]: https://github.com/smthnspcl/raycons
[88]: https://github.com/smthnspcl
[89]: https://github.com/smthnspcl/raygauge
[90]: https://github.com/dbriemann/libpartikel
[91]: https://github.com/dbriemann
[92]: https://github.com/WEREMSOFT/spine-raylib-runtimes
[93]: https://github.com/WEREMSOFT
[94]: https://github.com/WEREMSOFT/stl-loader-for-raylib
[95]: https://github.com/TheLumaio/Raylib-GBuffers
[96]: https://github.com/TheLumaio
[97]: https://github.com/tofuengine/tofu
[98]: https://github.com/tofuengine
[99]: https://www.glfw.org
[100]: https://github.com/Ferrohound/RaylibEX
[101]: https://github.com/Ferrohound
[102]: https://github.com/JusticeShultz/MathX
[103]: https://github.com/JusticeShultz
[104]: https://github.com/LilySweetCat/RaylibCs-UI
[105]: https://github.com/LilySweetCat
[106]: https://github.com/RobLoach/raylib-tmx
[107]: https://www.mapeditor.org
[108]: https://github.com/baylej/tmx
[109]: https://github.com/nbdy/ruicf
[110]: https://github.com/nbdy
[111]: https://github.com/JeffM2501/RLGameGui
[112]: https://github.com/jackcarey/raylib-extensions
[113]: https://github.com/jackcarey
[114]: https://github.com/coolcoy12/RayLibUtils
[115]: https://github.com/coolcoy12
[116]: https://github.com/moonsteal/raylib-barebones
[117]: https://github.com/moonsteal
[118]: https://github.com/Doy-lee/RaylibSIMD
[119]: https://github.com/Doy-lee
[120]: https://github.com/8bitPandaPlugins/RTAudioGameLib
[121]: https://github.com/8bitPandaPlugins
[122]: https://github.com/thestk/rtaudio
[123]: https://github.com/zzador/RayLib-Utilities
[124]: https://github.com/zzador
[125]: https://github.com/jozanza/libraygun
[126]: https://github.com/jozanza
[127]: https://github.com/JeffM2501/raylibExtras
[128]: https://github.com/Ushio/raylibImGui
[129]: https://github.com/Ushio
[130]: https://github.com/nicholasimon/displayfx_raylib
[131]: https://github.com/nicholasimon
[132]: https://github.com/JacobLondon/rlgutils
[133]: https://github.com/JacobLondon
[134]: https://github.com/thyliverman/PaperSDL
[135]: https://github.com/thyliverman
[136]: https://github.com/ChrisDill/Raylib-cs
[137]: https://github.com/hbiblia/gtk-raylib
[138]: https://github.com/hbiblia
[139]: https://www.gtk.org
[140]: https://github.com/impzero/gastar
[141]: https://github.com/impzero
[142]: https://github.com/RobLoach/raylib-physfs
[143]: https://www.icculus.org/physfs
[144]: https://github.com/thyliverman/Paper
[145]: https://github.com/AliElSaleh/Animator-For-Raylib
[146]: https://github.com/AliElSaleh
[147]: https://github.com/JeffM2501/TestFrame
[148]: https://github.com/c-krit/ferox
[149]: https://github.com/c-krit
[150]: https://github.com/ProfJski/RaylibOpOverloads
[151]: https://github.com/ProfJski
[152]: https://github.com/electronstudio/rlzero
[153]: https://github.com/electronstudio
[154]: https://github.com/lordmauve/pgzero
[155]: https://github.com/haxeui/haxeui-raylib
[156]: https://github.com/haxeui
[157]: http://haxeui.org
[158]: https://github.com/Not-Nik/rlobj
[159]: https://github.com/Not-Nik
[624]: https://git.samerion.com/Samerion/Glui
[625]: https://git.samerion.com/Samerion

CHECKPOINT

### Softwares

| Name       | Author     | Description                       |
|------------|------------|-----------------------------------|
| [gxarch][160] | [gtrxAC][161] | Simple fantasy computer architecture that uses raylib! |
| [gxSE][162] | [gtrxAC][161] | Command-based sprite/image editor. |
| [3d-audio-producer][163] | [adct-the-experimenter][164] | Fork of the [adct-the-experimenter/binaural-audio-editor][165] that uses replaced with raygui and raylib. |
| [chip8][166] | [Lockna][167] | Very basic [CHIP-8][168] emulator that uses raylib for rendering. |
| [SkyBoy][169] | [skylersaleh][170] | Game Boy and Game Boy Color Emulator powered by raylib! |
| [2D-CAD-Raylib][171] | [sparkskapil][172] | 2D CAD viewer for raylib. |
| [raygui_calculator][173] | [sorykkk][174] | Demonstrates simple and functional calculator gui written with raygui based on raylib library. |
| [FunWithEasings][175] | [MarcMDE][176] | Small and simple Easings visualizing tool developed in C with raylib and C easings. |
| [SharedBuff][177] | [Mudzii][178] | Level editor using a shared buffer between an Maya API and raylib engine. |
| [rFXGen][179] | [raysan5][56] | Simple and easy-to-use fx sounds generator. |
| [rPBR][180] | [victorfisac][58] | 3D model viewer with PBR pipeline written using OpenGL with usage of raylib in pure C. |
| [raylib-libretro][181] | [RobLoach][75] | [libretro][182] frontend using raylib. |
| [FNode][183] | [victorfisac][58] | Tool based in nodes to build GLSL shaders without any programming knowledge written in C using OpenGL and GLFW. |
| [RayTracer][184] | [MaximeHouis][185] | Ray Tracer in C++ using raylib. |
| [GeldaEngine][186] | [fedqx][187] | C raylib game engine. |
| [rengfx][188] | [xdrie][189] | Lightweight, expressive, extensible 2D/3D game engine, Written in [D][190]. |
<!--| [raytaiko][191] | [Rabios][20] | Simple and moddable Taiko no Tatsujin engine written in [Lua][192] using raylib using [TSnake41][193]'s [LuaJIT bindings][194]. |-->
| [cbit-raylib][195] | [nurakmaljalil91][196] | C++ Game Engine built on top of raylib. |
| [PhysicsEngine][197] | [CarterPatterson][198] | Simple physics engine built in raylib for [AIE][199] CS 2019, Written in C++! |
| [Midday-Commander][200] | [Guevara-chan][201] | •Retrofuturistic file manager•, Written in [Nim][202]. |
| [ttme][203] | [hfabre][204] | Tiny tile map editor, Written in Go. |
| [ArtColors][205] | [ProfJski][151] | Sort of color mixing tools built with raylib. |
| [experimental-raygui-editor][206] | [Demizdor][14] |  Experimental GUI editor for raygui. |
| [Raylib-Buildfiles][207] | [rfaile313][208] | Simple Makefile that incorporates raylib on OS: Windows && Platform: Desktop. |
| [music-player][209] | [redsled84][210] | Linked list music player using raylib. |
| [riley-duper][211] | [ArnautDaniel][212] | Iterative melancholy written in Factor. |
| [raylib-vide-player][213] | [WEREMSOFT][93] | Videoplayer using raylib. Play unsuported video format by the browser in the broswer. |
| [baslike-editor][214] | [TheLumaio][96] | Editor for [baslike][215] written in raylib. |
| [PACKER][216] | [pkeckler][217] | raylib asset packer. |
| [Chip8-raylib][218] | [ComLarsic][219] | [CHIP-8][168] emulator written in C# using raylib. |
| [Chip8][220] | [LesFarrell][221] | [CHIP-8][168] Emulator/Interpreter using written using C and the raylib library. |
| [cobra-py][222] | [ralsina][223] | 80s-style [Python][224] environment. |
| [Alien-raylib][225] | [athreef][226] | Alien distribution for raylib video game engine. |
| [cpp-raylib-tilemap][227] | [JusticeShultz][103] | Runtime tile map tool in the C++ raylib library. |
| [MasterPlan][228] | [SolarLune][229] | easy-to-use graphical free-flow project management tool and idea board. |
| [Cute Exporter][230] | [Clay Murray][231] | The best PSD layers to PNG texture atlas exporter. |
| [MySprite][232] | [TonyButDead][233] | Free pixel art tool created in the Go programming language with raylib. |
| [SeijiEmery's level editor][234] | [SeijiEmery][235] | Quick experiment in building a small game/nice-ish level editor/platformer from scratch with raylib over a weekend. |
| [rTexPacker][236] | [raylib technologies][237] | Simple and easy-to-use textures packer and font atlas generator. |
| [rTexViewer][238] | [raylib technologies][237] | Simple and easy-to-use textures viewer and pixel formats converter. |
| [rIconPacker][239] | [raylib technologies][237] | Simple and easy-to-use icons packer. |
| [rGuiStyler][240] | [raylib technologies][237] | Simple and easy-to-use raygui styles editor. |
| [rGuiLayout][241] | [raylib technologies][237] | Simple and easy-to-use raygui layouts editor. |
| [rGuiIcons][242] | [raylib technologies][237] | Simple and easy-to-use raygui icons editor. |
| [graphingcalculator][243] | [obaodelana][244] | Graphing Calculator made with raylib using C. |
| [LevelEditor-MayaPlugin][247] | [MadeleinNyblom][248] | Level editor that sends information from [Maya][249] to raylib using a circular buffer. |
| [khkFramework-raylib][250] | [kenhyokun][251] | Experimental C/C++ 2D game framework with raylib. |
| [abyss_engine][252] | [HurricaneInteractive][253] | Very simple game engine written in [Rust][254] and built on top of [raylib-rs][255]. |
| [CopyCat][256] | [reidevries][257] | C++ 17 Game engine based on raylib and [EnTT][258] libraries, end goal of creating a tactical RPG. |
| [peryEngine][259] | [pery77][260] | C/C++ Retro game engine based on raylib. |
| [Ungine][261] | [The-Italian-Coders-Group][262] | [Source][263]-like raylib-based game engine for C++. |
| [chat_from_scratch][264] | [senior-sigan][265] | Code from the series of my streams where I work on creating Chat application absolutely from scratch, Written in C++. |
| [mmGame-Engine-Raylib-ECS][266] | [bayganik][267] | C# Game engine using Raylib-cs and [Entitas lite][268] as an ECS. |
| [ray-quake][269] | [xero1][270] | [.NET][271] Core Quake source port built using raylib. |
| [raylibeditor][272] | [practicing01][273] | Editor made with raylib. |
| [tyro][274] | [parmaja][275] | Simple graphical environment for kids and newbies, using raylib as small game engine to draw, Written in Pascal. |
| [Raylibculator][276] | [Fakaaa][277] | Calculator made with raylib. |
| [raylib_package][278] | [Elkantor][279] | [BSCXX][280] module for raylib C library. |
| [clay][281] | [RafaelOliveira][282] | 2D game engine for raylib in C++. |
| [Quill][283] | [sparkskapil][172] | 2D CAD Application using raylib and C++. |
| [RayLib-Keyboard-keycode-tester][284] | [jmorel33][285] | Keyboard tester made with raylib. |
| [sponGB][286] | [kugo12][287] | Gameboy emulator written using Rust and raylib. |
| [BlobEditor][288] | [trikko][289] | Simple raylib and Dlang project. |
| [nprof][290] | [Andre-LA][291] | Very basic profiler for [raylib-nelua][292], Written in [Nelua][293]. |
| [mc_rtc-raylib][294] | [gergondet][295] | Simple [mc_rtc][296] GUI client using raylib. |
| [Red-Shell][297] | [KonPet][298] | Level Editor for the Mario vs Luigi Python clone made in C++ using raylib. |
| [XPROEngine][299] | [JonSnowbd][300] | build-inside C game engine that utilizes raylib/[Flecs][301]/[Binn][302] to create incredibly fast games with C/Lua. |
| [gargula][303] | [gilzoide][304] | Game engine based on nested structs and compile-time tree traversals powered by raylib and D compatible with better C. |
| [randevlper][305] | [rayoflight][306] | 2D Engine implementing [Box2D][307] and raylib. |
| [v2][308] | [notsnail][309] | Framework for games built with raylib. |
| [particle_editor][313] | [Demizdor][14] | Experimental particle editor! |
| [rlwm][314] | [gtrxAC][160] | Fake operating system/window manager. |
| [HellRok][315] | [Taylor][316] | Simple game engine built using raylib and [MRuby][317]. |
| [Sketch_Game_Engine][318] | [MallocStudio][319] | Simple game engine built on top of raylib that intended as personal hobby project. |
| [simple_raycasting][320] | [TheDarkBug][321] | Simple raycasting "engine" written in C with raylib for graphics. |
| [LunarViewer][322] | [LunaRyuko][323] | Model viewer for Quake 1 and Hexen 2. |
| [mapviewer][324] | [myuce][325] | Very primitive map viewer for the Quake map format. |
| [minitile][326] | [catmanl][327] | A mini tilemap editor. |

[160]: https://github.com/gtrxAC/gxarch
[161]: https://github.com/gtrxAC
[162]: https://github.com/gtrxAC/gxSE
[163]: https://github.com/adct-the-experimenter/3d-audio-producer
[164]: https://github.com/adct-the-experimenter
[165]: https://github.com/adct-the-experimenter/binaural-audio-editor
[166]: https://github.com/Lockna/chip8
[167]: https://github.com/Lockna
[168]: https://en.wikipedia.org/wiki/CHIP-8
[169]: https://github.com/skylersaleh/SkyBoy
[170]: https://github.com/skylersaleh
[171]: https://github.com/sparkskapil/2D-CAD-Raylib
[172]: https://github.com/sparkskapil
[173]: https://github.com/sorykkk/raygui_calculator
[174]: https://github.com/sorykkk
[175]: https://github.com/MarcMDE/FunWithEasings
[176]: https://github.com/MarcMDE
[177]: https://github.com/Mudzii/SharedBuff
[178]: https://github.com/Mudzii
[179]: https://github.com/raysan5/rfxgen
[180]: https://github.com/victorfisac/rPBR
[181]: https://github.com/RobLoach/raylib-libretro
[182]: https://www.libretro.com
[183]: https://github.com/victorfisac/FNode
[184]: https://github.com/MaximeHouis/RayTracer
[185]: https://github.com/MaximeHouis
[186]: https://github.com/fedqx/GeldaEngine
[187]: https://github.com/fedqx
[188]: https://github.com/xdrie/rengfx
[189]: https://github.com/xdrie
[190]: https://dlang.org
<!--[191]: https://github.com/Rabios/raytaiko-->
[192]: https://lua.org
[193]: https://github.com/TSnake41
[194]: https://github.com/TSnake41/raylib-lua
[195]: https://github.com/nurakmaljalil91/cbit-raylib
[196]: https://github.com/nurakmaljalil91
[197]: https://github.com/CarterPatterson/PhysicsEngine
[198]: https://github.com/CarterPatterson
[199]: https://aieinstitute.edu.au
[200]: https://github.com/Guevara-chan/Midday-Commander
[201]: https://github.com/Guevara-chan
[202]: https://nim-lang.org
[203]: https://github.com/hfabre/ttme
[204]: https://github.com/hfabre
[205]: https://github.com/ProfJski/ArtColors
[206]: https://github.com/Demizdor/experimental-raygui-editor
[207]: https://github.com/rfaile313/Raylib-Buildfiles
[208]: https://github.com/rfaile313
[209]: https://github.com/redsled84/music-player
[210]: https://github.com/redsled84
[211]: https://github.com/ArnautDaniel/riley-duper
[212]: https://github.com/ArnautDaniel
[213]: https://github.com/WEREMSOFT/c99-raylib-vide-player
[214]: https://github.com/TheLumaio/baslike-editor
[215]: https://github.com/TheLumaio/baslike
[216]: https://github.com/pkeckler/PACKER
[217]: https://github.com/pkeckler
[218]: https://github.com/ComLarsic/Chip8-raylib
[219]: https://github.com/ComLarsic
[220]: https://github.com/LesFarrell/Chip8
[221]: https://github.com/LesFarrell
[222]: https://github.com/ralsina/cobra-py
[223]: https://github.com/ralsina
[224]: https://python.org
[225]: https://github.com/athreef/Alien-raylib
[226]: https://github.com/athreef
[227]: https://github.com/JusticeShultz/cpp-raylib-tilemap
[228]: https://solarlune.itch.io/masterplan
[229]: https://solarlune.itch.io
[230]: https://powerc9000.itch.io/cute-asset-pipeline
[231]: https://powerc9000.itch.io
[232]: https://tonybutdead.itch.io/mysprite
[233]: https://tonybutdead.itch.io
[234]: https://seijiemery.itch.io/agj-level-editor-in-a-weekend
[235]: https://seijiemery.itch.io
[236]: https://raylibtech.itch.io/rtexpacker
[237]: https://raylibtech.itch.io
[238]: https://raylibtech.itch.io/rtexviewer
[239]: https://raylibtech.itch.io/riconpacker
[240]: https://raylibtech.itch.io/rguistyler
[241]: https://raylibtech.itch.io/rguilayout
[242]: https://raylibtech.itch.io/rguiicons
[243]: https://github.com/obaodelana/graphingcalculator
[244]: https://github.com/obaodelana
[247]: https://github.com/MadeleinNyblom/LevelEditor-MayaPlugin
[248]: https://github.com/MadeleinNyblom
[249]: https://www.autodesk.com/products/maya/overview
[250]: https://github.com/kenhyokun/khkFramework-raylib
[251]: https://github.com/kenhyokun
[252]: https://github.com/HurricaneInteractive/abyss_engine
[253]: https://github.com/HurricaneInteractive
[254]: https://www.rust-lang.org
[255]: https://github.com/deltaphc/raylib-rs
[256]: https://github.com/reidevries/CopyCat
[257]: https://github.com/reidevries
[258]: https://github.com/skypjack/entt
[259]: https://github.com/pery77/peryEngine
[260]: https://github.com/pery77
[261]: https://github.com/Italian-Coders-Group/Ungine
[262]: https://github.com/Italian-Coders-Group
[263]: https://developer.valvesoftware.com/wiki/Source
[264]: https://github.com/senior-sigan/chat_from_scratch
[265]: https://github.com/senior-sigan
[266]: https://github.com/bayganik/mmGame-Engine-Raylib-ECS
[267]: https://github.com/bayganik
[268]: https://github.com/rocwood/Entitas-Lite
[269]: https://github.com/xero1/ray-quake
[270]: https://github.com/xero1
[271]: https://dotnet.microsoft.com
[272]: https://github.com/practicing01/raylibeditor
[273]: https://github.com/practicing01
[274]: https://github.com/parmaja/tyro
[275]: https://github.com/parmaja
[276]: https://github.com/Fakaaa/Raylibculator
[277]: https://github.com/Fakaaa
[278]: https://github.com/Elkantor/raylib_package
[279]: https://github.com/Elkantor
[280]: https://github.com/Elkantor/bscxx
[281]: https://github.com/RafaelOliveira/clay
[282]: https://github.com/RafaelOliveira
[283]: https://github.com/sparkskapil/Quill
[284]: https://github.com/jmorel33/RayLib-Keyboard-keycode-tester
[285]: https://github.com/jmorel33
[286]: https://github.com/kugo12/sponGB
[287]: https://github.com/kugo12
[288]: https://github.com/trikko/BlobEditor
[289]: https://github.com/trikko
[290]: https://github.com/Andre-LA/nprof
[291]: https://github.com/Andre-LA
[292]: https://github.com/Andre-LA/raylib-nelua
[293]: https://nelua.io
[294]: https://github.com/gergondet/mc_rtc-raylib
[295]: https://github.com/gergondet
[296]: https://github.com/jrl-umi3218/mc_rtc
[297]: https://github.com/KonPet/Red-Shell
[298]: https://github.com/KonPet
[299]: https://github.com/JonSnowbd/XPROEngine
[300]: https://github.com/JonSnowbd
[301]: https://github.com/SanderMertens/flecs
[302]: https://github.com/liteserver/binn
[303]: https://github.com/gilzoide/gargula
[304]: https://github.com/gilzoide
[305]: https://github.com/randevlper/rayoflight
[306]: https://github.com/randevlper
[307]: https://box2d.org
[308]: https://github.com/notsnail/v2
[309]: https://github.com/notsnail
[310]: https://github.com/erikerlandson/ray-ubi
[311]: https://github.com/erikerlandson
[312]: https://developers.redhat.com/products/rhel/ubi
[313]: https://github.com/Demizdor/particle_editor
[314]: https://github.com/gtrxAC/rlwm
[315]: https://github.com/HellRok/Taylor
[316]: https://github.com/HellRok
[317]: https://mruby.org
[318]: https://github.com/MallocStudio/Sketch_Game_Engine
[319]: https://github.com/MallocStudio
[320]: https://github.com/TheDarkBug/simple_raycasting
[321]: https://github.com/TheDarkBug
[322]: https://github.com/LunaRyuko/LunarViewer
[323]: https://github.com/LunaRyuko
[324]: https://github.com/myuce/mapviewer
[325]: https://github.com/myuce
[326]: https://github.com/catmanl/minitile
[327]: https://github.com/catmanl

### Deprecated/Removed/Unknown bindings

| Name                        | Author               | Language             |
|-----------------------------|----------------------|----------------------|
| [Raylib-J][328]             | [CreedVI][329]       | Java ([LWJGL3][330]) |
| [rust_raylib_bindings][331] | [DevJac][332]        | Rust                 |
| [raylib-rust][333]          | [dtcristo][334]      | Rust                 |
| [Raylib-for-GLBasic][335]   | [SliverLIVE][336]    | [GLBasic][337]       |
| [fb-raylib][338]            | [glasyalabolas][339] | [FreeBASIC][340]     |
| [raylib-haxe][341]          | [haxeui][342]        | [Haxe][343]          |
| [rayex][344]                | [shiryel][345]       | [Elixir][346]        |

[328]: https://github.com/CreedVI/Raylib-J
[329]: https://github.com/CreedVI
[330]: https://www.lwjgl.org
[331]: https://github.com/DevJac/rust_raylib_bindings
[332]: https://github.com/DevJac
[333]: https://github.com/dtcristo/raylib-rust
[334]: https://github.com/dtcristo
[335]: https://github.com/SliverLIVE/Raylib-for-GLBasic
[336]: https://github.com/SliverLIVE
[337]: https://www.glbasic.com
[338]: https://github.com/glasyalabolas/fb-raylib
[339]: https://github.com/glasyalabolas
[340]: https://www.freebasic.net
[341]: https://github.com/haxeui/raylib-haxe
[342]: https://github.com/haxeui
[343]: https://haxe.org
[344]: https://github.com/shiryel/rayex
[345]: https://github.com/shiryel
[346]: https://elixir-lang.org

> NOTE: You won't find these bindings in [BINDINGS.md](https://github.com/raysan5/raylib/blob/master/BINDINGS.md)!

### Libraries bindings/ports

| Name                          | Author          | Description              |
|-------------------------------|-----------------|--------------------------|
| [rayfork-rs][347]             | [Dacode45][348] | Port of rayfork to Rust. |
| [Animator-For-Raylib-CS][349] | [EMoore13][350] | Modified version of AliElSaleh's Animator-For-Raylib that uses raylib-cs! |

[347]: https://github.com/Dacode45/rayfork-rs
[348]: https://github.com/Dacode45
[349]: https://github.com/EMoore13/Animator-For-Raylib-CS
[350]: https://github.com/EMoore13

### Community Examples

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
<!--| [rayfork-games][430] | [Rabios][20] | Full port of raylib sample games to rayfork! |-->
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
<!-- [430]: https://github.com/Rabios/rayfork-games -->
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
- [Bad Apple!! but its 7600 ReCT and Raylib Logos [info in description]](https://www.youtube.com/watch?v=8LnQ1A0rJ9s)
- [Why I'm Glad I Didn't Use a Game Engine](https://www.youtube.com/watch?v=nBaCRp9UzDw)
- [raylib C - Simple sand game](https://www.youtube.com/watch?v=o8QOWVHaMsg)
- [Using Android's sensor with Raylib](https://www.youtube.com/watch?v=2woi4NR7xPA)
- [Raylib SpriteEngine](https://www.youtube.com/watch?v=mMPtnHUiZbM)
- [Bad Apple!! but its 7600 ReCT and Raylib Logos [info in description]](https://www.youtube.com/watch?v=8LnQ1A0rJ9s)
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
<!--[![Rabios/rayport](logos/rayport.png)](https://github.com/Rabios/rayport "Rabios/rayport")-->
[![RobLoach/raylib-cpp](logos/raylib-cpp.png)](https://github.com/robloach/raylib-cpp "RobLoach/raylib-cpp")
[![ChrisDill/Raylib-cs](logos/raylib-cs.png)](https://github.com/ChrisDill/Raylib-cs "ChrisDill/Raylib-cs")
<!--[![Rabios/raylib-boo](logos/raylib-boo.png)](https://github.com/Rabios/raylib-boo "Rabios/raylib-boo")-->
[![gen2brain/raylib-go](logos/raylib-go.png)](https://github.com/gen2brain/raylib-go "gen2brain/raylib-go")
[![Lachee/raylib-goplus](logos/raylib-go-plus.png)](https://github.com/Lachee/raylib-goplus "Lachee/raylib-goplus")
[![deltaphc/raylib-rs](logos/raylib-rust.png)](https://github.com/deltaphc/raylib-rs "deltaphc/raylib-rs")
[![raysan5/raylib-lua](logos/raylib-lua.png)](https://github.com/raysan5/raylib-lua "raysan5/raylib-lua")
[![RobLoach/raylib-lua-sol](logos/raylib-lua-sol.png)](https://github.com/RobLoach/raylib-lua-sol "RobLoach/raylib-lua-sol")
[![TSnake41/raylib-lua](logos/tsnake41-raylib-lua.png)](https://github.com/TSnake41/raylib-lua "TSnake41/raylib-lua")
[![HDPLocust/raylib-luamore](logos/raylib-luamore.png)](https://github.com/HDPLocust/raylib-luamore "HDPLocust/raylib-luamore")
<!--[![Rabios/raylua](logos/raylua.png)](https://github.com/Rabios/raylua "Rabios/raylua")-->
[![Andre-LA/raylib-nelua](logos/raylib-nelua.png)](https://github.com/Andre-LA/raylib-nelua "Andre-LA/raylib-nelua")
[![AregevDev/raylib-cr](logos/raylib-cr.png)](https://github.com/AregevDev/raylib-cr "AregevDev/raylib-cr")
[![drezgames/raylib-pascal](logos/raylib-pascal.png)](https://github.com/drezgames/raylib-pascal "drezgames/raylib-pascal")
[![GuvaCode/Ray4Laz](logos/ray4laz.png)](https://github.com/GuvaCode/Ray4Laz "GuvaCode/Ray4Laz")
[![overdev/raylib-py](logos/raylib-py.png)](https://github.com/overdev/raylib-py "overdev/raylib-py")
[![RobLoach/node-raylib](logos/node-raylib.png)](https://github.com/RobLoach/node-raylib "RobLoach/node-raylib")
<!--[![Rabios/raylib-v7](logos/raylib-v7.png)](https://github.com/Rabios/raylib-v7 "Rabios/raylib-v7")-->
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
