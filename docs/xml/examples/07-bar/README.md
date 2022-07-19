<!-- 

Auto Generated File DO NOT EDIT 

-->

# Bar

Draws a very simple horizontal bar with current metric value


```xml
<component type="bar" metric="accl.x" units="m/s^2" />
```
<kbd>![07-bar-0.png](07-bar-0.png)</kbd>



## Positioning

Place the bar component inside a `translate` to move it around

## Size

Use `width` and `height` to control the size of the component, in pixels


```xml
<component type="bar" width="100" height="100" metric="speed" units="kph" />
```
<kbd>![07-bar-1.png](07-bar-1.png)</kbd>


## Colours

Use `fill` and `outline` to change the fill and outline colours

Specify the colours, as usual, in r,g,b or r,g,b,a


```xml
<component type="bar" metric="accl.y" units="m/s^2" fill="255,255,255,128" />
```
<kbd>![07-bar-2.png](07-bar-2.png)</kbd>



```xml
<component type="bar" metric="accl.y" units="m/s^2" outline="255,0,255" />
```
<kbd>![07-bar-3.png](07-bar-3.png)</kbd>


To get rid of the outline completely, specify an alpha of `0`


```xml
<component type="bar" metric="accl.y" units="m/s^2" outline="255,0,255,0" />
```
<kbd>![07-bar-4.png](07-bar-4.png)</kbd>


Use `zero` to change the colour of the zero marker


```xml
<component type="bar" metric="accl.y" units="m/s^2" zero="255,0,255" />
```
<kbd>![07-bar-5.png](07-bar-5.png)</kbd>


Use `bar` to change the colour of the bar itself


```xml
<component type="bar" metric="accl.y" units="m/s^2" bar="255,0,255" />
```
<kbd>![07-bar-6.png](07-bar-6.png)</kbd>


Use `h-neg` and `h-pos` as rgba values to control the highlight colours of ends of the bar


```xml
<component type="bar" metric="accl.y" units="m/s^2" h-neg="255,0,255" />
```
<kbd>![07-bar-7.png](07-bar-7.png)</kbd>



```xml
<component type="bar" metric="accl.y" units="m/s^2" h-pos="255,0,255" />
```
<kbd>![07-bar-8.png](07-bar-8.png)</kbd>


## Outline Width

Use `outline-width` to control the width of the outline


```xml
<component type="bar" metric="accl.y" units="m/s^2" outline-width="3" />
```
<kbd>![07-bar-9.png](07-bar-9.png)</kbd>



## Max & Min Values

Use `max` and `min` to control the max and min values that the bar will display


```xml
<component type="bar" metric="accl.y" units="m/s^2" max="5" min="-1" />
```
<kbd>![07-bar-10.png](07-bar-10.png)</kbd>



```xml
<component type="bar" metric="accl.y" units="m/s^2" max="10" min="0" />
```
<kbd>![07-bar-11.png](07-bar-11.png)</kbd>


