Multiarch Build
===============

The notes-buildah directory contains a shell script with the 'multi' filename. This script is shamelessly copied from a presentation by Nalin Dahyabhai, RedHat, at DevConf.CZ:2020 (https://www.youtube.com/watch?v=SYJgkkjqd7s). This is my first attempt at usingt buildah to build doh-client containers for both amd64 and arm64 in a single script. This is strictly experimental (26 July 2020) and clearly needs some optimization, if not outright correction.

Be sure to update the version tag in the multi script file

## Usage
1. Authenticate with the repository (e.g. 'buildah login docker.io'.
2. Run script from reposity root (for correct path resolution).


buildah manifest create and buildah manifest push
