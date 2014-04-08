=================
	 Set 3
=================
1. loc1.getLocation();

2. loc2

3. (3,5)

4. 135

5. Whatever direction the input point is located at.

=================
	 Set 4
=================
1. ArrayList<Location> getOccupiedLocations(Location loc);

2. boolean isValid(Location loc);

3. The Super Class of the location.

4. No, because the size of the array will be undetermined.

=================
	 Set 5
=================
1. Color, Location, Direction

2. The color is red unless you set it before hand

3. So you can change the properties of the bug.

4. No, you can't have two of the same actor in the grid. Although it can be placed into a grid, remove itself and then put itself back.

5. setDirection(getDirection() + Location.LEFT);

=================
	 Set 6
=================
1. if (gr == null) return false;

2. return (neighbor == null) || (neighbor instanceof Rock);

3. instanceof, gr

4. neighbor

5. Bug, Rock, Flower

6. it returns false

7. Yes it is needed in the move method because the bug needs to know it's location.

8. Because the color is automatically set unless the setColor method has been called.

9. No, because it sets a flower one location behind itself, not ontop of itself. This is also because you cannot have two actors on one location of the grid.

10. flower.putSelfInGrid(gr, loc);

11. 4 times