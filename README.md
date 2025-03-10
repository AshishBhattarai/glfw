# GLFW packaged for the Zig build system

This is a fork of [glfw](https://github.com/glfw/glfw), packaged for Zig. Unnecessary files have been deleted, and the build system has been replaced with build.zig.

_Looking for Zig bindings to GLFW?_ See [mach-glfw](https://github.com/AshishBhattarai/mach-glfw).

## Updating

To update this repository, run `./update.sh` followed by `./verify.sh` to verify the repository contents.

## Verifying repository contents

For supply chain security reasons (e.g. to confirm we made no patches to the code) we provide a `git diff` command you can run to verify the contents of this repository:

```sh
./verify.sh
```

If nothing is printed, there is no diff. Deleted files, and changes to `README.md`, `build.zig`, `.github` CI files and `.gitignore` are ignored.

## Credits

This repository is a fork of the now-discontinued [GLFW fork by thedeadtellnotales](https://github.com/thedeadtellnotales/glfw).
