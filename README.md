# Random_Points_In_Spline_Zone_Plugin
 The simplest random point generator inside any polygon defined by a spline. To do this, call the GenerateRandomPointInSplineZone function and give it a Spline Сomponent. 
![HighresScreenshot00000](https://user-images.githubusercontent.com/72274260/194704066-a76f1e09-0850-498a-a449-ba5d1d87489a.png)
 You can check the plugin using AActor SplineTest and specify the necessary settings in details.
![image](https://user-images.githubusercontent.com/72274260/194704171-5a820b2b-d1de-4501-97d4-7ca1fe552d00.png)
The plugin works on polygon triangulation.Я

BUGS.
1. Most likely, I use a slightly incorrect formula to determine the random point, so in the case of the simplest shapes, the points given out will tend to the corner (although I'm not sure).

Protected by MIT.
