# Hello! 👋

## ⚠️ **Recruiters** ⚠️

I'm very happily employed and not looking for a job, sorry.

---

I'm Alec, I live in San Diego. I'm an adrenaline junkie software engineer.

- Coding 🖥️
- Flying airplanes and aerobatics 🛩️
- Rock climbing 🧗‍♂️
- Skiing ⛷️
- My adorable dog Ada (yes, named after Ada Lovelace) 🐶

I've been all over the software stack, working on ChromeOS (low level firmware,
and high level CI systems) at Google, games at Sunblink, and web stacks all over
the place. I have a passion for GPUs, hardware and bare-metal software, and
cutting edge web tech (WASM, WebRTC and WebGPU).

In 2021 I founded Tungsten Labs with my tech lead back from Google, we created
[Maglev](https://gitlab.com/tungstenlabs/maglev), a peer-to-peer RPC framework
built on WebRTC. I'm still very passionate about that project, but it's on hold
for now.

## Projects

My favorite personal project is https://github.com/AThilenius/logic-paint-rs
It is:

- Based on a game by Zachtronics called
  [KOHCTPYKTOP](https://www.zachtronics.com/kohctpyktop-engineer-of-the-people/),
  which sadly isn't playable any more because it's a flash game
- Written in Rust (because I'm obsessed with Rust)
- Compiled to WASM
- Uses WebGPU for fixed-cost hardware accelerated rendering
- Lets you edit and simulate transistors (something between BJT and CMOS, for you hardware people)

Once I finished with the editor I then built a functional 16 bit CPU in it,
modeled after the [CL-3B
micro-architecture](http://users.ece.utexas.edu/~patt/05f.360N/handouts/360n.appC.pdf).
It's micro-coded with a common 16-bit bus, 8 registers with dual output and a
16K of RAM (not drawn here).

![CPU](https://github.com/AThilenius/logic-paint-rs/blob/main/misc/screenshots/logic-paint-cpu.png?raw=true)

I love this project dearly, because it requires knowledge of how a computer
works all the way from the transistor up to WASM running in Chromium (which is
what VSCode is build with). Next up is a toy language with a homemade compiler
for it 😊 Have to rewrite my parser-generator first though!
