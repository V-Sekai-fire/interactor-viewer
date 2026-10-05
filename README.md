# interactor-viewer

A planned mesh-viewer adapter for checking solver output by eye; today it holds only the C port headers it will implement.

## What it is for

It will be a mesh sink that loads the retarget core's per-step meshes into an interactive viewer bound to Elixir, to confirm fits are free of intersections and keep their polygons, UVs and materials, and to compare them with reference meshes. The port headers define the mesh payload and the source and sink interfaces as a plain C ABI.

## Building and running

There is nothing to build yet.

## Licence

MIT. See [LICENSE](LICENSE).
