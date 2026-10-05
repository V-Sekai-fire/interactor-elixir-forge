# interactor-elixir-forge

Elixir tools that drive Python machine-learning models: an image-generation pipeline app and single-file scripts for media and mesh work.

## What it is for

`apps_tools/` holds the Mix applications. `apps_tools_development/` holds the scripts, for image editing, vision-language inference, speech, rigging, segmentation and mesh conversion, each with the third-party code it calls vendored beside it. [docs](docs/index.md) describes the tools.

## Build and run

    cd apps_tools/zimage_generation && mix deps.get && mix test

A development script runs with `elixir <script>.exs`; the comment at its top gives its usage.

## Licence

MIT. See [LICENSE](LICENSE). Vendored third-party trees keep their own licences.
