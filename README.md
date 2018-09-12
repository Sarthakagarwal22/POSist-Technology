# POSist-Technology
1) Run the code on any ide
2) Input the following as sample input to create a genesis node with node id = 2, node vale as 13 and node owner name as sarthak 
    1
    2
    13 
    Sarthak
    11
    
3) Create another node and check if it can be added or not
    1
    2
    13 
    Sarthak
    2
    4
    15
    Hello
    11

This input creates only one genesis node as 15>13

4)
    1
    2
    13 
    Sarthak
    2
    4
    5
    Hello
    2
    8
    6
    Hello123
    11
This creates two nodes since (6+5) < 13
