# World Editor

## Screenshots

![Flat Terrain](/docs/images/screenshot-1.png?raw=true)

![Heightmap Import](/docs/images/screenshot-2.png?raw=true)

![Script Editor](/docs/images/screenshot-3.png?raw=true)

## External Dependencies

You must run the configure script in the project root to
install dependencies and build shared libraries before
you can run the editor. The current development build
does not use system wide libraries and relies on rpath
to handle paths. This may cause problems when moving
the directory later on. Release builds should use the
system wide versions when possible.
