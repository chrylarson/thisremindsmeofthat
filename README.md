thisremindsmeofthat
===================

Neo4j based associative notebook using py2neo to interact with the database

I want to create a notebook that works more naturally with the way that my mind works. 

I love making assocations between things.  The more disparate the better.  I often think metaphorically. 

I wish there was a way to accumulate those associations.  I wonder if they would grow into something larger.  What if a strange connection between x and y could, months later, be easily accessible and connected to a new insight about z. 

I got introduced to Neo4j a couple months ago.  It seems like the perfect foundation for building this associative notebook. Plus, there's a way to interact with neo4j using python thanks to py2neo.

I've played with this idea before, along with my friend Chris. I've never been quite able to bring the idea to life. I think with Neo4j and py2neo I can.  A graph database already does what I've dreamed about doing. Now it's a matter of working out an intuitive way to add a note node to the graph and discover relationships between it and previous nodes. 

Since I'm not good at writing code this will be easier said than done.


How to install and run
======================

Install neo4j

Install py2neo

Clone thisremindsmeofthat repo

from the python cli 
```python
  from trmtCmdLine import *
  cmdLine()
  
  enter command: add "New thing that reminds me of another thing"
  ```
  
  
