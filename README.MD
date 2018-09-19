Geometry - JavaScript library for working with objects in a two-dimensional coordinate system. Right now there is only the Point class.

In progress.

Examples: 

```
var point1 = new Point(100,42);
var point2 = new Point([10,10]);//just a different constructor param.

console.log(point1);

point1.add(1,1);//point1 is now: x:101 y:43
point1.add(point2);//point1 is now: x:111 y:53
console.log(point1.x, point1.y);

//chaining is possible as well:
var point3 = point2.clone().multiply(2);
```
