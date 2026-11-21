<div align="center">

<img src="./banner.svg" alt="Rishika Bimal Attodi: Graphics, Real-Time Systems, Interactive Software" width="100%"/>

<br/>

<a href="https://YOUR-PORTFOLIO-URL"><img src="./btn-portfolio.svg" alt="Portfolio" height="52"/></a>
<a href="https://www.linkedin.com/in/rishikaba"><img src="./btn-linkedin.svg" alt="LinkedIn" height="52"/></a>
<a href="https://www.youtube.com/@RishBiA"><img src="./btn-youtube.svg" alt="Demo videos on YouTube" height="52"/></a>
<a href="mailto:YOUR-EMAIL"><img src="./btn-email.svg" alt="Email" height="52"/></a>

</div>

<img src="./divider.svg" width="100%"/>

<img src="./h-about.svg" alt="About me" width="100%"/>

I build real-time software in **C and C++**: renderers, engine systems and networked games, mostly from scratch.
I've written a 3D rasterizer that draws every pixel on the CPU, been Graphics Champion on a custom OpenGL engine, and right now I'm turning real Singapore streets into a 3D training simulator for autonomous shuttles.

<table>
<tr>
<td>🌸 <b>Now</b></td>
<td>Visualisation &amp; Integration Lead on <b>Formula 9</b>, an autonomous shuttle fleet simulator (9-person team)</td>
</tr>
<tr>
<td>🎓 <b>Studying</b></td>
<td>B.Sc. Computer Science in Real-Time Interactive Simulation, <b>SIT-DigiPen Singapore</b></td>
</tr>
<tr>
<td>✨ <b>Most at home in</b></td>
<td>Rendering, engine systems, server-authoritative networking</td>
</tr>
<tr>
<td>💌 <b>Open to</b></td>
<td>Internships in data analysis and business analysis</td>
</tr>
</table>

<br/>

<img src="./h-work.svg" alt="Featured work" width="100%"/>

#### 🚐 Formula 9: Autonomous Shuttle Fleet Training Simulator
<sub><b>9-person multidisciplinary team</b> · Visualisation &amp; Integration Lead · Sep 2026 to present</sub>

A Unity 3D simulator that trains autonomous-shuttle fleet managers on real Singapore streets: route planning, incident response and battery charging, then watching the fleet drive it out in 3D.

<img src="./stats-f9.svg" alt="1,066 real Toa Payoh buildings in 3D · 5,249 real LTA bus stops · 141 automated tests" width="480"/>

- **Unity port:** moved the earlier native client into Unity across 133 files, rebuilding 8 UI pages and the live fleet map on OpenStreetMap tiles.
- **3D city:** built Toa Payoh from 1,066 real buildings in 5 data-driven styles (HDB, office, low-rise, landed, other), with custom shaders, shadows, a procedural sky and 5 shuttles on colour-coded routes.
- **Procedural textures:** wrote a Unity editor tool that paints every building style from JSON using tileable fractal noise (windows, balconies, curtains, weathering) with matching normal maps, packed into 4 texture arrays. It replaced 10 hand-made PNGs, and restyling is now a one-click rebuild.
- **Charging, end to end:** Unity UI, FastAPI endpoints and JSON schemas for booking across 4 chargers, with overlap and conflict checks so a port is never double-booked. Also fixed a charging deadlock.
- **Road-detail pipeline:** data pipeline and REST API for 62 signalised junctions (683 signal heads), 151 crossings and 10,000+ road markings.

`Unity 6` `C#` `Python` `FastAPI` `JSON Schema` `pytest` `ShaderLab` `Procedural textures` `OpenStreetMap` · 🎬 [Demo video](YOUR-LINK) · 🔒 private team repo

<br/>

#### 🦉 Luminara Zoo
<sub><b>8-person team (NocturnalStudios)</b> · Graphics Champion · Sep 2025 to Apr 2026</sub>

A night-shift point-and-click game where you keep four zoo animals fed, healthy and sane until 6 am. I built the rendering core of our own **custom C++ / OpenGL engine** across six milestones, as primary author of 12 engine files.

<img src="./stats-luminara.svg" alt="168 commits · ~2,800 lines of engine code · 22 scenes" width="480"/>

- **Engine setup:** built the engine from scratch, integrating 6 libraries (GLFW, GLEW, GLM, ImGui, STB, RapidJSON) into a CMake build that separates Engine and Game, with a one-click script so all 8 teammates could build it.
- **Renderer:** wrote the renderer, sprite rendering, shader, buffer and framebuffer classes and a 2D camera with zoom, plus a layering system with drag-to-reorder in the ImGui editor.
- **Particles &amp; VFX:** a JSON-driven particle and screen-effect system with 5 GLSL shaders (floating particles, falling leaves, water, static camera), each toggled per scene in the editor without code changes.
- **Shipping:** a Windows installer and uninstaller (Inno Setup) that bundles the release and its assets, refined over 3 versions until it installed cleanly on school lab PCs.

`C++` `OpenGL` `GLSL` `ECS` `ImGui` `RapidJSON` `CMake` `Inno Setup` · 🎬 [Demo video](YOUR-LINK) · 📁 [Repo](https://github.com/nursyazliyarni/NocturnalStudios)

<br/>

<table>
<tr>
<td width="50%" valign="top">

#### 🔺 3D Software Rasterizer
<sub>Solo · Computer Graphics · 2025</sub>

An OpenGL-style pipeline written by hand in C++, with every pixel drawn on the CPU: barycentric rasterization, a depth buffer, perspective-correct texturing, frustum culling and Sutherland–Hodgman clipping. It renders about 60 lit objects with shadows.

`C++` `Rasterization` `Clipping` · 🎬 [Demo](YOUR-LINK)

</td>
<td width="50%" valign="top">

#### 🧩 Multiplayer Sudoku Rush
<sub>2-person team · Backend &amp; gameplay · 2026</sub>

A real-time Sudoku race for 2–3 players over **UDP with a custom reliability layer**. The server validates every move and decides who claimed each cell first. It also has rooms, a live leaderboard and SQLite match history.

`C++` `UDP` `SQLite` `Win32` · 📁 [Repo](https://github.com/R15hika/MultiplayerSudokuGame)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🍪 The Gingerbread Curse
<sub>3-person team · Team lead · Nov 2026</sub>

A 2-player co-op potion game in C over **encrypted Cyclone DDS**, where the host enforces the rules. I built salted PBKDF2 accounts on a separate auth thread, DDS Security, rejoin, and one-click setup.

`C` `Cyclone DDS` `OpenGL` `Threads` · 🎬 [Demo](YOUR-LINK)

</td>
<td width="50%" valign="top">

#### 📅 Exam Revision Timeline
<sub>App built solo · Data Structures · 2026</sub>

A raw Win32 desktop planner. Exams live in a **binary search tree** keyed by start time, the app catches clashing exam times, and a lower-bound search finds your next exam without scanning every record.

`C++` `Win32` `BST` `GDI` · 📁 [Repo](https://github.com/R15hika/ExamTimelineC-Version)

</td>
</tr>
</table>

<br/>

<img src="./h-toolkit.svg" alt="Toolkit" width="100%"/>

<p>
<img src="https://img.shields.io/badge/C-2d1046?style=flat-square&logo=c&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/C++-2d1046?style=flat-square&logo=cplusplus&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/C%23-2d1046?style=flat-square&logo=dotnet&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Python-2d1046?style=flat-square&logo=python&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/OpenGL-2d1046?style=flat-square&logo=opengl&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/GLSL-2d1046?style=flat-square&logo=opengl&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Unity-2d1046?style=flat-square&logo=unity&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/FastAPI-2d1046?style=flat-square&logo=fastapi&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/SQLite-2d1046?style=flat-square&logo=sqlite&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/MongoDB-2d1046?style=flat-square&logo=mongodb&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/CMake-2d1046?style=flat-square&logo=cmake&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Git-2d1046?style=flat-square&logo=git&logoColor=ff8fd0"/>
</p>

<br/>

<img src="./h-journey.svg" alt="Metamorphosis" width="100%"/>

| | When | What I learned to build |
|:-:|:--|:--|
| 🥚 | May 2025 | A 3D pipeline by hand: what the GPU does for you |
| 🐛 | Sep 2025 | Engine systems other programmers build on (Luminara Zoo) |
| 🍃 | Feb 2026 | Choosing the right data structure (Exam Timeline) |
| 🌸 | Mar 2026 | Server-authoritative multiplayer over UDP (Sudoku Rush) |
| 🦋 | Sep 2026 | Full-stack simulation on real city data (Formula 9) |
| ✨ | Nov 2026 | Secure, encrypted networking in C, as team lead (Gingerbread Curse) |

<div align="center">
<br/>
<sub>Made with ♡ by Rishika</sub>
</div>
