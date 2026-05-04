## In Depth
This node extracts the visible Revit geometry from a selected Revit element and converts it into Dynamo geometry.

In this example, a wall is selected and used as an input to the Element.GetGeometry node along with a detail level value of Fine (other options are Medium, Coarse).  The output is a solid and is used to extract the volume and create a bounding box.


___
## Example File

![Element.GetGeometry](./Revit.Elements.Element.GetGeometry_img.jpg)