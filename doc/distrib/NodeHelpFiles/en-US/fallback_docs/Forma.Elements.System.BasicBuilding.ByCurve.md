## In Depth
The BasicBuilding.ByCurve node creates a building unit from a closed curve. You must provide a closedCurve (a polycurve), a functionId, a program, and any optional holes (closed curves).

In this example, number sliders create a rectangle that serves as the closedCurve input for the BasicBuilding.ByCurve node. The node also takes a functionId (example Residential, Commercial) and a program (example, LIVING_UNIT, CORE) as inputs. You can optionally include holes by providing closed curves.  The resulting Unit output is converted into a floor plan, which is then used to generate a BasicBuildingByPlan element and sent to Forma. 
The valid values for functionId can be found in Forma under Settings > Buildings > Functions, and the valid values for program are located under Analyze > Unit distribution > Unit filter.

___
## Example File

![BasicBuilding.ByCurve](./Forma.Elements.System.BasicBuilding.ByCurve_img.jpg)