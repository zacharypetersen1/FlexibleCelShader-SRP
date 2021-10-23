This repository contains versions of Flexible Cel Shader built for URP and HDRP.

To use:


1.) Clone / copy the repo into your project.

2.) When you create a new material, select either "Shader Graphs/Urp_FlexibleCelShader" or "Shader Graphs/Hdrp_FlexibleCelShader".


A thing to note:

1.) All color properties use HDR colors. For the high / low light color, instead of using a separate slider for the intensity, click on the color itself and either adjust the HDR color's intensity slider at the bottom or manually enter a value. 


To Add an Outline:

1.) Create an extra material slot on the MeshRenderer component.

2.) Create a meterial using one of the outline shaders found under the "Outline" category.

3.) Place the outline material in the new material slot.

You'll find two outline shaders under the categories "Outline/Outline" and "Outline/TransparentOutline".
