The mobility of a light source control whether the light is [[Static Lighting|Static]] or [[Dynamic Lighting|Dynamic]].


# Movable

When a [[Light]]'s mobility is set to Movable then its light is fully dynamic, both direct and indirect lighting.
It is computed at runtime.
This includes [[Shadows]] and [[Shading]].

This is useful if the light will be moved or if parameters other than color or intensity is changed at runtime.

It will not influence baked lighting such as [[Lightmass]].
It will cast [[Dynamic Shadows]] if Details panel > Light > Cast Shadows is enabled.
If at least one of Cast Dynamic Shadows and Cast Static Shadows is enabled in the same category.


# Stationary

Means that the light won't move, but there are some properties, such as intensity and color, that can change at runtime.
Not sure if there are other parameters that can change as well.
Will result in partially baked lighting.
Direct lighting and direct shadows will be computed at runtime.
Indirect, [[Global Illumination]], lighting will be baked.


# Static

The [[Light]] may not change in any way.
Can be fully baked using [[Lightmass]], producing [[Baked Lighting]] for both direct and indirect lighting.

Whenever something is changed in the scene that affects the baked [[Lightmap|Lightmaps]] a Preview text will be shown on the objects that receive baked lighting.
This means that what is shown in the [[Level Viewport]] isn't representative of what the final package project will look like.


# References
- [_Lighting in Unreal Engine 5 for Beginners_ by William Faucher @ youtube.com](https://youtu.be/fSbBsXbjxPo?t=318)
- [_Understanding Lightmass - Baking Checklist_, by Epic Games @ dev.epicgames.com](https://dev.epicgames.com/community/learning/courses/yon/introducing-global-illumination/kn8/understanding-lightmass-baking-checklist)



