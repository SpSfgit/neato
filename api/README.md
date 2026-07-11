# NEATO API

Application environment related specifications.

So basically, the NEATO API is the default _G, events and handlers of the normal Neetcomputers API, with changes and additions defined by the specifications.

This *doesn't* mean that the API has to behave exactly the same as the normal Neetcomputers API, or that it can't have additions from the OS developer, but rather that the expected parameters and return types are the same across all OSes.

For example, in a GUI based operating system based on applications that each get their own window, the OS could modify the behavior of the mouse event to be offset by the window's position, and the graphics API to use a specific layer for the window, rather than the main global layer.

Basically, you can modify the behavior of certain things, but it has to be in a way that preserves compatibility.

### Changes to the default API:

*Note: get started writing specs for changes to the default API.*

### Additions to the default API:

- [Terminal emulation (term.md)](term.md) - Extra functions for a standardized terminal emulator.
- [System info (sys.md)](sys.md) - Provides system information to check for OS name, version, and NEATO compatibility.