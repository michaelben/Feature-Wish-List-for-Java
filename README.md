Feature-Wish-List-for-Java
==========================

Feature wish list I want most for Java

Language feature I want most:
  1. raw string format or triple-quote string format like in Python.
  2. foreach loop with (index, element), like for (index, elment) in enumerate(list) in Python.
  3. 

Library feature I want most:
  1. Polygon2D in Java2D.
     It seems Polygon2D is accidentally missing in Java2D. There is Polygon class but it is for integer. It is a pain to convert float/double to integer each time to render a polygon on screen.
  2. Shape2D(including Polygon2D) with ArrayList<Point2D> data model. Currently Polygon has 2 int arrays as its data model. Path2D has an PathIterator. But I wish the data model is ArrayList<Point2D> such that when a point's position is changed, the shape is changed automatically. Also it would be easy to get prev and next points for a point in a shape, which is common for geometry operation.
  3. This is missing area calculation method for Shape, even in Area class.
  4. 
