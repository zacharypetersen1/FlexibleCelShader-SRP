This repository contains versions of Flexible Cel Shader built for URP and HDRP.

To use:\
1.) Clone / copy the repo into your project.\
2.) Delete the URP or HDRP folder if you are not using that render pipeline.\
3.) When you create a new material, select either "Shader Graphs/Urp_FlexibleCelShader" or "Shader Graphs/Hdrp_FlexibleCelShader".

All color properties use HDR colors. For the high / low light color, instead of using a separate slider for the intensity, click on the color itself and either adjust the HDR color's intensity slider at the bottom or manually enter a value. 

To Add an Outline:\
1.) Create an extra material slot on the MeshRenderer component.\
2.) Create a meterial using one of the outline shaders found under the "Outline" category.\
3.) Place the outline material in the new material slot.

You'll find two outline shaders under the categories "Outline/Outline" and "Outline/TransparentOutline".
