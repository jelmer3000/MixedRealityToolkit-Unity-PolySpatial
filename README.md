# Fork of Mixed Reality Toolkit for Unity, for supporting VisionOS via PolySpatial

## With the release of VisionOS2, you now have two options:
### Option 1: Use MRTK in immersive mode (via the polyspatial plugin)
This repo was based on the PolySpatial plugin in the Immersive Mode. This meant that all original MRTK shaders are NOT supported and will render black or pink. I recreated some of the shaders, to some extend, in shader graph so that the demo scenes looks kind of "OK". However, don't expect full shader support. WIP and some more info can be found on [this branch](https://github.com/jelmer3000/MixedRealityToolkit-Unity-PolySpatial/tree/wip-polyspatial-visionOS-support)

### Option 2: Use MRTK in fully immersive mode (with passthrough from VisionOS 2.0)
Now with VisionOS2, you could also explore the Fully Immersive Mode (=without the Polyspatial plugin), since this mode now has support for video-passthrough . This means *theoretically* that all MRTK shaders just work since graphics are handled by the URP pipeline as usual. How to set up the input system, I don't know. Please let me know if you find out more. I haven't tried this option myself yet. 



