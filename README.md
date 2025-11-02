# J2ME Apps Collection

Ready-to-run MIDP-2.0 / CLDC-1.1 JARs. Works in J2ME Loader (Android) and on real Java ME devices.

## Downloads
- Get the JARs from the repository.
- Each app is self-contained; no extra libraries required.

## How to Run
- Android (recommended): install J2ME Loader → import the .jar → launch.
- Real devices: copy the .jar to the phone → install via the device’s Java app manager.

## What’s Inside
- Cornell-Cube3D
  - Three compact demos: a rotating wireframe cube, three spheres with path tracing, and a Cornell box path-traced scene adapted for phones.
- FluidSim2D
  - Real-time 2D fluid simulation with smooth advection and vivid flow visualization.
- ReactiveLight 2D
  - 2D ray emission and refraction through prisms; clean, crisp ray visuals.
- Mini_Mine
  - Voxel world with a classic 3D rasterizer and a path tracer (ambient occlusion, soft shadows, color bleeding, progressive accumulation).
- Cloth Physics Simulator
  - Mass–spring cloth with Verlet integration, sphere/ground collisions, Z-buffer rasterization, and simple lighting.
- System Info (AIDA64-like)
  - Device/JVM diagnostics: JSR support, memory, display, color depth, key map, RMS info, and a tiny CPU benchmark.

## Compatibility
- Target: MIDP-2.0, CLDC-1.1.
- Works well in J2ME Loader across a range of Android devices and resolutions.
- Real devices: any handset supporting MIDP-2.0/CLDC-1.1 should run the JARs; performance depends on hardware.

## Notes
- Path-traced demos (Cornell scenes, Mini_Mine RT mode) accumulate samples over time. For best quality, hold the camera still and let the image refine.
- Performance varies by device. If an app offers quality or resolution settings, reduce them on slower phones.

## License
Licensed under the MIT License. See LICENSE for details.

## Credits
Thanks to tester Denis Rachev (DeNiS_RaChEv).
