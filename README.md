# DV-Dijkstra-2
Re-build of the Dijkstra DV project, except this time, the camera is actually facing the right way.
As you can see, the player just randomly goes up infinitely and I don't know why, but it at least gets to the goal. It just...skips all the other steps to get there.


From the OG DV build:
DV-Djikstra
Dick Van Dijk-Stra (aka D.V. for Dijkstra)

note: It's currently buggy and only goes toward the last target because the onCollision function I wrote broke and I had to revert to a save file. My group is leaving for CA in ten minutes, so I'll clean it up for the Project version on the 17th. -ZG

note pt 2: the scripts are in the Assets folder - I need to rework my arrive function so that it will actually collide with the waypoint instead of stopping and looking at it. Then I need to rewrite the onCollision function so it switches targets after it hits the waypoints. Then I have to make it look nice.

