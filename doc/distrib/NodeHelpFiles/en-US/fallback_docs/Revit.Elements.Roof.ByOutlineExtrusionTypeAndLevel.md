## In Depth
This node creates a roof using Revit’s extrusion roof creation method. The outline input defines the section/profile shape of the roof, and Revit extrudes that profile to create the roof form.

In this example, several points are created to generate a polycurve (profile shape) and a reference plane. These are used as inputs to the Roof.ByOutlineExtrusionTypeAndLevel node along with a roof type, level, and extrusion start and end values. The output is a Revit roof.
___
## Example File

![Roof.ByOutlineExtrusionTypeAndLevel](./Revit.Elements.Roof.ByOutlineExtrusionTypeAndLevel_img.jpg)