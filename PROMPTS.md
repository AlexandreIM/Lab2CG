The current code draws a sphere, one green bunny, one golden bunny, and one blue bunny, all side by side. How do I rewrite the code to draw 8 blue bunnies in a circle, surrounded by 14 golden bunnies in a diamond shape, surrounded by 24 green bunnies in a rectangle shape (like the brazilian flag)?

The bunnies are all properly drawn. Now I want to animate them, so they all move along the perimeter of their respective shapes in a clockwise direction.

The bunnies now move. Next, they should hop while they move. The hops should start from one vertice of the polygon to the next one on the movement path (for the circle, it can be every 90 degrees).

Next, the bunnies should point in the direction they are moving (consider the front of the bunny being opposite of the tail)

The bunnies now move in the appropriate path, but they turn instantly when passing from one edge of the polygon to the next edge. Now, the polygon paths should have round edges, so the bunnies make smooth turns.

The bunnies now have proper movement paths. Next, their hops shoul be animated, so that they lean forwards when rising and lean backwards when falling.

The bunnies now have their full movement cycles. Next, they need to have "hats" (just a small brown disc on top of their heads) that remain attached to them troughout their movement.

The bunnies now have their hats. Next, their movement speed should be calculated circularly, so that a bunny in a different path from another bunny will complete said path in the same time.