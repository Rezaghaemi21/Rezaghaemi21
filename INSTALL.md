# Installation

1. Open the profile repository `Rezaghaemi21/Rezaghaemi21`.
2. Replace its root `README.md` with the included `README.md`.
3. Copy the included `assets` folder to the repository root.
4. Commit the three files to the default branch.

Expected structure:

```text
Rezaghaemi21/
├── README.md
└── assets/
    ├── hero-dark.svg
    ├── hero-light.svg
    ├── system-dark.svg
    └── system-light.svg
```

The graphics are self-contained animated SVG files with no external font or image dependency. GitHub selects the matching asset through the `picture` element when the interface switches between light and dark mode. Motion is disabled automatically when the visitor prefers reduced motion.
