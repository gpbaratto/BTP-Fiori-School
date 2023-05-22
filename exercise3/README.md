# README file for Exercise 3: DEALING WITH EXISTING CODE
In exercise 3, you are going to build a UI service for a transactional SAP Fiori elements-based app using the unmanaged runtime implementation which allows the integration of existing business logic (i.e. Brownfield implementation).

# Motivation

The topic of this exercise is *Dealing with Existing Code*.

So, we start with having a look at the legacy business logic that we want to leverage for our unmanaged business object implementation.

For this we investigate the sub package **`/DMO/FLIGHT_LEGACY`** that resides in the package **`/DMO/FLIGHT`**.

The data is read from already existing legacy data base tables **`/DMO/TRAVEL`** and **`/DMO/BOOKING`**.

In addition, we will use function modules such as **`/DMO/FLIGHT_TRAVEL_CREATE`**, **`/DMO/FLIGHT_TRAVEL_UPDATE`** or **`/DMO/FLIGHT_TRAVEL_DELETE`** that are used to create, update and delete the data in a buffer. We also have a read function module that reads the data from the buffer rather than from the database level that comes handy when implementing the business logic that is required when the business object is called via EML rather than by a  SAP Fiori UI. And there is finally a function module that saves the travel and booking data to the database tables.

> **Hints and Tips**    
> Speed up the typing by making use of the Code Completion feature (shortcut Ctrl+Space) and the prepared code snippets provided. 
> You can easily open an object with the shortcut *Ctrl+Shift+A*, format your source code using the Pretty Printer feature *Shift+F1* and toggle the fullscreen of the editor using the shortcut *Ctrl+M*.   
>
> Please note that the placeholder **`####`** used in object names in the exercise description must be replaced with the suffix of your choice during the exercises. The suffix can contain a maximum of 4 characters (numbers and letters). Numbers and letters are allowed.  
> The screenshots in this document have been taken with the suffix **`1234`**.
> Please note that the ADT dialogs and views may change in the future due to software updates - i.e. new and/or optimized features.

Follow the instructions below.

![Tables_and_function_modules](/exercise3/images/W4U2_005_Tables_and_Function_Modules.png)

# HANDS-ON EXERCISES
Find the links to the different hands-on exercises below.
        
## Exercise 3 Unit 1:	Creating the CDS Data Model 
[Link to the hands-on exercise.](unit1.md)
    
## Exercise 3 Unit 2:	Defining and Implementing the Business Object Behavior 
[Link to the hands-on exercise.](unit2.md)
        
## Exercise 3 Unit 3:	Creating the Business Object Projection
[Link to the hands-on exercise.](unit3.md)
        
## Exercise 3 Unit 4:	Building and Previewing the OData UI Service
[Link to the hands-on exercise.](unit4.md)

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.

