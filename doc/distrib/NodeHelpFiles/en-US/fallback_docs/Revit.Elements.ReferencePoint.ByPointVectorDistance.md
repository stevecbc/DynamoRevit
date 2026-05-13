## In Depth
This node creates a Reference Point in the Revit environment by starting from an existing point, moving in a vector direction, and using a specified distance.  This node is used in the Revit Conceptual Mass / Adaptive Component environment, where Reference Points can drive forms, curves, hosted adaptive points, or parametric geometry.

In this example, a point is created along with a vector and used as an input to the ReferencePoint.ByPointVectorDistance node along with a distance value. The output is a Reference Point.
___
## Example File

![ReferencePoint.ByPointVectorDistance](./Revit.Elements.ReferencePoint.ByPointVectorDistance_img.jpg)