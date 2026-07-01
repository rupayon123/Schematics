<h1 align="center">Schematics</h1>

<p align="center">
  <strong>Public workspace for electronics schematics, hardware notes, circuit references, and project diagrams.</strong>
</p>

<p align="center">
  <a href="https://github.com/rupayon123/Schematics">Repository</a>
  |
  <a href="projects/README.md">Project Index</a>
  |
  <a href="templates/parts-list.md">Parts List Template</a>
</p>

## About

Schematics is a lightweight public home for hardware diagrams and electronics notes. Use it to collect circuit sketches, wiring references, board pinouts, parts lists, and project-specific schematic files.

## Suggested Layout

```text
projects/       Project-specific schematic folders and index
templates/      Reusable project README and parts-list templates
references/     Datasheets, pin maps, and reusable notes
exports/        PNG, PDF, or SVG schematic exports
```

## Add A Project

1. Create a folder in `projects/<project-name>/`.
2. Copy `templates/project-readme.md` into that folder as `README.md`.
3. Copy `templates/parts-list.md` into that folder as `parts-list.md`.
4. Add source schematic files, exported diagrams, wiring notes, and verification notes.
5. Update `projects/README.md` so the project is easy to find.

## Status

This repository is ready for the first hardware notes and diagrams.

## License

MIT
