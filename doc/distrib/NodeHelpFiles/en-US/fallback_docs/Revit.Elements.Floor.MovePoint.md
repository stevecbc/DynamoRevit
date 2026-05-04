## In Depth
The node takes a floor, a point, and a new target location or elevation value, depending on the node input structure. The output is the updated Revit floor after the point has been moved.

In this example a floor is created and input into the gate node.  The floor points are exacted and new offset (Z-axis) points are generated.  The original extracted floor points along with the new offset values and the floor are input into the Floor.MovePoint node.  The output is the same floor with different offset points.  Run this example as is, then run it again with the gate node "Open."
___
## Example File

![Floor.MovePoint](./Revit.Elements.Floor.MovePoint_img.jpg)