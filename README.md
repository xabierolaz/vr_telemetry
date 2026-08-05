# Semantic Telemetry Pipeline for UAV Digital Twins (Pipeline A/B)

Companion repository for the paper on object-level semantic telemetry for operating UAVs from a geospatial digital twin when the video link degrades. It contains the full LaTeX manuscript (compile-ready, mirrors the Overleaf project) and links to the real-flight data and video.

**Status:** under preparation / review (target venue: VRIH).

## Demo

Side-by-side: real flight with YOLO detections (left) vs. the Unreal Engine / Cesium digital twin with reconstructed semantic actors (right):

![Side-by-side demo: real flight (YOLO) vs digital twin (Unreal/Cesium)](media/side_by_side_twin_preview.gif)

▶️ Full-quality video (24 s, 2560×960): [`media/side_by_side_twin.mp4`](media/side_by_side_twin.mp4)

## TL;DR

Instead of streaming video, the aircraft downlinks per-object semantic telemetry (detector tags, tracks, footprints, aircraft pose) at kilobyte scale; the ground station reconstructs and displays the scene inside the twin. The paper reports the end-to-end pipeline, the bandwidth/latency characterization, and a real-flight validation with a YOLO-based perception front-end.

## Repository contents

| `media/` | Demo video: side-by-side real flight vs. digital twin (GIF preview + full mp4) |

## Resources

- **Real-flight video:** `video_final.mp4` in the [Resources release](../../releases/tag/resources) — onboard recording of the validation flight used in the paper, with synchronized telemetry (`video_final_gps.csv`, `video_final_sync.json` included in the same release).
- **Side-by-side demo video:** [`media/side_by_side_twin.mp4`](media/side_by_side_twin.mp4) — real flight with YOLO detections next to the synchronized digital-twin reconstruction (see GIF preview above).
