<div align="center">

<img src="./banner.svg" alt="Rishika Bimal Attodi: Graphics, Real-Time Systems, Interactive Software" width="100%"/>

<br/>

<a href="https://r15hika.github.io/RishikaBimalAttodiPortfolio/"><img src="./btn-portfolio.svg" alt="Portfolio" height="52"/></a>
<a href="https://www.linkedin.com/in/rishika-dice/"><img src="./btn-linkedin.svg" alt="LinkedIn" height="52"/></a>
<a href="https://www.youtube.com/@RishBiA"><img src="./btn-youtube.svg" alt="Demo videos on YouTube" height="52"/></a>
<a href="mailto:rishikabimal@gmail.com"><img src="./btn-email.svg" alt="Email" height="52"/></a>

</div>

<img src="./divider.svg" width="100%"/>

<img src="./h-about.svg" alt="About me" width="100%"/>

I build software that turns **real-world data** into something people can use: data pipelines and APIs, the databases behind multiplayer games, and real-time C/C++ for graphics and engines.
Next, I want to bring that into **data and business analysis**: taking raw data, structuring it, and turning it into answers.

<table>
<tr>
<td width="130" nowrap>🌸&nbsp;<b>Now</b></td>
<td>Visualisation &amp; Integration Lead on <b>Formula 9</b>, an autonomous shuttle fleet simulator (9-person team)</td>
</tr>
<tr>
<td width="130" nowrap>🎓&nbsp;<b>Studying</b></td>
<td>B.Sc. Computer Science in Real-Time Interactive Simulation, <b>SIT-DigiPen Singapore</b></td>
</tr>
<tr>
<td width="130" nowrap>✨&nbsp;<b>Strengths</b></td>
<td>Data pipelines &amp; REST APIs · database design (SQLite, MongoDB) · data modelling · Python, C/C++</td>
</tr>
<tr>
<td width="130" nowrap>💌&nbsp;<b>Open&nbsp;to</b></td>
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

`Unity 6` `C#` `Python` `FastAPI` `JSON Schema` `pytest` `ShaderLab` `Procedural textures` `OpenStreetMap`

<br/>

#### 🦉 Luminara Zoo
<sub><b>8-person team (NocturnalStudios)</b> · Graphics Champion · Sep 2025 to Apr 2026</sub>

A night-shift point-and-click game where you keep four zoo animals fed, healthy and sane until 6 am. I built the rendering core of our own **custom C++ / OpenGL engine** across six milestones, as primary author of 12 engine files.

<img src="./stats-luminara.svg" alt="168 commits · ~2,800 lines of engine code · 22 scenes" width="480"/>

- **Engine setup:** built the engine from scratch, integrating 6 libraries (GLFW, GLEW, GLM, ImGui, STB, RapidJSON) into a CMake build that separates Engine and Game, with a one-click script so all 8 teammates could build it.
- **Renderer:** wrote the renderer, sprite rendering, shader, buffer and framebuffer classes and a 2D camera with zoom, plus a layering system with drag-to-reorder in the ImGui editor.
- **Particles &amp; VFX:** a JSON-driven particle and screen-effect system with 5 GLSL shaders (floating particles, falling leaves, water, static camera), each toggled per scene in the editor without code changes.
- **Shipping:** a Windows installer and uninstaller (Inno Setup) that bundles the release and its assets, refined over 3 versions until it installed cleanly on school lab PCs.

`C++` `OpenGL` `GLSL` `ECS` `ImGui` `RapidJSON` `CMake` `Inno Setup`

<br/>

<img src="./projects.svg" alt="More projects: Multiplayer Sudoku Rush (C++, SQLite database design), The Gingerbread Curse (C, MongoDB accounts, encrypted networking), Exam Revision Timeline (C++, BST data model), 3D Software Rasterizer (C++, CPU rendering)" width="100%"/>

<br/>

<img src="./h-toolkit.svg" alt="Toolkit" width="100%"/>

<p>
<img src="https://img.shields.io/badge/C-2d1046?style=flat-square&logo=c&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/C++-2d1046?style=flat-square&logo=cplusplus&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/C%23-2d1046?style=flat-square&logo=dotnet&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Python-2d1046?style=flat-square&logo=python&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/OpenGL-2d1046?style=flat-square&logo=opengl&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/GLSL-2d1046?style=flat-square&logo=opengl&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Power_BI-2d1046?style=flat-square&logo=powerbi&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Unity-2d1046?style=flat-square&logo=unity&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/FastAPI-2d1046?style=flat-square&logo=fastapi&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/SQLite-2d1046?style=flat-square&logo=sqlite&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/MongoDB-2d1046?style=flat-square&logo=mongodb&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/UiPath-2d1046?style=flat-square&logo=uipath&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/CMake-2d1046?style=flat-square&logo=cmake&logoColor=ff8fd0"/>
<img src="https://img.shields.io/badge/Git-2d1046?style=flat-square&logo=git&logoColor=ff8fd0"/>
</p>

<br/>

<img src="./h-journey.svg" alt="Metamorphosis" width="100%"/>

| | When | What I learned to build |
|:-:|:--|:--|
| 🦋 | Nov 2026 | Secure MongoDB accounts, as team lead (Gingerbread Curse) |
| ✨ | Sep 2026 | Data pipelines and APIs on real city data (Formula 9) |
| 🌸 | Mar 2026 | Designing a SQLite database for match history and stats (Sudoku Rush) |
| 🍃 | Feb 2026 | Modelling data so it stays sorted and searchable (Exam Timeline) |
| 🐛 | Sep 2025 | JSON-driven engine systems other programmers build on (Luminara Zoo) |
| 🥚 | May 2025 | A 3D pipeline by hand: what the GPU does for you |

<div align="center">
<br/>
<sub>Made with ♡ by Rishika</sub>
</div>
