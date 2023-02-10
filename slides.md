---
theme: gaia
_class: lead
paginate: true
backgroundColor: #EeEeFf
marp: true
---

# Web Assembly

---
# The web as we know it
![bg 50%](js.png)
![bg 50%](css.png)
![bg 50%](html.png)

---

# We have gone far... but at what cost

> Any application that can be written in JavaScript, will eventually be written in JavaScript.

*- Jeff Atwood*

---

# Designed for
- Basic interactivity to complement existing functionality

# Used for

<style>
    .test{
        display:flex;
    }
</style>


- Complex SPA's
- Video Games
- Multi-Media Editors
- IDE's
- Server side code


---

# Domain Specific Languages

- Match the level of abstraction a problem requires.
- Allow more expressive solutions to specific problems.

<!-- Being able to take advantage of a specialized language is something that up until recently the web has lacked -->

---

![bg 70%](https://webassembly.org/css/webassembly.svg)

---

# WASM

- Developed by Mozilla
- Supported by most major browsers
- Simple stack based virtual machine
- Small binary format 
- Can be run on server (wasmtime)

---

![bg 90%](languages/cpp.png)
![bg 90%](languages/c.png)
![bg 90%](languages/go.png)
![bg 90%](languages/lua.svg)
![bg 90%](languages/rust.png)
![bg 90%](languages/zig.png)

---

# Real World Use

 - Lichess
 - wasm-flate
 - Squoosh
 - Figma
 - Doom 3
 - And many more...

---
# References

- https://webassembly.org/
- https://madewithwebassembly.com/
- https://en.wikipedia.org/wiki/Jeff_Atwood#:~:text=In%202007%2C%20Jeff%20Atwood%20made,eventually%20be%20written%20in%20JavaScript.%E2%80%9D
- https://caniuse.com/?search=wasm