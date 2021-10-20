# gsnodegraph

Custom node graph widget for wxPython, created to be used in [Gimel Studio](https://github.com/GimelStudio/GimelStudio).

It is specifically aimed towards an image-editing node graph setup and has styling specific to Gimel Studio, but it can be adapted for other node graph use-cases.

**NOT YET READY FOR PRODUCTION!**

Highly inspired by the look of Blender's nodes (with adjustments), if you couldn't tell. ;)


# Usage

Simply ```pip install gsnodegraph``` and run the ```main.py``` to see the WIP nodegraph demo. The ``nodes.py`` file in the ``nodes`` folder gives a demo of how to setup nodes to work with the nodegraph.


# Status & Roadmap

Currently, the basic node graph interaction is working, but it's *not production-ready* quite yet!

**Roadmap**

- [x] Zoom/pan canvas
- [x] Basic node drag n' drop
- [x] Box selection
- [x] Multi-selection
- [x] Sockets and wires
- [x] Parameters
- [ ] Support image thumbnails with expand and collapse functionality
- [x] Implement node delete, duplicate and mute
- [ ] Keyboard shortcuts
- [ ] Configuration settings
- [ ] Cleanup + bug testing
- [ ] Lock zoom to a predefined range
- [x] Make PYPI package


**Extra possiblities**

- [ ] Nodegraph minimap?
- [ ] Image as background?


# Contributing

All contributions are welcome! Feel free to open a PR or ask questions.
