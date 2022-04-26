[![Create UPM branches and run NPM publish](https://github.com/tichise/ink-decal/actions/workflows/main.yml/badge.svg)](https://github.com/tichise/ink-decal/actions/workflows/main.yml)

Ink Decal Library for Unity
---

Ink Decal Library is a library for projecting Splatoon-like ink using Unity's Decal function.

<img width="512" alt="image" src="https://user-images.githubusercontent.com/43707/164626855-69f32ff9-95c1-4371-8884-865e148c6558.png">

### What is Decal?
[Decal Renderer Feature | Universal RP | 12.0.0](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@12.0/manual/renderer-feature-decal.html)

With the Decal Renderer Feature, Unity can project specific Materials (decals) onto other objects in the Scene. The decals interact with the Scene’s lighting and wrap around Meshes.

### Install

#### How to use decals
To use decals in URP, first add a decal from the Add Renderer Feature button under Universal Renderer Data.

#### manifest.json
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
    "tokyo.tichise.ink-decal": "1.0.3"
  }
}

```
