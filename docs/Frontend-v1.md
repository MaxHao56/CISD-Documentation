# Frontend-v1


## Project Structure





## Framework documentation on json and commands and build for the project and tools used


## Programming languages ts, css and javascripts

## testing

## Techniques






programming lanauages  = typescirpts mainly its pacakages
                       = CSS mainly its packages
                       = React/Next.js mainly its pacakges




techniques and some data structure handling thinking


# muti-model database documentation

the muti-model database includes three different structures of data. 
structure -> key/values and tables with relational databases
semi-structure -> json file/ xml file and etc
and unstructure data -> like plain text and picture basically things that just scraped out of the somewhere


introduction ->

1. without one single system
2. with one single system -> which we are talking about arangoDB and OrientDB. The reason is that it contains one single database storage and one dbms and both are open source and free

   to make query and modfication easy. it has stragegies. the first strategy is to create a mediator with system called polyglot persistence and it adpapts acts middle processsor or a middleware that takes information to unified processing center and distrubute them out like BigDawg and DBMS+.

   the documentation focus on the second stragey and making single databse that stores mutiple model and have its managmenet system

  the difference between muti-modal and model is the file difference the modal stands for different formats of the file. speech, video and text and etc. the model meaning different database system and archtietctyre.



PRELIMINARIES ON DATA MODELS


relational model - subset of the carterisan product and data are represented as tuples
semi- XML and JSON and meaning they are relaying on their data structure to store the value which makes it more felxible
key and valuse/ json, dicto and hashes and array

graph model -  base on the definition of the mathmatical term graph construcuted by vertices and edges
    Transactional databases - small graphs and set of linguistic trees or chemical
compounds
    non Transactional databases which is a big large graph with serveral compoennets corresponding to the oepratation of shortest pathing and branching subgraphs and etc


There are four different appaoarches to the database extension of the orignal model.
(1) creating entire new adaption model 
(2) creating extension model on top of the funcitonariies that it exists
(3) creating new interface
(4) no changes
3 and 4 are usually graph datatbase and key/value database and 1 and 2 are mostly conludmn and documents and relational database

as it seems the document and relational are by far the most popluar databse that it exists since 2018

Multi-model databases employ various optimization strategies, including inverted indexes, B-trees, materialization, hashing, and bitmap indexes, tailored to the specific data models they support.
------ question herer ------- how did it do it and why did make it this way. and one more intresting thing is almost like 99% of them supports database query lanauges so how do they link the database to sql like even nosql and document and also josn file...
[i guess they heavily reply on the dbms that they designed]

