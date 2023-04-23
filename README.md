Download Link: https://assignmentchef.com/product/solved-assignment-16-colored-cards
<br>
Edit, compile, and run the following program on the UH UNIX shell:

The purpose of this assignment is to learn how to use an array of structures.

<ul>

 <li>Modify the cards.c example code

  <ul>

   <li>The <strong>struct card</strong> structure should also have the card’s color, “red” or “black”.</li>

   <li>The corresponding code in the program should hold the new cards, and display their colors when printing.</li>

  </ul></li>

 <li>You must use an array of <strong>struct card’s </strong>in your program.</li>

 <li>The color MUST be a part of the struct.

  <ul>

   <li>Don’t use the color as a separate array.</li>

  </ul></li>

</ul>

//structure definitionstruct card{char *rank;char suit[MAX];//** add the color of the cards here **};

<ul>

 <li>The display function should output the new structs as shown below.</li>

</ul>

Submit your C program via Laulima, and makefile if you use one.

<strong>Example I/O</strong>

Display an ordered deck of cards:

Ace of Clubs    (black)         Two of Clubs    (black)

Three of Clubs    (black)        Four of Clubs    (black)

Five of Clubs    (black)         Six of Clubs    (black)

Seven of Clubs    (black)       Eight of Clubs    (black)

Nine of Clubs    (black)         Ten of Clubs    (black)

Jack of Clubs    (black)       Queen of Clubs    (black)

King of Clubs    (black)         Ace of Diamonds (red)

Two of Diamonds (red)         Three of Diamonds (red)

Four of Diamonds (red)          Five of Diamonds (red)

Six of Diamonds (red)         Seven of Diamonds (red)

Eight of Diamonds (red)          Nine of Diamonds (red)

Ten of Diamonds (red)          Jack of Diamonds (red)

Queen of Diamonds (red)          King of Diamonds (red)

Ace of Hearts   (red)           Two of Hearts   (red)

Three of Hearts   (red)          Four of Hearts   (red)

Five of Hearts   (red)           Six of Hearts   (red)

Seven of Hearts   (red)         Eight of Hearts   (red)

Nine of Hearts   (red)           Ten of Hearts   (red)

Jack of Hearts   (red)         Queen of Hearts   (red)

King of Hearts   (red)           Ace of Spades   (black)

Two of Spades   (black)       Three of Spades   (black)

Four of Spades   (black)        Five of Spades   (black)

Six of Spades   (black)       Seven of Spades   (black)

Eight of Spades   (black)        Nine of Spades   (black)

Ten of Spades   (black)        Jack of Spades   (black)

Queen of Spades   (black)        King of Spades   (black)




shuffling deck …




Seven of Hearts   (red)          Four of Diamonds (red)

Four of Hearts   (red)          Five of Diamonds (red)

Two of Diamonds (red)           Ace of Hearts   (red)

Two of Hearts   (red)         Three of Clubs    (black)

Six of Diamonds (red)          King of Hearts   (red)

Four of Clubs    (black)       Eight of Hearts   (red)

Nine of Clubs    (black)       Three of Diamonds (red)

Queen of Spades   (black)        Jack of Diamonds (red)

Jack of Hearts   (red)           Two of Spades   (black)

Six of Clubs    (black)         Ten of Hearts   (red)

King of Clubs    (black)         Two of Clubs    (black)

Nine of Spades   (black)       Eight of Spades   (black)

Ten of Spades   (black)       Seven of Diamonds (red)

Ace of Diamonds (red)          King of Diamonds (red)

Six of Spades   (black)        Five of Clubs    (black)

King of Spades   (black)        Four of Spades   (black)

Queen of Diamonds (red)         Seven of Clubs    (black)

Queen of Hearts   (red)         Queen of Clubs    (black)

Jack of Clubs    (black)       Three of Hearts   (red)

Three of Spades   (black)       Eight of Diamonds (red)

Nine of Hearts   (red)           Ten of Diamonds (red)

Eight of Clubs    (black)         Six of Hearts   (red)

Seven of Spades   (black)        Nine of Diamonds (red)

Five of Hearts   (red)           Ace of Clubs    (black)

Ten of Clubs    (black)        Jack of Spades   (black)

Five of Spades   (black)         Ace of Spades   (black)




Would you like to shuffle again?

If so, press “Enter” key. If not, enter any other char.





