# Semantic Telemetry Pipeline for UAV Digital Twins (Pipeline A/B)

Companion repository for the paper on object-level semantic telemetry for operating UAVs from a geospatial digital twin when the video link degrades. It contains the full LaTeX manuscript (compile-ready, mirrors the Overleaf project) and links to the real-flight data and video.

**Status:** under preparation / review (target venue: VRIH).

## TL;DR

Instead of streaming video, the aircraft downlinks per-object semantic telemetry (detector tags, tracks, footprints, aircraft pose) at kilobyte scale; the ground station reconstructs and displays the scene inside the twin. The paper reports the end-to-end pipeline, the bandwidth/latency characterization, and a real-flight validation with a YOLO-based perception front-end.

## Repository contents

| Path | Content |
|---|---|
| `main.tex` | Full manuscript |
| `VRIH2025.cls` | Journal class (compiles with both pdfLaTeX and XeLaTeX) |
| `figures/` | Figures referenced by the manuscript |

## Resources

- **Real-flight video:** `video_final.mp4` in the [Resources release](../../releases/tag/resources) — onboard recording of the validation flight used in the paper, with synchronized telemetry (`video_final_gps.csv`, `video_final_sync.json` included in the same release).

## Compile the paper

`pdflatex main.tex` (default) or `xelatex main.tex` — the class selects fonts accordingly (`\ifPDFTeX` guard, no fontspec required under pdfLaTeX).

## Citation

Citation details will be added upon publication.
