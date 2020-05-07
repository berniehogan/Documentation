---
layout: default
title: Codebook
parent: Key Concepts
---

## Overview 

The codebook is a place for you to examine the variables that will be included with your protocol file. Since Network Canvas uses a model of stages, different variables will be used in different stages (and sometimes multiple stages). Thus, it is useful to have a single place to look at all the data collected in an interview at a glance.

Data in the codebook is organised by the type of object that is associated with the data. The primary objects are egos, alter nodes, and alter edges. Ego refers to the participant. Under ego you will see variables that are collected in _Ego Form_ stages. Alter nodes (or sometimes simply 'alters' or 'nodes') refer to the nodes that are created or selected during an interview. Data on alter nodes are collected from a variety of other screens such as the Name Generator (using quick add) stage or the Ordinal Bin stage. Edge data is usually collected using the "Per Alter Edge Form". 

## Different node types 

Network Canvas allows you to collect multiple node types as well as multiple edge types. The codebook is organised such that we see the name of the node type (such as "person" or "location") followed by the variables that can be associated with that node. 

## Separating variables and stages 

Internally, Network Canvas separates the varaibles you collect from the stages where the data is entered. This is because you might want to use (or even edit) a variable in multiple stages. A variable is created through a stage. For example, when you want to create an ordinal variable for a node like "How close are you", ranging from 'extremely close' to 'not close at all'. Then you can use this variable elsewhere in the program. 

This is especially useful for layout variables. When you first create a sociogram stage Architect will prompt you to create a layout variable. This variable will store the X and Y coordinates of the node on the screen. Then you might want a different stage, but you want to keep the same layout that the particpant already created. You can use the layout variable from a drop down box on that screen rather than expect the participant to repeat the node layout. 

The codebook will show you not only the variable type but all the different stages where that variable is used. 

## Why are some variables marked as 'not in use'?

Whenever you create a variable it will then be stored in the codebook. You can use it again in other stages. However, if you delete all the stages that used this variable, you will not delete the variable (recall that we separate variables and stages internally). This means you might have some 'orphan' variables that are not in use in any stage. 

We do not delete these variables automatically in case you are storing them temporarily while you add new stages. Thus, you can use the codebook to review your variables and confirm that any orphan variables are indeed 'not in use' and not simply orphaned by accident when you meant to collect that data. 

## What does 'input control' mean? 

An input control is the specific mechanism used to enter the data. For example, textual data can be collected in a 'text input' which is a single line or a 'text area' which is a larger box. Network Canvas enforces consistency of these across stages. So while you can change a variable to be a text area or a text input, you can't make it a text area on one screen and then text input on the other. The input control column provides a way at a glance to see how the data is collected. 

{% include tip-caution.md content="Sometimes input control is empty. There are a number of scenarios where this can occur. For example: 
- The variable is added on the node creation screen. Here you can 'sneak in' a variable using "Assign Additional Variables". This is useful when you collect data on nodes using different prompts. For example, on each of the stages you can add a categorical variable such as _stage\_type_ = "closeness" for every node created on that stage. Then if you want to add nodes using a different prompt such as 'who are your family members', on this stage you can sneak in a _stage\_type_ = "family" variable. Since this was added automatically there was no 'input control'. 
- The variable is a 'system variable'. Fo example, node names are created in the act of creating a node. There's no specific control for them. The same for layout varaibles. Data for the layout varaible is created as people layout the nodes, but again there's no specific input control." markdown= true %}



