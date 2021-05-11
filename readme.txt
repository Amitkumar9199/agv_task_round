**task_1**
#I have successfully solved the case 1
#there are 6 .py files corresponding to different heuristic function 
1.astar_diagonal.py:diagonal distance
2.astar_manhattan.py:manhattan distance
3.astar_euclidean:euclidean_distance
4.astar_with_zero_heuristic:dijkstra
5.astar_admissible_heuristic:
		here I have taken admissible heuristic function as h(n)=(abs(x1-x2)+abs(y1-y2))/2
		where x1,y1 are coordinates of neighbour point 
		and x2,t=y2 are coordinates of end point

6.astar_admissible_new:
		here I have taken h(n)=distance(start,end)-distance(start,neighbour) 

**to run **
1.type "python3 filename.py" in terminal
2.in pygame window you can see graph
3.first left click on graph marks start_position
4.second left click on graph marks end_position
5.further left clicks on graph makes barriers
6.when you are done done with your graph press space bar
7.to clear screen press "c"key

Hope, you like it.
Name:amit kumar
Roll:20CS30003



