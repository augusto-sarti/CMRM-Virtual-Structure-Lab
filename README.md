# CMRM Virtual Structure Lab — dual recordings, bundled edition v0.3

Two audio performances of Beethoven's *Für Elise* are bundled in `audio/` and have been decoded successfully in a media test.

## Publishing to GitHub Pages

Upload the **contents** of this folder (not the folder itself) to the root of the `CMRM-Virtual-Structure-Lab` repository, preserving the `audio/` and `modules/` directories. GitHub Pages serves `index.html` automatically. When served via HTTPS/HTTP, the site loads both bundled files automatically. If it does not, press **Load both default performances**.

Modules 1–5 and 7 use Performance A, and Module 6 compares A and B. Both source recordings can be replaced independently using file inputs. Uploaded audio stays in the browser.

When opening `index_offline.html` with file://, browsers may prohibit fetch() of nearby files. If the automatic defaults fail, select the two bundled OGG files via the file inputs or run a local HTTP server.

## Licensing

- A: V. Gao, CC0 1.0.
- B: Jason M. C. Han, CC BY-SA 4.0, attribution is required.

Consult `AUDIO_CREDITS.md`; retain it when publishing. The OGG recordings are bundled unchanged.

This updates the unified site only; previous approved module source files are retained inside `modules/`. End-to-end browser behavior should be checked after upload.
