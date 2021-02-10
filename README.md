This repository contains versions of Flexible Cel Shader built for URP and HDRP.

When I get some time, I might try to fill out this readme, but for now what you can do is:


1.) Clone / copy the repo into your project.

2.) When you create a new material, select either "Shader Graphs/Urp_FlexibleCelShader" or "Shader Graphs/Hdrp_FlexibleCelShader".


A few things to note:

1.) I switched all color properties to use HDR colors. For the high / low light color, instead of using a separate slider for the intensity, click on the color itself and either adjust the HDR color's intensity slider at the bottom or manually enter a value (if you manually enter, you shouldn't be restricted by the slider's limit) 

2.) I added an emission Color property, If you add an emission map, you can adjust this color to control what the emission looks like.


For Adding Outlines:

For the outline shaders in this case, I ended up implementing the outline as a separate shader rather than a separate pass within the same shader (I don't think shader graph supports multiple passes atm?). In order to add an outline to one of your renderers, what you'll have to do is create an extra material slot and place a material using one of the outline shaders into that slot.

You'll find two outline shaders under the categories "Outline/Outline" and "Outline/TransparentOutline".