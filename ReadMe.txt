Folder 'graph' has '__main__.py', so it can be executed as a python module by running "python -i graph" from console when in it's directory. 

It can also be launched by simply running launch.bat. 

'graph.py' inside of folder 'graph' contains function quickSort and classes Graph, Node and Djikstra. 
sort function works like this: sortedList=quickSort(list) 
create graph like this: myGraph=Graph() 
create node like this: node=Node(label) 
add node to graph like this: myGraph.addNode(node) 
connect one node to another like this: node1.connect(node2,distance) 
create object of Djikstra: alg=Djikstra(myGraph) 
get path as a list and a distance like this: path,distance=alg.searchPath(city1,city2) 
there is also a function in '__main__.py' for displaying path to console: printPath(city1,city2) 
 
'__main__.py' also automatically prints a few tests of quickSort and searchPath. 