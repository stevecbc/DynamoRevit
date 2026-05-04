## In Depth
This node is exposing the internal identifier that Revit uses behind the scenes for units and specs. Instead of relying on display names (which can vary by language or settings), Revit uses these TypeId strings to ensure consistency across API's and more.

In this example the Length Spec type is chosen and used as the input to the ForgeType.TypeId node.  The output is a string stating the ForgeType.TypeId.
For more information on ForgeType see below.
https://help.autodesk.com/view/RVT/2025/ENU/?guid=d9fcf276-9566-de83-2b0b-d89b65ccc8af
___
## Example File

![ForgeType.TypeId](./Revit.Elements.ForgeType.TypeId_img.jpg)