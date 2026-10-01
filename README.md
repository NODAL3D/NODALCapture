# NODAL Capture

Capture software included with the **NODAL M1** portable multi-camera motion capture system from NODAL Vision Systems.

NODAL Capture covers setup, calibration, capture, and export for synchronized multi-camera 3D sessions. It ships with the hardware.

## Platform support

**Windows 10 / 11 (64-bit) only** for now. macOS and Linux builds are not available yet.

## What it does

1. **Setup** — Pair cameras with the system (USB dongle for sync and trigger).
2. **Calibration** — Wand-based volume calibration with per-camera residuals before a session.
3. **Capture** — Hardware-triggered takes across cameras with sub-5 ms sync (system capability: 30–120 FPS global shutter).
4. **Export** — Synchronized video and calibration out to the pipeline you already use.

NODAL is the capture layer. You can pair exports with the post-processing or analysis tools you trust.

## Post-processing (alpha)

The product roadmap includes post-processing tools that ship alongside capture. Treat these as **alpha** unless a release notes otherwise:

- Capture editor
- Pose estimation (open-source models loaded)
- Manual pose adjustment
- Fine tuning

Capture, calibration, and export are the production-ready path today. C3D and OpenSim export are supported where stated in current product materials. API and SDK are in development.

## System requirements (software)

| Requirement | Detail |
| --- | --- |
| OS | Windows 10 / 11 · 64-bit |
| Memory | 8 GB (16 GB recommended for 8-camera kits) |
| Ports | One USB-A or USB-C for the dongle |

Hardware kits (cameras, tripods, dongle, case) are configured per session — camera count and volume size are scoped with sales.

## Download

Download the Windows installer (`.exe`) from the current NODAL Capture release channel used by your team (GitHub Releases or the download section on [nodal3d.com](https://www.nodal3d.com) when published).

No licence key is required for founding / included-with-hardware installs as described on the site: the software ships with the system.

## First session

1. Run the Windows installer.
2. Plug in the universal USB dongle.
3. Power on cameras — they join the session; calibrate the volume, then capture.

## Related

- Product site: [https://www.nodal3d.com](https://www.nodal3d.com)
- Company: NODAL Vision Systems Pte. Ltd.
- Contact: hello@nodal3d.com
