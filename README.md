<div align="center"> <img src="./assets/banner.svg" alt="Rishika Bimal Attodi: Graphics, Real-Time Systems, Interactive Software" width="100%"/> <br/>

<a href="https://YOUR-PORTFOLIO-URL"><img src="https://img.shields.io/badge/Portfolio-ff5fb4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a> <a href="https://www.linkedin.com/in/rishikaba"><img src="https://img.shields.io/badge/LinkedIn-9d4dff?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="https://www.youtube.com/@RishBiA"><img src="https://img.shields.io/badge/Demo_Videos-c94dff?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/></a> <a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-6b2bbf?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div> <img src="./assets/divider.svg" width="100%"/>
🦋  About me

I build real-time software in C and C++: renderers, engine systems and networked games, mostly from scratch. I've written a 3D rasterizer that draws every pixel on the CPU, been Graphics Champion on a custom OpenGL engine, and right now I'm turning real Singapore streets into a 3D training simulator for autonomous shuttles.

<table> <tr> <td>🌸 <b>Now</b></td> <td>Visualisation &amp; Integration Lead on <b>Formula 9</b>, an autonomous shuttle fleet simulator (9-person team)</td> </tr> <tr> <td>🎓 <b>Studying</b></td> <td>B.Sc. Computer Science in Real-Time Interactive Simulation, <b>SIT-DigiPen Singapore</b></td> </tr> <tr> <td>✨ <b>Most at home in</b></td> <td>Rendering, engine systems, server-authoritative networking</td> </tr> <tr> <td>💌 <b>Open to</b></td> <td>Internships in graphics, simulation and real-time systems</td> </tr> </table> <img src="./assets/divider.svg" width="100%"/>
🌷  Featured work
🚐 Formula 9: Autonomous Shuttle Fleet Training Simulator

<sub><b>9-person multidisciplinary team</b> · Visualisation & Integration Lead · Sep 2026 to present</sub>

A 3D simulator that trains autonomous-shuttle fleet managers on Toa Payoh's real streets: plan detours, handle incidents and manage charging, then watch the fleet drive it out in 3D.

<table> <tr> <td align="center"><b>~74k</b><br/><sub>lines migrated Qt → Unity</sub></td> <td align="center"><b>Real map</b><br/><sub>OpenStreetMap + LTA data</sub></td> <td align="center"><b>Full stack</b><br/><sub>Unity UI ↔ FastAPI backend</sub></td> </tr> </table>
Engine migration: led the move from C++/Qt to Unity, porting the backend, shared data formats and tools into one project for the whole team.
3D city: extruded Toa Payoh's real OpenStreetMap building footprints into textured 3D buildings with procedural meshes and custom shaders.
Charging, end to end: data contracts, FastAPI booking services and Unity UI for charger bookings and return-to-route, with tests. Also fixed a charging deadlock in the backend.
Real-world data: imported LTA traffic-light, crossing and road-marking data and served it through new API endpoints.

Unity 6 C# Python FastAPI MongoDB UI Toolkit ShaderLab OpenStreetMap · 🎬 Demo video · 🔒 private team repo

<br/>
🦉 Luminara Zoo

<sub><b>8-person team (NocturnalStudios)</b> · Graphics Champion · Sep 2025 to Apr 2026</sub>

A night-shift point-and-click game where you keep four zoo animals fed, healthy and sane until 6 am. It runs on our own custom C++ / OpenGL engine with an ECS and an ImGui level editor, and shipped across six milestones.

Rendering: sprites with GLM transforms, prefab/JSON-driven rendering and the 2D camera.
VFX: particle system and scene-level effects (fireflies, falling leaves, water, film grain).
Layering system shared by graphics, logic, physics and collision, with drag-to-reorder in the editor.
Engine setup: project scaffolding, CMake build pipeline and the Windows installer.

C++ OpenGL ECS ImGui RapidJSON CMake · 🎬 Demo video · 📁 Repo

<br/> <table> <tr> <td width="50%" valign="top">
🔺 3D Software Rasterizer

<sub>Solo · Computer Graphics · 2025</sub>

An OpenGL-style pipeline written by hand in C++, with every pixel drawn on the CPU: barycentric rasterization, a depth buffer, perspective-correct texturing, frustum culling and Sutherland–Hodgman clipping. It renders about 60 lit objects with shadows.

C++ Rasterization Clipping · 🎬 Demo

</td> <td width="50%" valign="top">
🧩 Multiplayer Sudoku Rush

<sub>2-person team · Backend & gameplay · 2026</sub>

A real-time Sudoku race for 2–3 players over UDP with a custom reliability layer. The server validates every move and decides who claimed each cell first. It also has rooms, a live leaderboard and SQLite match history.

C++ UDP SQLite Win32 · 📁 Repo

</td> </tr> <tr> <td width="50%" valign="top">
🍪 The Gingerbread Curse

<sub>3-person team · Team lead · Nov 2026</sub>

A 2-player co-op potion game in C over encrypted Cyclone DDS, where the host enforces the rules. I built salted PBKDF2 accounts on a separate auth thread, DDS Security, rejoin, and one-click setup.

C Cyclone DDS OpenGL Threads · 🎬 Demo

</td> <td width="50%" valign="top">
📅 Exam Revision Timeline

<sub>App built solo · Data Structures · 2026</sub>

A raw Win32 desktop planner. Exams live in a binary search tree keyed by start time, the app catches clashing exam times, and a lower-bound search finds your next exam without scanning every record.

C++ Win32 BST GDI · 📁 Repo

</td> </tr> </table> <img src="./assets/divider.svg" width="100%"/>
🪻  Toolkit
<p> <img src="https://img.shields.io/badge/C-2d1046?style=flat-square&logo=c&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/C++-2d1046?style=flat-square&logo=cplusplus&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/C%23-2d1046?style=flat-square&logo=dotnet&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/Python-2d1046?style=flat-square&logo=python&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/OpenGL-2d1046?style=flat-square&logo=opengl&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/GLSL-2d1046?style=flat-square&logo=opengl&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/Unity-2d1046?style=flat-square&logo=unity&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/FastAPI-2d1046?style=flat-square&logo=fastapi&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/SQLite-2d1046?style=flat-square&logo=sqlite&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/MongoDB-2d1046?style=flat-square&logo=mongodb&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/CMake-2d1046?style=flat-square&logo=cmake&logoColor=ff8fd0"/> <img src="https://img.shields.io/badge/Git-2d1046?style=flat-square&logo=git&logoColor=ff8fd0"/> </p> <img src="./assets/divider.svg" width="100%"/>
🐛 → 🦋  Metamorphosis
	When	What I learned to build
🥚	May 2025	A 3D pipeline by hand: what the GPU does for you
🐛	Sep 2025	Engine systems other programmers build on (Luminara Zoo)
🍃	Feb 2026	Choosing the right data structure (Exam Timeline)
🌸	Mar 2026	Server-authoritative multiplayer over UDP (Sudoku Rush)
🦋	Sep 2026	Full-stack simulation on real city data (Formula 9)
✨	Nov 2026	Secure, encrypted networking in C, as team lead (Gingerbread Curse)
<div align="center"> <br/> <sub>Made with ♡ by Rishika</sub> </div>
