---
layout: default
title: node-and-edge-types
parent: Key Concepts
---

## Overview

Network analysis uses the idea of graphs to represent phenomena in the world. We normally think of these as social networks, such as who is a friend with whom. However, networks can represent all manner of objects. Some examples of other network types: 

- **Geogrpahic locations**: We can imagine a network where the nodes are geogrpahic locations. In this case, the respondent could nominate the places they go to. Edges might be places that are visited on the same trip. 

- **Concept map**: A participant might list off (or select from a roster) a series of concepts. Then, they can link concepts as edges if the concepts are used together in some manner. 

- **Multiple roles in an organization**: If you are studying an organization, you might want to collect different edge type for the same nodes. For example, you can have one edge type for "who goes to each other for advice" and another for "who socialises outside work". 

Network Canvas allows you to store and collect multiple edge types in the same interview session. We refer to this feature as "ontological flexibility". 

## Creating multiple node types.

Nodes are created through one of the four name generator stages. Two (Form and Quick Add) enable the participant to create new nodes by pressing the 'add node' button in the lower right corner. Two (large roster and small roster) enable the participant to select a node from a pre-defined list. On all of these screens the first thing you must do is select a single node type to be generated on that screen. 

If a node type is already defined you can use it. Otherwise, you'll have to create a new node type. This involves creating a label for that type (e.g., "Person" or "Location", a 'name' variable that will be used to display the node, a colour which will be consistent through the interview and a create node icon. Presently we have two icons, one that looks like a person and one that looks like a pin on a map. 

xx.getPic(create node type screen). 

Any stage where you enter data about a node will expect you to first indicate the type of node to be used in that stage. Typically you cannot display or edit multiple node types on the same stage.

## Creating multiple edge types

Edges in this sense refer to the connections between the alter nodes. Connections between the participant and the other nodes are considered as variables on that node. As an example consider 'is_family' as an edge type. For relations between the participant and the alter, you would just use a Per Alter form and a boolean variable ("is this person a family member"). However, if you want to connect two alters to indicate they are family you need an explicit edge type to do this.

First, on a sociogram screen you select the type node. Then below you would select a 'prompt'. In the prompt window, you can see options for 'Edge Display and Creation'. If you have an edge type already created you can choose to display that edge type. If you have not already created an edge type, you can create a new edge type by entering it's label in the edge_type text box. Then you will be able to create or see edges of this type on the sociogram. For example, the prompt might be "connect any two people who are family members", and the edge type could be called "edge_family".  

You can only create one edge type at a time. But you can use a second prompt to create a second edge type. This way the participant keeps the same nodes on the screen, typically with the same layout. When the participant presses the down arrow, the old prompt disappears and a new one appears. For example you could have a second edge type to go with the prompt "connect any two people who have worked together", and the edge type could be called "edge_coworkers".
 
 xx.getPic(sociogram prompt create edge screen) 
 
## Displaying multiple edge types 

On the sociogram screen you can only show one type of node and one type of edge at a time. This is because each stage should only be a simple series of actions for the participant. However, if you want to rapidly alternate between edge types in conversation with the participant, try the Narrative Interface screen. This screen does not collect any new data directly. Instead, it allows you to turn on and off the display of variables related to nodes. So you could select edge_family to display the family connections and then select 'edge_coworkers' to display the coworker connections. 

xx.getPic(narrative interface -> inset on multiple edge types)

## Displaying multiple node types?

Presently, Network Canvas constrains the user to only display one node type per stage. Displaying different node types per stage is a 'road map' feature. 

## Managing multiple node and edge types 

You can use multiple node types and have multiple edge types per node. To manage both the types of nodes and edges as well as the data associated with each node and edge type, you can click on the [[xx 'codebook']]. Here it will display all the types with their icons, colours, and associated variables. 
