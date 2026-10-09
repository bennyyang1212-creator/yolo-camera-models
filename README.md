# YOLOCamera model downloads

Public Core ML model files for YOLOCamera, based on Ultralytics YOLO26 and YOLOE26.

Download models from [Releases](https://github.com/bennyyang1212-creator/yolo-camera-models/releases/tag/coreml-input-v2). No account is required to download. The app downloads models on demand and verifies SHA256 before compiling them locally. The bundled nano models also remain available offline.

## Model inputs

- Detection: 320×320 live, 640×640 still.
- Pose, segmentation, depth: 512×512 live, 640×640 still, 960×960 AI still for s/m/l/x.
- Classification: 224×224 live/still, 336×336 AI still for s/m/l/x.
- Semantic segmentation and oriented boxes: 640×640.

`manifest.json` lists all 45 model archives, sizes, and checksums. Export scripts and input documentation accompany the release.

Upstream model sources: https://github.com/ultralytics/ultralytics and https://github.com/ultralytics/assets/releases . Models are subject to the licensing terms in LICENSE.txt. Models may return no detections; classification/depth/semantic outputs have task-specific behavior. These exports do not establish accuracy guarantees.
