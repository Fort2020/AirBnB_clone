# AirBnB_clone project

![image](https://user-images.githubusercontent.com/113660966/225206662-2a2eb1c6-dfec-4935-882a-7318ee58e33c.png)
Description of the Project

This is the Airbnb clone project, which is a complete web application, integrating database storage, a back-end API, and front-end interface in a clone of AirBnB.
This team project is part of the ALX Software Engineering program, which represents the first step towards building a full web application.
This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.

# Installation

Clone the repository and run the console.py
git clone https://github.com/**********/AirBnB_clone.git 

#Usage

MethodDescriptionUsagecreateCreates object of given class.createshowPrints the string representation of an instance based on the class name and id.show --or-- .show()allPrints all string representation of all instances based or not on the class name.all --or-- .all()updateUpdates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file).update "" ---or--- .update(, , ) --or-- .update(, )destroyDeletes an instance based on the class name and id (save the change into the JSON file).destroy --or-- .destroy()countRetrieve the number of instances of a class.count .count()helpPrints information about specific command.helpquit/EOFExit the program.exits normal

# Repo Contents

This repository contains the following files:

FilesDescriptionsAUTHORScontains info about authors of the project.base_model.pydefines BaseModel class (parent class), and methods.user.pydefines subclass User.amenity.pydefines subclass Amenity.city.pydefines subclass City.place.pydefines subclass Place.review.pydefines subclass Review.state.pydefines subclass State.file_storage.pycreates new instance of class, serializes and deserializes data.console.pycreates object, retrieves object from file, does operations on objects, updates attributes of object and destroys object.test_base_model.pyunittests for base_model.test_user.pyunittests for user.test_amenity.pyunittests for amenity.test_city.pyunittests for city.test_place.pyunittests for place.test_review.pyunittests for review.test_state.pyunittests for state.test_file_storage.pyunittests for file_storage.test_console.pyunittests for console.web staticunit testing libraries and web frameworks such as html, css etc.

# General Execution

Your shell should work like this in interactive mode:

$ ./console.py (hbnb) help Documented commands (type help <topic>): ============================ EOF help quit (hbnb) (hbnb) (hbnb) quit $ 

But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py (hbnb) Documented commands (type help <topic>): ============================ EOF help quit (hbnb) $ $ cat test_help help $ $ cat test_help | ./console.py (hbnb) Documented commands (type help <topic>): ============================= EOF help quit (hbnb) $ 

All tests should also pass in non-interactive mode: $ echo "python3 -m unittest discover tests" | bash

# Authors

#Ezenna Frank

#Adedolapo Adefaye 
