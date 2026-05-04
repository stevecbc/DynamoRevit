## In Depth
This node takes Dynamo geometry objects and creates import instance in your Revit model, making the geometry visible in a Revit view.  All geometry is grouped into one element.

In this example a sphere and a cuboid are created in Dynamo, a view is selected and used as the inputs to the ImportInstance.ByGeometriesAndView node.  The output creates a single piece of Revit geometry in a specified view.
___
## Example File

![ImportInstance.ByGeometriesAndView](./Revit.Elements.ImportInstance.ByGeometriesAndView_img.jpg)