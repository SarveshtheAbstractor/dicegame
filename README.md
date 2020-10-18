# dicegame
Hi You all first of thanks for seeing this project :)\
<----------------------------------------------------------------------->\
It's a Pig Dice Game(You can google for more information) made with JS,CSS3, HTML5\
<----------------------------------------------------------------------->\
Beautiful Interface is built with HTML5 and CSS3 and I have used Lato Fonts as font family and icons were fetched from ionic framework CDN\
<----------------------------------------------------------------------->\
Here's comes the crux The Javascript\
 <----------------------------------------------------------------------->\
I will break everything into pieces for you to easily understand it-\

<----------------------------------------------------------------------->\

1.Initialise function -\
This functions intialises all global variables to their intial state\
for example scores,roundscore,activePlayer will be set to zero\

<----------------------------------------------------------------------->\

2.Roll Button Event Listener(Invoked only on click) - \
This function uses global variables and manipulates them.\
Steps Done By this function are --\
a. Check if gamestate is true or not\
b. Generate a random number by Math object in js\
c. Display the dice and set image of dice respective to that random number\
d. Update the score if dice was not 1\
e. Else jump to next player function\

<----------------------------------------------------------------------->\

3.Next Player function =\
This function checks if activeplayer is 0 or 1 sets to 1 or 0 respectively\
and also sets roundscore to zero and updates UI\

<----------------------------------------------------------------------->\

4.Hold Button Event Listener(Invoked only on click)-\
This function uses global variables and manipulates them.\
Steps Done By this function are --\
a. Check if gamestate is true or not\
b. Add the roundscore to global score and Update the UI\
c. Check if user has won the game or not , if not then nextPlayer function is invoked.\

<----------------------------------------------------------------------->\

It's all, it's that simple :)\
Take your time and see the code.\

<----------------------------------------------------------------------->\

About myself-
Myself Sarvesh Hiwase, a Intermediate Web Developer and Programmer, a Computer Enthusiast willing to learn new technologies for fun projects.\

<----------------------------------------------------------------------->\
