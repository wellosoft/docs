---
title: Other TEXDraw Variants
---

For any non-UI user or those who don’t want UI Canvas dependency, may use TEXDraw 3D. It’s a great alternative to using this component rather than standard one. You can add TEXDraw 3D to your scene by navigating to GameObject > 3D Object > TEXDraw 3D or attach this to your Game Object located in TEXDraw > TEXDraw 3D. You also can attach RectTransform (yes, it’s still work on outside Canvas) if you prefer.

Alternatively, for those who already use NGUI can use the NGUI variant. This kind of variant doesn’t available without importing the NGUI extension for TEXDraw first. This extension is packed as a .unitypackage file that can be found in TEXDraw root folder. To import it, simply open the package. To add this component to your scene, hit the NGUI menu located in NGUI > Create > TEXDraw

Those three variants have the similar functionality and properties. What you type inside in either text will yield the same result.

Either these three components, they can be Integrated seamlessly into TextMeshPro’s SDF Rendering. If you have TextMeshPro in the project, SDF Rendering in TEXDraw can be activated by Declaring scripting symbol TEXDRAW_TMP in Player settings and importing required shaders, which explained in detail here