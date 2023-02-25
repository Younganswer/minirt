# miniRT
### My first RayTracer with miniLibX
<br/><br/><br/>

## Summary
#### This project is an introduction to the beautiful world of Raytracing. Once completed you will be able to render simple Computer-Generated-Images and you will never be afraid of implementing mathematical formulas again.
<br/><br/><br/>

## Install
	$ make [-jN] (all)
<br/><br/><br/>

## Usage
	$ ./miniRT /path_to_scene/your_scene.rt
* File must end with `.rt` extension
* Scene file has 6 elements:
	* Ambient light:
		* `A ratio [color]`
	* Camera
		* `C position orientation fov`
	* Light
		* `L position ratio [color]`
	* Sphere
		* `sp position diameter color`
	* Plane
		* `pl position normal color`
	* Cylinder
		* `cy position axis diameter height color`
* Elements in capital letters are mandatory
* Color of light is used in bonus part
<br/><br/><br/>

## Result
* Mandatory(scene01.rt)
![Mandatory(scene01.rt)](./result/mandatory.png)
* Bonus(scene02.rt)
![Bonus(scene02.rt)](./result/bonus.png)