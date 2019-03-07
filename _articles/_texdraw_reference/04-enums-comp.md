---
title: Enumeration Choices
---

**Auto Fit** is used for what happens to the whole text when generated text is out of the given rectangle layout. The choices are...

| Off | Turn off rescaling. Text can generated beyond it’s rectangle |
| Down Size | Scale text down if it oversized |
| Rect Size | Force the rectangle to follow the generated text size |
| Height Only | Adjust the height of the rectangle automatically |
| Scale | Scale the generated text until fit on the rectangle |
| Best Fit | Attempt to find the largest possible size (caution: potentially expensive) |
{:class="props"}

**Auto Wrap** is used for what happens to each line of generated text when it’s horizontal line is beyond than given rectangle width. Auto Wrap is always be calculated first before Auto Fit.

| No Wrap | No wrapping applied |
| Letter Wrap | Wrap (Move to below) any character if it oversized |
| Word Wrap | Wrap any word if it oversized |
| Word Wrap Justified | Wrap any word, then stretch space sizes to rectangle edges |
{:class="props"}

**Auto Fill** is useful only if you use a custom material which requires UV1 vectors like Gradient and Texture Overlay shaders. This is about how texts are UV-mapped, in automatic-way.

| None | Don’t attempt to fill any UV1 values (Faster) |
| Rectangle | Interpolate according to Rectangle Bound (Scaling will take effect) |
| Whole Text | Interpolate to the generated text rectangle (Scaling isn’t taken into effect) |
| Whole Text Squared | Interpolate like Whole text, but keep at ratio size of 1:1 (prevent stretches) |
| Per Line | Interpolate text line-by-line |
| Per Character | Generated Character Quads will always either have (0,0) or (1,1) coordinate. |
| Per Character Squared | Like per-character, but keep it’s aspect ratio at 1:1. |
| Local Continous | All characters UV is mapped based on their local position |
| World Continous | All characters is mapped based on their world position, interactively. |
{:class="props"}
