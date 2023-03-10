![Airbnb](https://user-images.githubusercontent.com/114498685/224133040-aa8f8e58-d9e8-40e8-ba17-357406d16e9f.png)

# The AirBnB Clone Project

# Description of the Project

This is the Airbnb clone project, which is a complete web application, integrating database storage, a back-end API, and front-end interface in a clone of AirBnB.

This team project is part of the ALX Software Engineering program, which represents the first step towards building a full web application.

This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.

# Installation 
Clone the repository and run the console.py

`git clone https://github.com/**********/AirBnB_clone.git                                                             `

# Usage
---------
|  Method |                   	Description                      |        Usage           |
| ------- | ---------------------------------------------------- | ---------------------- |
| create  | Creates object of given class. | create <class name> |
| show    | Prints the string representation of an instance based on the class name and id.| show <class name> <id> --or-- <class name>.show(<id>) |
| all     | Prints all string representation of all instances based or not on the class name.| all <class name> --or-- <class name>.all() |
| update  | Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file).| update <class name> <id> <attribute name> "<attribute value>" ---or--- <class name>.update(<id>, <attribute name>, <attribute value>) --or-- <class name>.update(<id>, <dictionary representation>) |
| destroy | Deletes an instance based on the class name and id (save the change into the JSON file).| destroy <class name> <id> --or-- .destroy() |
| count   | Retrieve the number of instances of a class.| count <class name>.count() |
| help    | Prints information about specific command.| help <command> |
| quit/EOF | Exit the program.| exits normal |

# Repo Contents
------------------
This repository contains the following files:

|  Files                      |                       Descriptions            |
| ------------------- | ------------------------------------ |
| AUTHORS	       | contains info about authors of the project. |
| base_model.py	       | defines BaseModel class (parent class), and methods. |
| user.py	       | defines subclass User. |
| amenity.py	       | defines subclass Amenity. |
| city.py	       | defines subclass City. |
| place.py	       | defines subclass Place. |
| review.py	       | defines subclass Review. |
| state.py	       | defines subclass State. |
| file_storage.py      | creates new instance of class, serializes and deserializes data. |
| console.py	       | creates object, retrieves object from file, does operations on objects, updates attributes of object and destroys object. |
| test_base_model.py   | unittests for base_model. |
| test_user.py	       | unittests for user. |
| test_amenity.py      | unittests for amenity. |
| test_city.py	       | unittests for city. |
| test_place.py        | unittests for place. |
| test_review.py       | unittests for review. |
| test_state.py        | unittests for state. |
| test_file_storage.py | unittests for file_storage. |
| test_console.py      | unittests for console. |
| web static           | unit testing libraries and web frameworks such as html, css etc. | 

# General Execution
Your shell should work like this in interactive mode:

```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
============================
EOF  help  quit
(hbnb) 
(hbnb) 
(hbnb) quit
$
```
But also in non-interactive mode: (like the Shell project in C)

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
============================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
=============================
EOF  help  quit
(hbnb)
$
```
All tests should also pass in non-interactive mode: `$ echo "python3 -m unittest discover tests" | bash`

# Authors
-----------

  #Ezenna Frank

  #Adedolapo Adefaye
