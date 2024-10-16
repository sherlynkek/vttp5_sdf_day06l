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

# Task 2
Develop a client program that establishes a connection with the server program.

    java -cp classes sg.edu.nus.iss.baccarat.client.ClientApp localhost:12345

Enable user input for commands in the client program.

All the server logic must be written in a class name “BaccaratEngine.java”

| Command           | Client         | Server |
| :---------------: | :------------: | :----: |



# Task 3
In the client program, you are required to create a CSV file to keep track of the
winning games. 

Hint : game_history.csv

Each row in the CSV file can only record up to 6 games, and there can be multiple
rows.

In Baccarat, when both the Player and Banker hands have the same total points, it
results in a tie game. In this scenario, neither the Player nor the Banker wins, and
bets on the Player and Banker are returned to the respective players. However, there
is a specific bet called the "Tie" bet, which wins if both hands tie. The payout for the
Tie bet is higher than the payouts for the Player and Banker bets, typically around 8
to 1 or 9 to 1, but it varies depending on the casino.

    B,P,P,P,B,B
    B,B,D,P,B,B
    B,P,B,P,B,B
    B,D,P,P,B,B
    B,P,P,P,B,P

# Task 4
Write at least two test cases for the *BaccaratEngine.java* class.

# Task 5
Create an HTML table that reads a CSV file and publish it as a website, you can use
JavaScript to read the CSV file and then dynamically generate the HTML table.

Place all three files (*index.html*, *script.js*, and *game_history.csv*) in the same
directory.

When you open the *index.html* file in a web browser, it will read the
*game_history.csv* file and display its contents as an HTML table on the webpage.


