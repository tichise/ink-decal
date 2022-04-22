[![Create UPM branches and run NPM publish](https://github.com/tichise/ink-decal/actions/workflows/publish.yml/badge.svg)](https://github.com/tichise/ink-decal/actions/workflows/publish.yml)

ink-decal

ink-decal is a library for projecting Splatoon-like ink using Unity's Decal function.

## What is Decal?
[Decal Renderer Feature | Universal RP | 12.0.0](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@12.0/manual/renderer-feature-decal.html)

With the Decal Renderer Feature, Unity can project specific Materials (decals) onto other objects in the Scene. The decals interact with the Scene’s lighting and wrap around Meshes.

## Install

Add the following to `manifest.json` in UnityProject.


```json
{
  "scopedRegistries": [
    {
      "name": "npm",
      "url": "https://registry.npmjs.com",
      "scopes": [
        "tokyo.tichise"
      ]
    }
  ],
  "dependencies": {
    "tokyo.tichise.ink-decal": "1.0.0",
  }
}

```
