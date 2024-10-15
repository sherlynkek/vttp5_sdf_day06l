# Task 1
Establish a source (*src*) directory and a classes directory for your application.

Establish a Java package for your application.

Under your main package, create two sub-packages named "client" and "server".

Ensure that your application can accept two command-line arguments as shown
below.

    java -cp classes sg.edu.nus.iss.baccarat.server.ServerApp 12345 4

The first argument should be the port number for the server program.

The second argument should be the no of decks of cards for the server program.

Shuffle the four decks of cards and save the values to a data file named "cards.db".

1 is Ace 1.1 is hearts, 1.2 is diamonds, 1.3 is spades, and 1.4 is clubs.

11 is Jack 11.1 is hearts, 11.2 is diamonds, 11.3 is spades, and 11.4 is clubs.

    E.g.
    1.1
    4.1
    5.2
    11 .1
    10.3
    11.4
    ……

