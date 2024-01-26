# BFST23Group13
# Project Requirements:

1. Allow the user to specify a data file for the application. The system should support loading a zipped .OSM file, but you may support other formats as well. 

2. Include a default binary file embedded as a resource of the program, which is loaded if the user does not choose another input file at start-up. 

3. Draw all roads in the loaded map dataset, using different colors for the different types of roads in the dataset. 

4. Show any rectangle of the map, as indicated by the user. 

5. Show the current zoom level, e.g., in the form of a graphical scale bar.

6. Allow the user to change the visual appearance of the map, e.g., toggle color blind mode, or customize which elements to show. 

7. Where appropriate, draw other cartographic elements. 

8. Adjust the layout when the size of the window changes.

9. Feature a coherent user interface for your map and accompanying functionality. Specifically, decide how the user can interact in a user-friendly and consistent manner with the user interface. 

10. Unobtrusively show (*either continuously or on hover*) the name of the road closest to the mouse pointer, e.g., in a status bar. 

11. Allow the user to search for addresses typed as a single string, and show the results on the map. The program must handle ambiguous user input appropriately, e.g., by displaying a list of possible matches. 

12. Make the computation of a shortest route on the map between two points somehow specified by the user possible (*e.g., by typing addresses or clicking on the map*). 

13. Allow the user to choose between routes for biking/walking, and cars. Car routes should take into account speed limits/expected average speeds. A route for biking/walking should be the shortest and cannot use highways. 

14. Output a textual description of the route found in Item 1 giving appropriate turn instructions. E.g., “Follow Rued Langgaardsvej for 50m, then turn right onto Røde Mellemvej.” It should be possible to copy the description (*as plain text*) to the clipboard. 

15. Allow the user to add something to the map, e.g., points of interest. 

16. Be fast enough for convenient use, even when working with a complete data set for Denmark. The load time for .OSM can be hard to improve, but loading a binary file should be fast. After the start-up the user interface should respond reasonably smooth. (*The lectures on spatial data structures and on implementing Dijkstra will be useful to achieve this*) 
