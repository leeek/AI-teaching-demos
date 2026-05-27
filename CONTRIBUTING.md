# Contributing a Demo

Thank you for helping build this shared library. The goal is to make examples easy for other faculty to find, understand, adapt, and use in class.

## How to Add a Demo

1. Copy the `_template/` folder.
2. Rename the copied folder with a short, descriptive name for your demo.
3. Move the renamed folder into `demos/`.
4. Fill in the demo folder's `README.md`.
5. Add your demo file or files to that same folder.
6. Submit a pull request.

If you are not comfortable with git, you can also send the completed demo folder to `[maintainer]`.

## Conventions

- Use relative paths for all file references, such as `./images/thing.png`, not absolute paths from your own computer.
- Prefer a single self-contained HTML file where possible.
- Name the main demo file `index.html` so it works cleanly on GitHub Pages.
- Each demo folder must include a `README.md`.

## README Fields

Each demo README should include:

- Concept taught
- Course where it is used
- Prompt used to generate it, or a short summary of the prompt
- Any manual tweaks made after generation
- Known limitations or quirks
