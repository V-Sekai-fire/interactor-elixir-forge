# interactor-elixir-forge

Elixir tools for machine-learning inference and mesh work: an image-generation pipeline app and single-file scripts.

## What it is for

`apps_tools/` holds the Mix applications. `apps_tools_development/` holds the scripts, for image editing, vision-language inference, speech, rigging, segmentation and mesh conversion. Some scripts keep the third-party code they call in their own `thirdparty/`, and shared third-party code sits in the top-level `thirdparty/`. [docs](docs/index.md) describes the tools.

## Build and run

    cd apps_tools/zimage_generation && mix deps.get && mix test

A development script runs with `elixir <script>.exs`; the comment at its top gives its usage.

## Licence

MIT. See [LICENSE](LICENSE). Vendored third-party trees keep their own licences.
