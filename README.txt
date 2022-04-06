Description:
This project is designed to take an input file of Eurail travel times, store 
the data in an undirected, weighted graph, calculate shortest path using 
Dijkstra's Algorithm, and create an output GraphViz file of the entire 
system route map with the itinerary highlighted. This project's main focus 
is on becoming familiar with graphs.

Dependencies:
graph.py
shortest_path.py
Empty.py
adaptable_heap_priority_queue.py
heap_priority_queue.py
priority_queue_base.py
ask_input.py
TripPlanner.py
project5.py

Requirements:
- Python 3
eurail.txt
argparse

Run as:
$ python project5.py --itinerary itinerary eurail.txt

Operation:
Enter origin/destination cities, answer y/n for quit and saving itinerary.

Output:
itinerary.gv file
