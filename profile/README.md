# SfM Tool

Tools for creating and exploring Structure from Motion (SfM) reconstructions:
camera poses and 3D points solved from a set of photos.

- **`sfm` CLI**: set up a workspace, extract and match features, solve
  (incremental or global, through COLMAP), and inspect, transform, align and
  merge reconstructions.
- **SfM Explorer**: a desktop viewer for reconstructions, their point tracks
  and camera rays. It can host an MCP endpoint, so an agent can read the scene,
  move the camera and selection, and take screenshots.
- **Python package**: the `sfmtool` Python API, with the algorithms and file
  formats implemented in Rust.

## Repositories

| Repository | Contents |
| --- | --- |
| [sfmtool](https://github.com/sfmtool/sfmtool) | The CLI, the SfM Explorer viewer, the Python package and the Rust crates |
| [sfmtool.github.io](https://github.com/sfmtool/sfmtool.github.io) | The documentation site, served at [sfmtool.github.io](https://sfmtool.github.io/) |

The project is under active development and its interfaces still change.
