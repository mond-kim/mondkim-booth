# Booth furniture update · 2026-11-16

- 1000 table: v15.17 model from the table studio's saved source `94133ed2150920420a5d89d9b365c9e4f81ed109`, `dist/model-v1517.json`. Native part contours, extrusion thicknesses, rotations and offsets are preserved. Glass across flats 1000 mm; glass 8 mm; finished height 732 mm.
- 440 Cloud Stool: R3.2 `proposed` assembly from the stool studio's source `d71d478afe31be1f78bbfa47b37a33bae3c47e59`, `dist/model.json`. The newer R3.3 model is intentionally excluded. Native A/B plate triangle meshes, bent tabs and holes are retained. Timber 80 mm; seat height 460 mm; base width approximately 600 mm.
- The stool timber outline and grain are the source studio's visualization assumptions, not a trace of the manufactured wood. The consultation area contains one R3.2 stool in front of the table; the left seat is removed. The front stool is moved 20 mm inward to keep its wider footprint within the 2 m booth depth.
- Remaining booth objects and artwork retain the original scene geometry. Gallery images are regenerated from the same updated scene mesh data with Blender. Lighting differs slightly from the interactive Three.js view.

`assets/furniture-final.js` contains the source geometry required for the viewer; manufacturing AI/DXF downloads are not included in this repository. This update represents exhibition placement and does not change fabrication drawings.
