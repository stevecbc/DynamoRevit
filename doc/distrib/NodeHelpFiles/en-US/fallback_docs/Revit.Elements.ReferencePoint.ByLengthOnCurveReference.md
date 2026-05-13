## In Depth
This node creates a Reference Point on a Revit curve reference at a specified distance along that curve.  This node is used in the Revit Conceptual Mass / Adaptive Component environment, where Reference Points can drive forms, curves, hosted adaptive points, or parametric geometry.

In this example, a model curve is created and used to generate an element curve reference. This reference is used as an input to the ReferencePoint.ByLengthOnCurveReference node along with a defined length. The output is a point along the element curve reference.
___
## Example File

![ReferencePoint.ByLengthOnCurveReference](./Revit.Elements.ReferencePoint.ByLengthOnCurveReference_img.jpg)