# CMRM Virtual Structure Lab — integrated prototype 0.1

Open `index_offline.html` in a modern browser, or deploy the whole folder to GitHub Pages. The navigation includes Modules 1–3 (one page), 4, 5, 6, and 7. The original approved module packages in `/mnt/data` have **not been altered**.

## Shared audio
Choose one recording in the top panel. The host sends the file to each module when opened. Every module extracts its own descriptors; calculations and settings are intentionally isolated, so a module's results do not overwrite another's. The module's original file selector remains usable. For Module 6, shared audio loads as Performance A; use its separate selector for Performance B. Audio is not uploaded to any server.

## Usage caveats
- Analysis can take time on full-length recordings, particularly when first opening another module.
- When switching modules, their playback is paused, but already visited modules stay loaded.
- The direct Wikimedia OGG download may be blocked by network policies; use the recording link and select a local file instead.
- Individual modules retain their original UI, so this is **functional integration**, not the final design-system consolidation.
- Module 7 form annotations remain local to its active page; CSV export is available there.
- Licensing: https://commons.wikimedia.org/wiki/File:FurElise.ogg (V. Gao, CC0 as indicated by the Commons page). The recommended recording itself is not bundled.

## Preserved source versions
- CMRM_Structure_Lab_Modules1-3_Audio_Revision_v01
- CMRM_Structure_Lab_Module4_Audio_CC0_v05
- CMRM_Structure_Lab_Module5_Feature_Fusion_v02
- CMRM_Structure_Lab_Module6_DTW_v01
- CMRM_Structure_Lab_Module7_Integrated_Form_v02
