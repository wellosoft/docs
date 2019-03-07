---
title: FAQ
section: About TEXDraw
---

## What is TEXDraw?

![Preview](images/intro.jpg){:class="float-right size-md"}
TEXDraw is a Component that makes a plain text can be converted into a graphical representation of mathematical formulas. TEXDraw renders mathematical formulas using the similar approach introduced in LaTeX writing system. The result is in form of a 3D mesh that can be used inside Unity’s UI or other mesh-based rendering systems.

## How it does work and why it is different?

TEXDraw, just like many other text generators, is designed to render strings to display screen. TEXDraw however, adds some functionality to render any kind of mathematical expressions that are used in various apps like educational software, scientific simulations, and many more. With the power of Unity’s built-in UI System and dynamic text support, generating math expressions are so easier and seamlessly than ever!

## What’s the Benefit of TEXDraw compared than Standard UI Text?

A lot, including:
+ LaTeX syntax, which has more clean typos and flexible features than standard HTML markup
+ Rich math expressions, including fractions, root, matrix, scripts, straight lines, tables, etc.,
+ Resizable delimiters or brackets, which is essential for writing complex math.
+ Dedicated UI layout system (No need external Horizontal/Vertical Layout).
+ +600 symbols included, or add your own symbol sets.
+ +40 distict expressions, including custom text font, size, color, background, borders, etc.
+ Import and use Sprites just like inserting font characters (aka. Inline sprites).
+ First class text features, including word wrap, justify alignment, and best fit mode.
+ Built-in support for rendering into Unity’s UI rendering, MeshFilter, or NGUI.
+ Built-in integration with TextMeshPro SDF Rendering
+ Dedicated editor GUI for customizing TEXDraw in many aspect.
+ Open source, no precompiled library, compatible to all platform.
+ Optimized codebase, work fast on mobiles.
+ Highly extensible extension (supplements), which enables:
+ RTL + Bidirectional input, WYSIWYG input editor, Link highlights, HTML + Markdown parsing, warping + WordArt effects, colour/gradient effects, bind to other UI (eg. inline images), etc.
+ And much other stuff you can think of...

## How easily I can make it work on my project?

Soon after you importing TEXDraw into your project, You can create a TEXDraw Object in `GameObject -> UI -> TEXDraw`, and start to typing on it.
Also, don’t forget check out sample scenes in `Assets/TEXDraw/Sample/Scenes`.

```c#
HA()
```

## Will this work on all platform? Any performance issues?
This package has been tested on runtime builds, including mobiles and web build. We always considering performance when we write new features. This asset halts your game performance? Tell us.

## Do this package provide support for other External Asset?
Yes, TEXDraw supports drawing text into NGUI environment or using the benefit of SDF Rendering from TextMeshPro. Click here for instruction setup.

## Can TEXDraw receive User Input?
Yes, There are two kind of input: TEXLink and TEXInput. Both adds interactivity to TEXDraw. You can see the details by visiting at either link.

## I have other trouble. Any suggestion for me?
See troubleshoot page for common problems.
