# Contributors

The following external contributors have changes incorporated into the current `sprite-gen` codebase.

## [@devswha](https://github.com/devswha)

- [PR #1](https://github.com/aldegad/sprite-gen/pull/1): protected subject colors during chroma cleanup and improved automatic key selection.

## [@bokjk](https://github.com/bokjk)

- [PR #2](https://github.com/aldegad/sprite-gen/pull/2): made machine-readable manifest paths use portable POSIX separators. The accepted change was ported into the reorganized package implementation.

## [@Dongkyu-ES](https://github.com/Dongkyu-ES)

- [PR #4](https://github.com/aldegad/sprite-gen/pull/4): made CLI help tests deterministic in colored shell environments.
- [PR #5](https://github.com/aldegad/sprite-gen/pull/5): added Aseprite JSON, Phaser-compatible, and Flame-compatible exports.
- [PR #6](https://github.com/aldegad/sprite-gen/pull/6): introduced character and effect subject profiles. The accepted implementation uses resolution-aware sparse-frame floors.

## [@napkn34](https://github.com/napkn34)

- [PR #7](https://github.com/aldegad/sprite-gen/pull/7): fixed Windows provider CLI resolution and UTF-8 subprocess I/O.
- [PR #9](https://github.com/aldegad/sprite-gen/pull/9): added the Windows `LockFileEx` backend for shared readers and exclusive publishers.

## [@monibu1548](https://github.com/monibu1548)

- [PR #11](https://github.com/aldegad/sprite-gen/pull/11): made vertical centering work in the pixel-unfake row-placement path and exposed per-frame vertical grounding through the CLI.

Thank you for testing the project in real environments, documenting the failures clearly, and contributing fixes that now ship as part of `sprite-gen`.
