# Lense Roadmap

Film emulation engine built on Soup Engine. GPL v2.

## 7D Port

Port to Canon 7D Mark II (Digic 5+, 20.2MP APS-C). Includes color matrix from DCP profiles, tone curve and WB pipeline adaptation.

## Atomos .cube Export

Export the in-camera look as an Atomos-compatible 3D .cube LUT for use on Shogun/Sumo monitors. CLI: `lense export --format cube`.

## Grain System

Silver halide grain simulation — size, roughness, ISO response. Luminance-weighted (grain in shadows, not highlights). Presets: ISO 400, 800, 3200.

## Lens Emulation

Vintage lens character: radial distortion, chromatic aberration (lateral + longitudinal), vignette, highlight bloom. Profiles: 50/1.4, 85/1.2, 24/2.8.

## AI Debayer

Neural demosaicing replacing bilinear/VNG. RGGB learned upsampling. Core ML / ONNX export. Target: 4K in < 2s on M-series Mac.

## iPhone

Metal shader port of color pipeline. AVCaptureSession RAW hook. Real-time preview 1080p60. .cube export from iPhone session.
