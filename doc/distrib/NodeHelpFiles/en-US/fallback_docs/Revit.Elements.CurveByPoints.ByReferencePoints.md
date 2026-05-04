## In Depth
This node creates a Curve By Points element in Revit using a list of existing Reference Points.  The input points requires one or more Revit ReferencePoint elements. These points define the path of the curve in the order they are provided. The node then creates a Revit curve that passes through those reference points, which can be used in adaptive components, conceptual massing, divided paths, or other workflows that rely on reference geometry.

In this example, several Reference Points are created in the Revit environment and passed into CurveByPoints.ByReferencePoints. The node generates a Curve By Points element through the input points. The output of this node is the resulting Revit Curve By Points element.
___
## Example File

![CurveByPoints.ByReferencePoints](./Revit.Elements.CurveByPoints.ByReferencePoints_img.jpg)