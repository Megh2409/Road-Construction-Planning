# Road-Construction-Planning
Road Construction using Highway Planning

Our project aims to help authorities by providing them with the most profitable path for road construction for a given map and the sequence in which these roads can be addressed so that it would be convenient for both the authorities as well as the general public.
We have also included a deadline section so that the roads that take more than the allocated time are highlighted and if necessary removed. Also, a check for hindrance detection is added which can be used when we have a limited number of resources and a proper allocation of these resources is required. For this, we take inputs for resources which can refer to asphalt, machinery, mortar, etc. Then we require the maximum resources needed for each road, the amount of resources allotted for each road, and available resources, based on which a safe sequence is generated that prevents any unwanted stoppage of work.

Working Plan
First, we take inputs for the number of roads
Then we will take inputs for the formation of the map in form of a graph for all the different roads
Then based on the graph we will apply the Dijkstra algorithm and find the shortest distance possible between the desired cities
This distance is saved as a parameter of size for the roads
Also, the route of the shortest path will be displayed
Then we read the utility, traffic, and deadline for all the roads
Based on these inputs we check for clashes between the priorities
If present the clashing is handled
Then the required sequence is generated
Based on the sequence we find the waiting and completion times for the roads
Now we check if the roads can be completed within their allocated time
If the deadline is crossed then an error message “DEADLINE NEEDS TO BE COMPROMISED” is displayed.
If the deadline is not passed the generated sequence is displayed and we move to the second part of the project
Here we read the number of resources needed for each road, the maximum resources needed for each road, the number of resources allotted for each road, and the available resources
Based on this a safe sequence is generated
If the sequence is not generated then an error message is displayed.

