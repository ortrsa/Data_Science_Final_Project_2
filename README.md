# Data Science Final Project

## Overview 
- This project is the final project of Data Science course and written in python(jupyter notebook).    
- It is direct continuation of the task from last semester, you can find the last project [Here](https://github.com/ortrsa/Data_Science_Final_Project).
- In this project, we walked through machine learning from basic models to more advanced one.
- In the project I tried to move forward along with the book (Hands-on Machine Learning) and slowly improve the models.
- This project was built from 4 parts:    

**part1:** improving the project from last semester with the new knowledge we gained in the semester,  
In this part I started directly from the Ensemble Learning because in its previous part we tested a lot of regular models,  
The main models were: Ada boost(with DecisionTree), Xgboost and RandomForest.  
In this case the Ada boost give us the best result (73.27%) the Ada boost improved the result by 1.3% (from last semester).
Because these are health tests we want to reduce the features as much as possible.  
A reduction with the help of feature_importances function is more effective then PCA in this case because in this way we can reduce the cost of the tests and make it easier for the subject (Coincidentally, the result is also better).
After reducing 6 out of 13 features with the help of feature_importances function, we reached 72.77 percent and downloaded almost half of the features.


**part2:** implement `GraphAlgo` class that contains more advanced functions on graph.      

*(you can read all about the functions in [here](https://github.com/ortrsa/Ex3/wiki/Functions-explanation).)*
  
**part3:** compare running time and correctness between this project, [Ex2](https://github.com/ortrsa/ex2)  and [networkx](https://github.com/networkx/networkx).  

  - To see time compareition on circle graphs click **[here](https://github.com/ortrsa/Ex3/wiki/Time-comparison_-new)**.
  - For correctness report outputs click **[here](https://github.com/ortrsa/Ex3/wiki/circle-graph-time-comparison-and-correctness-check)**
  - *(you can find the correctness file in the src folder feel free to verified this output)*

  
# Model explain
 





# How it's work..
After initializing the graph, the fun part begins.  
In GraphAlgo we implement advanced functions with some familiar algorithms like BFS, and dijkstra's.  


`shorest_path()` - use [Dijkstra's Algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm) to find the shortest path In the most efficient way.  
**Dijkstra's**  

![Alt Text](https://github.com/ortrsa/Ex3/blob/master/img/dWtprX5.gif)  


`connected_component()` - make 2 lists, list 1 contain all the nodes that you can get *from* the first node, and list 2 contain all the nodes that can get *to* the first node, and take the intersection between list 1 and 2.  
We are able to make these lists using [BFS](https://en.wikipedia.org/wiki/Breadth-first_search).  
**BFS**  

![Alt Text](https://github.com/ortrsa/Ex3/blob/master/img/KcsN.gif)  
  
  


`plot_graph()` - use [matplotlib](https://matplotlib.org/gallery/index.html) library to draw the graph.  

**A5 graph from data folder**  

![Alt Text](https://github.com/ortrsa/Ex3/blob/master/img/A5_graph.png)

# Links:
- [Dijkstra's Algorithm - Wikipedia](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
- [BFS - Wikipedia](https://en.wikipedia.org/wiki/Breadth-first_search)
- [Directed_graph - Wikipedia](https://en.wikipedia.org/wiki/Directed_graph)
- [correctness file output - Wiki](https://github.com/ortrsa/Ex3/wiki/circle-graph-time-comparison-and-correctness-check)
- [Ex2](https://github.com/ortrsa/ex2)
- [Functions - Wiki](https://github.com/ortrsa/Ex3/wiki/Functions-explanation)
- *(you can see the structure of the project in this [WikiPage](https://github.com/ortrsa/Ex3/wiki/Inherent-diagram).)*

# About:
This project is part of oop course of Ariel university and made for study purposes.  
This project was made by Or Trabelsi and Nadav Epstein, for more information please contact me, email - ortrsa@gmail.com.
