## In Depth
This node indicates if a point has analysis by a true or false result.

In this example, we gather all Forma elements, select the "proposal" and "site limits" categories, and use them as inputs to run the sun analysis.  The ground results are extracted and used as input for the SunGround.Mask node.  This node output value is based on if the masked point has analysis values (true or false).  This node only search’s inside the analysis area.

For additional information on sun analysis see link below.
https://help.autodeskforma.com/autodeskforma/en/articles/6951253-introduction-to-the-sun-hours-analysis
___
## Example File

![SunGround.Mask](./Forma.Analysis.SunGround.Mask_img.jpg)