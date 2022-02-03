# time-scaled-maps
Creating warped maps that represent public transport travel times instead of physical distance

Input: city / region + radius
Output: sexy time-scaled map

	1. Get GIS file (incl. points of interest, lines, districts, lakes, etc.)
	2. Get GTFs public transport data
	3. Extract & clean up stops (coordinates + names)
	4. Calculate distance matrix + densify
	5. Calculate embedding in 2D based on distance matrix
	6. Overlay embedding with original points
	7. Calculate warping (bidimensional regression)
	8. Apply warping to original map
	9. Render original map in GIS program
	10. Automate
	11. Web interface
		a. Design
		b. …

