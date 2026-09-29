# Semantic Telemetry for UAV Digital Twins — data and media

Companion data repository for the manuscript *A VR Digital Twin for UAV Teleoperation under Degraded Video Links: Geospatial Priors and Semantic Object-State Telemetry in Unreal Engine* (under review at *Virtual Reality & Intelligent Hardware*).

## Demo

Side-by-side: real flight with YOLO detections (left) vs. the Unreal Engine / Cesium digital twin with reconstructed semantic actors (right):

![Side-by-side demo: real flight (YOLO) vs digital twin (Unreal/Cesium)](media/side_by_side_twin_preview.gif)

Full-quality video (24 s, 2560×960): [`media/side_by_side_twin.mp4`](media/side_by_side_twin.mp4)

## Real-flight data

The onboard recording of the validation flight and its synchronized telemetry are in the [Resources release](../../releases/tag/resources):

| File | Content |
|---|---|
| `video_final.mp4` | Onboard video of the validation flight |
| `video_final_gps.csv` | GNSS track synchronized with the video |
| `video_final.json` | Per-frame synchronization metadata |
| `video_final_yolo_towers.mp4` | Onboard video with YOLO tower detections |
| `side_by_side_twin.mp4` | Real flight vs. digital twin, synchronized |

## Other media

`media/vision_yolo_peloton_road_FINAL.mp4` — simulated moving-obstacle encounter (Unreal closed loop) from related work by the same authors.

## Citation

Citation details will be added upon publication.
