## In Depth
This node is used when you already have a Path of Travel with one or more waypoints and want to move a specific waypoint to a new location. Instead of creating a new path or inserting another waypoint, this node modifies the position of an existing waypoint.

In this example, an existing waypoint element (must have more than a start and end point) has been selected and used as an input to the PathOfTravel.SetWayPoint node along with a new location point and index value for the new location. The output is the same Path of Travel element with a modified waypoint location. The last nodes display the original point locations and the updated point locations.



___
## Example File

![PathOfTravel.SetWayPoint](./Revit.Elements.PathOfTravel.SetWayPoint_img.jpg)