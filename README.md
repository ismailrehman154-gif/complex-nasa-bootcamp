# NASA Facility Locations

Lists NASA's facility locations (around 400 of them) and shows the current temperature at each one.

![NASA Facility Locations screenshot](screenshot.jpg)

The hard part is the chain. First you fetch the facilities, then for every single one you fire off a second request to a weather API using its coordinates, and stitch it all together as results trickle in. One API feeding another, 400 times over.

Vanilla JavaScript with fetch. My code is on the `answer` branch.
