# 3D Cartoon Studio — Browser Edition

## Run
1. Extract the ZIP.
2. Open `index.html` in a modern browser with internet access.
3. If your browser blocks JavaScript modules on `file://`, run a local static server (for example VS Code Live Server) or publish the folder to GitHub Pages.

## Included
- 9 editable scene blocks
- Procedural 3D cartoon placeholder characters and environment
- Three.js renderer and GSAP dependency loaded as an ES module
- Camera presets and simple camera moves
- Scene duration, lighting, action notes and background settings
- Project JSON save/load
- Browser recording of the full scene sequence as WebM

## Current limitations
- This is a working starter editor, not a complete professional animation suite.
- Characters are simple procedural placeholders. Importable GLB/GLTF character support, rig controls, lip-sync, audio tracks and advanced timeline keyframes are future upgrades.
- Browser recording exports WebM where MediaRecorder is supported. MP4 is not guaranteed in browsers; browser-side FFmpeg conversion can be added later but is memory-intensive, especially on phones.
- Blender is not embedded in the browser. Use Blender to create/export licensed GLB/GLTF assets, then load them in a future asset-import module.
- Three.js and GSAP are loaded from jsDelivr, so the first launch requires an internet connection.
