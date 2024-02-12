# Trilateral Vector Graphics (TVG)
This is a test version of the TVG parser, our plan is to simplify how 3D graphics are made and this is the first step to achieving such goal. Please be sure to read the `LICENSE` file before using, or modifying this module.

```
npm install tvg-parser
```

## Research
We plan on changing the way low poly 3D graphics are stored. 3D graphics files such as `.obj` files are stored as polygons or to be more specific a mesh of verticies.

These take up a lot of disk space and are a primary factor in download size and in turn download speeds with games. This also affects things such as render time, as computers have to render individual polygons instead of rendering one whole object at once.

We're working on so much more than just saving space on your computer, we're lowering production time in games and movies, and we're raising performance for games. This is the initial version of `.tvg` files and its parser. Please remember that this file type is still in it's early stages of development and even prototyping so there will most likely be changes made to the format of this file type.

## Documentation
As these file types are in their early stages, we haven't provided proper tests to document anything. We'll update the module along with the README file for more information. 

#### [Vector3D coming early 2025](https://softsync.org/Vector3D)
#### [© SoftSync Digital, 2024](https://softsync.org/)
