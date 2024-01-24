# Assignment-1 for Object-Oriented Anlysis & Design
This program defines a set of classes representing different shapes such as rectangles, ovals, squares, and circles. It utilizes a canvas (CCanvas) to generate a specified number of random shapes, ensuring uniqueness based on their information (dimensions and type).

## This program ensures uniqueness with hashcodes created from object parameters

Rectangle Example:

```
@Override
public int hashCode() {
  return Objects.hash(width, length);
}
```

Leveraging HashSets:


```
this.shapeSet = new HashSet<>();
```

## To create a canvas, and generate random shapes, instantiate a new CCanvas object

```
CCanvas canvas = new CCanvas();
```
