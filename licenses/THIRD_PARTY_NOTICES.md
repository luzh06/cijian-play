# Third-party notices

| Component | Included files | License |
| --- | --- | --- |
| Three.js r170 | web/vendor/three.module.js and addons, including Octree.js and Capsule.js | MIT; see three-r170-LICENSE.txt |
| fflate 0.8.2 | local loader dependency | MIT; see fflate-0.8.2-LICENSE.txt |
| PLATEAU, OpenStreetMap, GSI, Poly Haven and model/texture assets | streets, terrain, HDRI, props | See tokyo-fill.csv and tokyo-props.md for per-asset sources and attribution |

Octree.js and Capsule.js retain the official Three.js r170 algorithms and MIT license. Octree's triangle/capsule narrow phase is reused with a project-owned bounded spatial grid.
Input controls were authored by the collaborating DeepSeek session; its references and implementation boundary are documented in CONTROLS_HANDOFF.md. No extra NippleJS, Sketchbook or Rapier runtime is bundled.
The derived access geometry was authored for this scene and does not replace PLATEAU/OSM source geography. The temple/Yanaka connection is a fictional composition.
These notices do not assign a blanket license to the team's own work or all scene assets.
