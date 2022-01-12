# Overview
neon is a 2D hardware accelerated rendering library with a focus on application development.
It's part of a larger application development framework called [alloy](https://github.com/Folling/alloy).
neon is part of a larger application development framework called [alloy](https://github.com/Folling/alloy).

This document is a WIP and will be expanded upon as the project progresses.

# Supported APIs
- [ ] OpenGL
- [ ] Vulkan
- [ ] DirectX
- [ ] Metal

This library has existed in multiple forms before. Two C++ versions and one previous rust version. 
You can find these projects (in ascending order of the creation date):
- [Original C++ version](https://memleak.eu/Folling/graphite)
- [Original Rust version](https://memleak.eu/Folling/graphite-rs)
- [Second C++ iteration](https://memleak.eu/Folling/graphite-CPP-v2)

# Features
- [ ] Basic shape rendering (lines, triangles, rects, circles, etc.)
- [ ] Complex shapes (bezier curves, bordered rects, etc.)
- [ ] Simple gradients
- [ ] image rendering
- [ ] text rendering 
- [ ] GIF rendering

# Goals
Given that neon is supposed to be used in applications for endusers a lot of functionality is considered redundant.
This includes, but isn't limited to:
- path-based rendering
- complex gradients
- shader-effects
- SVG rendering

Of course as development progresses these might be considered more useful. The point is merely that they aren't considered
when designing neon's API.

# Contributing
alloy is open source and is supposed to benefit from the inclusion of other people. 
However I do reserve the rights to deny any feature requests or pull requests but am always open to discussion and having my mind changed. 
If you're uncertain whether or not a certain pull request would be appreciated and don't want to waste effort without knowing whether it's worth it, feel free to open an issue and ask. 
All code should be formatted using the same guideline. For this please use rustfmt. In the future a customised rustfmt stylisation might be used.
File and directory names are are to be formatted using snake_case. Excluded from this rule are files that have a certain convention such as .gitignore, LICENCE.txt and markdown files.

# Support
I have a fulltime job and can only afford so much time for alloy. If you would like to change that in the future consider donating to the project (note: Donating link will follow, alloy isn't worth donating yet). I also appreciate feedback (next to constructive criticism) so feel free to email me at coding@folling.de. 

# Naming
Neon is often used as an element in neon signs or other visually impressive objects. (Impressive meant in the literal sense of leaving an impression).
Hence it was chosen as the name for the rendering library which is also visually impressive.
