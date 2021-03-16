## Transforms:
* The transform property comes in two different settings, two-dimensional and three-dimensional.
Each of these come with their own individual properties and values.

## Transform Syntax:
* div {
 *  -webkit-transform: scale(1.5);
  *    -moz-transform: scale(1.5);
   *     -o-transform: scale(1.5);
    *       transform: scale(1.5);
}

## 2D Transforms:
1. 2D Rotate:The transform property accepts a handful of different values. The rotate value provides
the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative 
value will rotate the element counterclockwise
2. 2D Scale:
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, 
therefore any value between .99 and .01 makes an element appear smaller while any value 
greater than or equal to 1.01 makes an element appear larger.

3. 2D Translate:The translate value works a bit like that of relative positioning, pushing and pulling an element in different
directions without interrupting the normal flow of the document. Using the translateX value will change the position 
of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

4. 2D Skew: The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.
The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal
axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, 
declaring the x axis value first, followed by a comma, and then the y axis value.%p

## 3D Transforms:
1. 3D Rotate:With three-dimensional transforms we can rotate an element around any axes. To do so, 
we use three new transform values, including rotateX, rotateY, and rotateZ.
2. 3D Scale.
3. 3D Skew.
