# Timbremancer Forge Content

This repository publishes the live catalog for Forge's Content Store and keeps
the provenance records for redistributed third-party content.

- `catalog.json` is the catalog Forge reads from `raw.githubusercontent.com`.
- `Multisamples/` contains source and licensing records, organized by family.
- Large `.timbrelibrary` packages are attached to immutable, versioned GitHub
  Releases instead of being committed to Git.

Each Content Store card installs one curated top-level SFZ. SFZ include files
and samples are packaged inside that instrument's `.timbrelibrary` as private
dependencies, so they do not appear as separate Forge Library rows.

Only content whose redistribution terms have been reviewed belongs here.
