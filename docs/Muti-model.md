# muti-model database documentation

## Introduction of Muti-Model

1. The muti-model is an advanced concept that takes the mutiple DBMS and merge them into one platform and able them to interact with each other and use other format to their benifits.

2. The difference between muti-modal and muti-model is at the architecture layer. The former one describes the different types of files like speech, audio and video. The latter describes as the different types of databse management system that exists

## Without a Sinle System Scenario

The `muti-model` database includes three different structure of data. 

| Types of Data     | File Type Example   | Formal Definition                                                |
| ----------------- | ------------------- | --------------------------------------------------------------- |
| Structured        | Relational Database | Structured data follows schemas and table rules; often relational with well-defined connections. |
| Semi-Structured   | JSON, XML, HTML     | Semi-structured data has patterns but lacks strict schemas and table structures. |
| Unstructured      | Text, Video, Speech, Audio | Unstructured data is typically plain and requires specialized techniques to extract information from various sources. |

the chanllange is that is complicated with *query the data* and *modification of the data*.



## With a Sinle System Scenario

`ArangoDB` and `OrientDB` are both single databse storage and single DBMS with both are open source and free to use.

### Modification Stratgy

1. Mediator with system called `polyglot persistence`. basically adapts the system and act as middleware processor to take the information to unified processing center and distribute them out. example **BigDawg** and **DBMS+**.

2. Single database platform and DBMS for mutiple models which is what we are using.



### Preliminaries on Data Models

1. Relational Model --- subset of carterisan product and data are represented as tuples.
2. Semi --- XNL and JSON, Graph, Hashes, Array... which they depending on their data structure to store the value. The benifits are flexibility and more in modifible
3. Graph Model --- base on the definition of the mathmatical term graph construcuted by vertices and edges `Transactional databases` - small graphs and set of linguistic trees or chemical compounds `non Transactional databases` which is a big large graph with serveral compoennets corresponding to the oepratation of shortest pathing and branching subgraphs.


### Four Different Apporaches to the Database Extensions of Original Model

1. Creating entire new adaption model
2. Creating extension model on top of the funcitonariies that it exists
3. Creating new interface
4. No changes 3 and 4 are usually graph datatbase and key/value database and 1 and 2 are mostly conludmn and documents and relational database
(Side Fact : document and relational are by far the most popluar databse that it exists at 2018 recoring to research)


