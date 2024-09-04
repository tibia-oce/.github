<h1><img src="https://github.com/mehah/otclient/blob/main/data/images/clienticon.png?raw=true" width="32" alt="logo"/> OTClient - Redemption</h1>

[![Discord Shield](https://discordapp.com/api/guilds/888062548082061433/widget.png?style=shield)](https://discord.gg/HZN8yJJSyC)
[![Build - Ubuntu](https://github.com/mehah/otclient/actions/workflows/build-ubuntu.yml/badge.svg)](https://github.com/mehah/otclient/actions/workflows/build-ubuntu.yml)
[![Build - Windows](https://github.com/mehah/otclient/actions/workflows/build-windows.yml/badge.svg)](https://github.com/mehah/otclient/actions/workflows/build-windows.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## 📋 Table of Contents

1. ![Logo](https://raw.githubusercontent.com/mehah/otclient/main/src/otcicon.ico)  [What is otclient?](#whatisotclient)
1. 🚀 [Features](#features)
1. <img height="16" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/android/android.png" alt="Android"> [The Mobile Project](#themobileproject)
1. 🔨 [Compiling](#compiling)
1. 🩺 [Need help?](#need-help?)
1. 📑 [Bugs?](#bugs)
1. ❤️  [Roadmap](#roadmap)
## <a name="whatisotclient">![Logo](https://raw.githubusercontent.com/mehah/otclient/main/src/otcicon.ico)  What is otclient?</a>

Otclient is an alternative Tibia client for usage with otserv. It aims to be complete and flexible, for that it uses LUA scripting for all game interface functionality and configurations files with a syntax similar to CSS for the client interface design. Otclient works with a modular system, this means that each functionality is a separated module, giving the possibility to users modify and customize anything easily. Users can also create new mods and extend game interface for their own purposes. Otclient is written in C++20 and heavily scripted in lua.

## <a name="features">🚀 Features</a>
Beyond of it's flexibility with scripts, otclient comes with tons of other features that make possible the creation of new client side stuff in otserv that was not possible before. These include, sound system, graphics effects with shaders, modules/addons system, animated textures, styleable user interface, transparency, multi language, in game lua terminal, an OpenGL 2.0 ES engine that make possible to port to mobile platforms. Otclient is also flexible enough to create tibia tools like map editors just using scripts, because it wasn't designed to be just a client, instead otclient was designed to be a combination of a framework and tibia APIs.

| <img src="https://github.com/kokekanon/OTredemption-Picture-NODELETE/blob/main/Picture/Attached%20Effect/Creature/001_Bone.gif?raw=true" width="200" alt="Haskanoid Video" style="max-width:200px;"> | <img src="https://github.com/kokekanon/OTredemption-Picture-NODELETE/blob/main/Picture/Attached%20Effect/Creature/002_aura.gif?raw=true" width="200" alt="Peoplemon by Alex Stuart" style="max-width: 200px;"> | <img src="https://github.com/kokekanon/OTredemption-Picture-NODELETE/blob/main/Picture/Attached%20Effect/Creature/003_particula.gif?raw=true" width="250" alt="Space Invaders" style="max-width: 250px;"> |
|-------------------------------------------|---------------|-------------------------|
| Creature Attached Effect | Light Attached Effect | Creature Particule |
