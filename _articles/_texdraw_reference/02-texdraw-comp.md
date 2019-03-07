---
title: TEXDraw Component
section: Inside of TEXDraw Package
---

This component is available under Unity’s UI Canvas object. This component has been made simple, so you can keep your focus on what you’ll type into.

Aside from **Text**, there are other optional properties that are quite useful for handling display output. Below is Description of each property inside this Component:

| Text | A plain text that you want input to. |
|| See here for practical guide to write, and here for scripting instruction. |
| Size | Size of generated graphics |
|| The font texture size will automatically resized based on Canvas configuration.   |
| Font Index | Index of used default font (-1 to follow default typeface rules) |
|| In scripting, you can set this as integer value. Each number represents an index of font that registered in the Font Stack. |
| Auto Fit | How final graphic is scaled when it’s render is out of the rectangle bound |
|| See here for available options |
| Auto Wrap | Horizontal wrapping mode if a line is beyond rectangle’s horizontal bound |
|| See here for available options   |
| Alignment | The horizontal and vertical alignment of the text. |
|| In scripting, this is a Vector2 property. A value of {0, 0} represent left-bottom alignment |
| Color | The main color for generated graphics |
|| Use \color if you want to write specific color |
| Material | Assign a Custom Material for This component |
|| If none assigned, the default material (from Resource) will be used for rendering  |
| Filling | Optional options for manipulating UV2 data |
|| Used in conjunction with custom Material effects, choose the way when font characters are overlaid with some shader graphics |
{:class="props detailed"}
