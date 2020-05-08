# FreeCADbuildDocker
Docker to build FreeCAD on openSUSE Tumbleweed using OCCT rather than OCE

Simple stuff. Make the docker image by running `requires` inside a docker shell with `rootShell`

Then when it's all built. `docker container commit freecad-build freecad-build` that container. Next, run `buildShell` to get a regular user shell in the container, and now do your normal FreeCAD build.
