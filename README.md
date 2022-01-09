# conference-app

The conference-app program allows the user to perform basic CRUD operations on
a Postgres database via an exposed api. It gave me a chance to experiment with Spring Boot.

Getting Started
---------------

These instructions will get you a copy of the project up and running on
your local machine for development and testing purposes.

### Prerequisites

Ensure you have Java 8 or higher installed on your machine. To check,
run the following on the command line:

`java --version`8

If you do not have Java installed, you should get a prompt to do so.
Once installed,

you should also have access to `javac`. You can check this by running:

`javac --version`8

You will need to have postgres installed. This can be checked by running:
`postgres -V`

In the event that the postgres command is not found, you may need to locate the directory of the utility. 
This can be done by issuing the locate bin/postgres command:

`locate bin/postgres`

In the event that the postgres use the following Homebrew command if on a mac
`brew install postgresql`

On windows, see the following page: https://www.postgresql.org/download/windows/

Getting Started
---------------

### Running conference-app

From the terminal run the following `./conference-demo-0.0.1-SNAPSHOT.jar`

From Intellij right click and run `ConferenceDemoApplication.java` 

Authors
-------

-   Ciaran McKenna

Contributing
------------

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

License
-------

[MIT](https://choosealicense.com/licenses/mit/)
