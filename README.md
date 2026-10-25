<div align="center">

# 🌐 Awesome 3D Web

**A curated list of libraries, tools, assets and learning resources for building 3D on the web, from product viewers and configurators to WebGPU and AI agent skills.**

Every GitHub link was checked for activity (not archived) when it was added. Last full review: **September 2026**.

![Links checked](https://img.shields.io/badge/links-checked_Sep_2026-brightgreen) ![License: CC0](https://img.shields.io/badge/license-CC0-lightgrey) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-blue)](CONTRIBUTING.md)

</div>

> **Part of the 3D Web series:** [Spin360](https://github.com/ahmettasdemirusa/spin360), a 360° product viewer web component, and [Three.js Product Skills](https://github.com/ahmettasdemirusa/threejs-product-skills), which teaches AI agents to build 3D product pages.

## Contents

- [Engines and libraries](#engines-and-libraries)
- [Framework bindings](#framework-bindings)
- [Product viewers, AR and 360°](#product-viewers-ar-and-360)
- [Physics and animation](#physics-and-animation)
- [Rendering, effects and splats](#rendering-effects-and-splats)
- [Shaders](#shaders)
- [glTF pipeline and optimization](#gltf-pipeline-and-optimization)
- [Debugging and performance](#debugging-and-performance)
- [WebGPU](#webgpu)
- [AI agent skills for 3D](#ai-agent-skills-for-3d)
- [Learning](#learning)
- [Free assets](#free-assets)

## Engines and libraries

- [three.js](https://github.com/mrdoob/three.js) - The most widely used JavaScript 3D library: WebGL and WebGPU renderers, loaders, controls and hundreds of [examples](https://threejs.org/examples/).
- [Babylon.js](https://github.com/BabylonJS/Babylon.js) - A full-featured rendering and game engine with an inspector, a node material editor and WebGPU support.
- [PlayCanvas](https://github.com/playcanvas/engine) - A graphics runtime built on WebGL, WebGPU, WebXR and glTF, with an optional collaborative [online editor](https://playcanvas.com/).
- [A-Frame](https://github.com/aframevr/aframe) - Declarative HTML for VR and AR scenes, built on three.js.
- [OGL](https://github.com/oframe/ogl) - A minimal WebGL library for people who want to stay close to the metal.
- [regl](https://github.com/regl-project/regl) - Functional, stateless WebGL.
- [CesiumJS](https://github.com/CesiumGS/cesium) - 3D globes and maps with 3D Tiles streaming.
- [deck.gl](https://github.com/visgl/deck.gl) - GPU-powered large-scale data visualization.

## Framework bindings

- [React Three Fiber](https://github.com/pmndrs/react-three-fiber) - A React renderer for three.js. [Docs](https://r3f.docs.pmnd.rs/).
- [Drei](https://github.com/pmndrs/drei) - Ready-made helpers for React Three Fiber: controls, staging, loaders and more.
- [@react-three/xr](https://github.com/pmndrs/xr) - VR and AR for React Three Fiber.
- [uikit](https://github.com/pmndrs/uikit) - User interfaces rendered inside React Three Fiber scenes.
- [Threlte](https://github.com/threlte/threlte) - A 3D framework for Svelte, built on three.js.
- [TresJS](https://github.com/Tresjs/tres) - Declarative three.js with Vue components.
- [Needle Engine](https://github.com/needle-tools/needle-engine-support) - Web-first 3D with Unity and Blender integrations, from browser to headset.

## Product viewers, AR and 360°

- [&lt;model-viewer&gt;](https://github.com/google/model-viewer) - Google's web component for glTF models, with AR on Android and iOS. [Docs](https://modelviewer.dev/).
- [Spin360](https://github.com/ahmettasdemirusa/spin360) - A zero-dependency 360° product viewer web component for image sequences and sprite sheets, under 5 KB gzipped.
- [Pannellum](https://github.com/mpetroff/pannellum) - A lightweight panorama viewer for equirectangular and cube-map images.
- [Photo Sphere Viewer](https://github.com/mistic100/Photo-Sphere-Viewer) - 360° spherical panoramas with markers, virtual tours and plugins.

## Physics and animation

- [Rapier](https://github.com/dimforge/rapier) - A fast 2D and 3D physics engine in Rust, with official JavaScript/WASM bindings. [Docs](https://rapier.rs/).
- [cannon-es](https://github.com/pmndrs/cannon-es) - A lightweight 3D physics engine written in JavaScript.
- [GSAP](https://github.com/greensock/GSAP) - A high-performance animation library, often paired with three.js for scroll-driven scenes.
- [Theatre.js](https://github.com/theatre-js/theatre) - A motion design editor for animating three.js scenes visually.

## Rendering, effects and splats

- [postprocessing](https://github.com/pmndrs/postprocessing) - A post-processing library for three.js: bloom, SSAO, depth of field and more.
- [three-gpu-pathtracer](https://github.com/gkjohnson/three-gpu-pathtracer) - A path tracer for three.js that turns ordinary scenes into photoreal renders.
- [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) - A BVH for fast raycasting and spatial queries on large meshes.
- [Spark](https://github.com/sparkjsdev/spark) - An advanced 3D Gaussian Splatting renderer for three.js.
- [GaussianSplats3D](https://github.com/mkkellogg/GaussianSplats3D) - A three.js implementation of 3D Gaussian Splatting.

## Shaders

- [LYGIA](https://github.com/patriciogonzalezvivo/lygia) - A granular, multi-language shader library (GLSL, HLSL, Metal, WGSL and more).
- [The Book of Shaders](https://thebookofshaders.com/) - A step-by-step guide to fragment shaders. [Source](https://github.com/patriciogonzalezvivo/thebookofshaders).
- [Shadertoy](https://www.shadertoy.com/) - Browse, fork and learn from thousands of live fragment shaders.
- [Inigo Quilez articles](https://iquilezles.org/articles/) - Signed distance functions, noise and ray marching, explained by a master.

## glTF pipeline and optimization

- [glTF-Transform](https://github.com/donmccurdy/glTF-Transform) - The glTF SDK and CLI: `optimize`, Meshopt/Draco compression, KTX2/WebP textures. [Docs](https://gltf-transform.dev/).
- [gltf.report](https://gltf.report/) - Inspect and optimize glTF files in the browser.
- [meshoptimizer](https://github.com/zeux/meshoptimizer) - Mesh simplification and compression; decoders ship with three.js.
- [Draco](https://github.com/google/draco) - Google's geometry compression library.
- [KTX-Software](https://github.com/KhronosGroup/KTX-Software) - Tools for KTX2 / Basis Universal GPU-compressed textures.
- [glTF Validator](https://github.com/KhronosGroup/glTF-Validator) - Check glTF files against the specification. [Web version](https://github.khronos.org/glTF-Validator/).
- [glTF Sample Viewer](https://github.khronos.org/glTF-Sample-Viewer-Release/) - Khronos' reference viewer, for checking how a model should look.
- [glTF-Blender-IO](https://github.com/KhronosGroup/glTF-Blender-IO) - Blender's official glTF 2.0 importer and exporter.
- [gltfjsx](https://github.com/pmndrs/gltfjsx) - Turns glTF files into reusable React Three Fiber components.

## Debugging and performance

- [stats.js](https://github.com/mrdoob/stats.js) - An FPS and frame-time monitor.
- [r3f-perf](https://github.com/utsuboco/r3f-perf) - A performance monitor for React Three Fiber scenes.
- [lil-gui](https://github.com/georgealways/lil-gui) - A small floating panel for tweaking parameters, and a drop-in replacement for dat.gui.
- [Leva](https://github.com/pmndrs/leva) - A React-first GUI for tweaking values.
- [Spector.js](https://github.com/BabylonJS/Spector.js) - Capture and inspect WebGL frames call by call. [Extension](https://spector.babylonjs.com/).
- [RenderDoc](https://renderdoc.org/) - A graphics debugger for deep GPU frame analysis.
- [three.js editor](https://threejs.org/editor/) - An in-browser scene editor for importing and inspecting models quickly.

## WebGPU

- [WebGPU Samples](https://github.com/webgpu/webgpu-samples) - Official samples showing the WebGPU API in practice.
- [WebGPU Fundamentals](https://webgpufundamentals.org/) - A thorough tutorial series for the WebGPU API and WGSL.
- [WebGPU on Chrome for Developers](https://developer.chrome.com/docs/web-platform/webgpu) - Overview, availability and best practices.

## AI agent skills for 3D

Skills that teach AI coding agents such as Claude Code and Codex to produce better 3D code.

- [Three.js Product Skills](https://github.com/ahmettasdemirusa/threejs-product-skills) - Product viewers, configurators, glTF optimization, &lt;model-viewer&gt; AR and 360° spins, with tested templates.
- [threejs-game-skills](https://github.com/majidmanzarpour/threejs-game-skills) - Skills for building playable, polished three.js browser games.
- [Three.js Awesome Graphics Agent Skills](https://github.com/scottstts/Threejs-Awesome-Graphics-Agent-Skills) - Skills for producing high-quality graphics in three.js scenes and games.
- [3dviz-pro-max](https://github.com/viettranx/3dviz-pro-max) - Creative 3D visualization, from an idea to a three.js or Blender scene.
- [threejs-architecture-effects](https://github.com/lhlGitHub/threejs-architecture-effects) - Interactive, self-assembling 3D architecture with three.js.
- [shader-for-interfaces](https://github.com/v2space-labs/shader-for-interfaces) - Designing, building and validating focused GPU effects for interfaces.
- [GSAP skills](https://github.com/greensock/gsap-skills) - GSAP's official skills for animation code.

## Learning

- [three.js manual](https://threejs.org/manual/) - The official guide, from fundamentals to optimization.
- [Discover three.js](https://discoverthreejs.com/) - A free online book about building professional three.js apps.
- [Three.js Journey](https://threejs-journey.com/) - A comprehensive video course (paid).
- [WebGL Fundamentals](https://webglfundamentals.org/) and [WebGL2 Fundamentals](https://webgl2fundamentals.org/) - How WebGL really works, from first principles.
- [Scivra](https://www.scivra.com/) - Free interactive 3D science labs (physics, chemistry, biology) built for the browser, a hands-on example of educational 3D on the web.

## Free assets

- [Poly Haven](https://polyhaven.com/) - CC0 HDRIs, textures and models. The HDRIs are ideal for product lighting.
- [ambientCG](https://ambientcg.com/) - CC0 PBR materials, HDRIs and models.
- [Kenney](https://kenney.nl/assets) - CC0 game assets, including many low-poly 3D kits.
- [glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets) - Khronos' reference models for testing viewers and features.
- [Sketchfab](https://sketchfab.com/) - A huge model library. Check each model's license before use.

## Contributing

Suggestions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ahmet Tasdemir](https://github.com/ahmettasdemirusa) has waived all copyright and related rights to this work.
