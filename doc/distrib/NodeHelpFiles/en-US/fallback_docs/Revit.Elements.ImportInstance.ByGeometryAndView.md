## In Depth
This node takes Dynamo geometry objects and creates import instances in your Revit model, making the geometry visible in a Revit view.  All geometry are independent element (not grouped).

In this example a sphere and a cuboid are created in Dynamo, a view is selected and used as the inputs to the ImportInstance.ByGeometry.  The output creates each individual piece of Revit geometry in a specified view.
___
## Example File

![ImportInstance.ByGeometryAndView](./Revit.Elements.ImportInstance.ByGeometryAndView_img.jpg)