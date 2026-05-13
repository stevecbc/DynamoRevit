## In Depth
This node removes an existing waypoint from a selected PathOfTravel element in Revit which allows you to recalculate the travel path.

In this example, an existing waypoint element (must have more than a start and end point) has been selected and used as an input to the PathOfTravel.RemoveWayPoint node along with an index value to remove. The output is the same Path of Travel element without the point identified at the specified index. The last nodes display the change from the original path to the modified path.
___
## Example File

![PathOfTravel.RemoveWayPoint](./Revit.Elements.PathOfTravel.RemoveWayPoint_img.jpg)