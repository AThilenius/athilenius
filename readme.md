# Hello 👋 I'm Alec Thilenius!

## 🔎 `let intro = match (interests, repos) {`

_Interests and public repos_

- 🔑 Distributed systems, networking and zero-trust infra
  - [Maglev](https://maglev.wlabs.dev/docs/) ([src](https://gitlab.com/tungstenlabs/maglev)) Founded startup product; web-first p2p networking, zero-trust relays
  - [Axum-Connect](https://github.com/AThilenius/axum-connect) Rust server-side impl for [Connect-Web](https://connectrpc.com/docs/web/getting-started/)
- 🦀 `Rust`, since 2018
  - [Logic-Paint](https://github.com/AThilenius/logic-paint-rs) See below; my favorite personal project!
  - [Axum-Connect](https://github.com/AThilenius/axum-connect) Lots of meta-programming
- 🌐 Modern web tech (`WASM`, `WebRTC`, `WebGL`, `WebGPU`, `SharedArrayBuffer-multithreading`)
  - [Logic-Paint](https://github.com/AThilenius/logic-paint-rs) Compiled to `WASM`, `WebGL` (soon to be `WebGPU`), multi-threading via `SharedArrayBuffer` and `WebWorkers`
  - [Maglev](https://maglev.wlabs.dev/docs/) ([src](https://gitlab.com/tungstenlabs/maglev)) Based on `WebRTC` (with a `Websocket` fallback), `WebCrypto`
  - [Simple Web Workers](https://github.com/AThilenius/simple-webworker-actors) `ES Proxy` and `WebWorker` based mutlithreaded actor framework
- 🕹️ Hardware accelerated rendering / game engines (`OpenGL`/`ES`, `Vulkan`, `WebGPU`).
  - [Logic-Paint](https://github.com/AThilenius/logic-paint-rs) Rendered in constant-time via pixel shader
  - [Voxmod](https://github.com/AThilenius/voxmod) For-fun game engine mostly in `C#`, with the start of a transition to Rust
  - [Filament-rs](https://github.com/AThilenius/filament-rs) Idiomatic Rust bindings for [Google Filament](https://github.com/google/filament)
  - [Legion Transform](https://github.com/amethyst/legion_transform) ECS based space-transformation hierarchies
    - _Originally authored by me, adopted by [Amethyst](https://github.com/amethyst/amethyst), inspired early [Bevy Transform](https://github.com/bevyengine/bevy/tree/main/crates/bevy_transform)_
  - [VoxelCraft](https://github.com/AThilenius/VoxelCraft) One of my first ever projects, game engine written in `C++`, embedded `C#` scripting runtime via `mono`
- 💾 Embedded systems
  - Some work at Google in this space, and a ton of personal projects
  - Used: `Arduino`, `arm` `ESP8266/32` `RP2040`, [Embassy](https://embassy.dev/), [Saleae L/A](https://www.saleae.com/) `i2c`, `spi`, `can`, `uart`, and so on
- 🗣️ Languages _(most recently used first)_
  - Rust, TypeScript, NuShell, SQL, Ruby, C#, Python, Go, GLSL, C/C++, Java, ObjectiveC

## 🏢 `SELECT * FROM "career" ORDER BY "date" DESC`

_Career and Education_

- [WoodRiver Energy LLC](https://www.woodriverenergy.com/) Director of Technology (2022 - Present)
  - Direct the company-wide tech strategy and set priorities
  - Manage our growing tech team and mentor junior developers
  - Large back-office application efforts (React, Typescript, Rust, Hasura, PSQL, Nu, Ruby)
  - Public facing presence (Webflow, Vue, Typescript, Hasura)
  - Significant infra efforts (Proxmox, Dokku, Cloudflare, Tailscale, et. al)
- [Tungsten Labs](https://maglev.wlabs.dev/docs/) Co-founder (2021-2022)
  - Worked on [Maglev](https://maglev.wlabs.dev/docs/), a peer-to-peer networking and RPC library focused on web-first (Typescript, Go)
  - Completed a working alpha but opportunities in life pulled both my partner and I away from it
- [Sublink](https://www.sunblink.com/) FTE (2019-2020)
  - Worked on [Heroish](https://store.steampowered.com/app/1876350/HEROish/) in [Unity DOTs](https://unity.com/dots) (C#)
  - Also the 'miscellaneous' implementer, of things outside game code (Typescript)
- [Google](https://chromium-review.googlesource.com/q/author:athilenius) FTE (2017-2019, 2015, 2014)
  - ChromeOS (FTE)
    - Embedded device firmware, running on the EC (C, RTOS)
    - Infrastructure transition for ChromeOS build/test fleet (Python, Go)
  - College internships (2)
    - Hardware accelerated rendering of [Google Maps](https://www.google.com/maps) desktop (Closure JS, GLSL)
    - Monitoring for (what became) [Dataflow](https://cloud.google.com/dataflow/docs/overview) (C++)
- [Blank Slate Systems](https://www.youtube.com/@Blankslatesystems) FTE (2013)
  - iOS systems design, hardware accelerated rendering (ObjectiveC, C#, Xamarin)
- [University of Colorado Boulder](https://www.colorado.edu/) Student (2012-2016)
  - Bachelors Degree in Computer Science
- [Intel](https://www.intel.com/) Intern (2006-2011)
  - College internships (3), high school internships (2)
  - Created and populated MOLAP cubes (data analytics)

## 🏡 `ls /etc`

_Non-technical Interest / Also Me_

- 🌞 Live in San Diego
- 💍 My wonderful wife, who is my rock
- 👶 Our beautiful baby boy, that lights up my world
- 🛩️ Flying! Currently building an [RV-14](https://www.vansaircraft.com/rv-14/) in my garage.
- 🧗 Rock climbing
- 😁 Emojis (though I don't normally go this overboard)

## 🖥️ `curl 172.0.0.1`

_Nerd alert, NERD ALERT!!_

- 📀 OS: [NixOS](https://nixos.org/), [i3 WM](https://i3wm.org/)
- 📄 Editor: [NeoVim](https://neovim.io/),
- 🌳 VCS: [Jujitsu](https://github.com/jj-vcs/jj) (backed by `git`), [LazyGit](https://github.com/jesseduffield/lazygit)
- 🛠️ Shell: [NuShell](https://www.nushell.sh/)
- ⌨️ Keyboard: [Chocofi 36-key split](https://github.com/pashutk/chocofi)

---

## ❤️ `open my-projects.toml | sort-by -r interest | take 1`

_My favorite personal project!_

https://github.com/AThilenius/logic-paint-rs

- Based on a game by Zachtronics called [KOHCTPYKTOP](https://www.zachtronics.com/kohctpyktop-engineer-of-the-people/), which sadly isn't playable any more because it's a flash game
- Written in Rust (because of course it is)
- Compiled to WASM
- Uses WebGL2 for fixed-cost (by pixels) hardware accelerated rendering
  - Each 'cell' is a single 16 bit unsigned texel and rendered entirely in a fragment shader.
- Lets you edit and simulate transistors (something between BJT and CMOS, for you hardware people)

Once I finished with the editor I then built a functional 16 bit CPU in it, modeled after the [CL-3B ISA](http://users.ece.utexas.edu/~patt/05f.360N/handouts/360n.appC.pdf). It's micro-coded with a common 16-bit bus, 8 registers with dual output and a 16K of RAM (not drawn here).

![CPU](https://github.com/AThilenius/logic-paint-rs/blob/main/misc/screenshots/logic-paint-cpu.png?raw=true)

I love this project dearly, because it requires knowledge of how a computer works all the way from the transistor up to WASM running in Chromium. Next up is a toy language with a homemade compiler for it 😊 Have to rewrite my parser-generator first though!
