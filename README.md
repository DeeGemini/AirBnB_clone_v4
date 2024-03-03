# AirBnB Clone - Web Dynamic
## Project Definition
* The AirBnB_clone-Web Dynamic project aims to create a dynamic web application based on the AirBnB clone project. It extends the functionality of the original AirBnB clone by implementing a web interface that allows users to interact with the application through a browser.

#### Functionalities of this command interpreter:
The command interpreter in this project provides various functionalities to interact with the AirBnB clone application. Some of the key functionalities include:

* Create, read, update, and delete (CRUD) operations for objects such as User, Place, City, State, Review, and Amenity.
* Search and filter functionality to retrieve specific data based on user-defined criteria.
* Ability to handle multiple storage engines (file storage and database storage) for persistence.

## Table of Content
* [Environment]
* [Installation]
* [File Descriptions]
* [Usage]
* [Examples of use]
* [Bugs]
* [Authors]
* [License]

## Environment
This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3) and Flask framework for web development. It is designed to be compatible with various operating systems including Linux, macOS, and Windows.

## Installation
* Clone this repository: `git clone "https://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@github.com/DeeGemini/AirBnB_clone_v4.git"`
* Access AirBnb directory: `cd AirBnB_clone_v4`
* Run hbnb(interactively): `./console` and enter command
* Run hbnb(non-interactively): `echo "<command>" | ./console.py`

## File Descriptions
* web_dynamic/: Contains the web application code.
* models/: Contains the Python classes representing various objects in the application.
* tests/: Contains unit tests for the application.
* console.py: Command-line interface for interacting with the application.
* README.md: This file providing information about the project.

## Usage
To use the AirBnB_clone-Web Dynamic project, you have two main options:

* Web Application: Start the web application by running the following command:To use the AirBnB_clone-Web Dynamic project, you have two main options:
> python -m web_dynamic.app
--This will start the Flask server, and you can access the application through a web browser.
* Command-line Interface: You can also interact with the application using the command-line interface. Run the following command to start the CLI:
> python console.py
--Once the CLI is running, you can use various commands to manipulate objects in the application. Use the help command for a list of available commands and their usage instructions.

## Examples of use
To start the web application, run the following command:
> python -m web_dynamic.app
--This will start the Flask server, and you can access the application through a web browser.

### Documented Commands
The command-line interface supports various commands for interacting with the AirBnB clone application. Some of the documented commands include:

* [Create](Create a new object)
* [Show](Display information about a specific object)
* [Update](Update the attributes of an object)
* [Destroy](Delete an object)
* [All](List all objects or objects of a specific type)

For detailed usage instructions, refer to the documentation or use the help command within the command-line interface.

## Bugs
No known bugs at this time. 

## Authors
Nontuthuzelo Ngwenya - [Github](https://github.com/DeeGemini) / [Twitter]()

## License
Public Domain. No copy write protection. 
