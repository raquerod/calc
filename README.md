# iphone 6 app calculator example

After creating a new project, go to main.storyboard and create a button. The size of the button should be 1/4 of the total width of the phone. 

![alt text](https://github.com/raquerod/calc/blob/master/images/Screen%20Shot%202017-03-31%20at%2011.20.26%20PM.png "Create Button")

Give the button the style you're looking for. Here, I changed the font and the background color to resemble the iphone native app.

![alt text](https://github.com/raquerod/calc/blob/master/images/Screen%20Shot%202017-04-02%20at%203.07.42%20PM.png "Create Style")

Next, copy the button to resemble a calculator.

![alt text](https://github.com/raquerod/calc/blob/master/images/Screen%20Shot%202017-04-02%20at%203.09.40%20PM.png "Calculator Style")

After that, I gave functionality to the buttons. All the buttons are under the function "numbers" that will display the number as text in a label on top of the buttons. The number of the buttons is retrieved by using tags. The tags start at 1. So for the number 0 the tag is 1, 1 tag is 2 and so on. So when retriving the number the function will see who's the sender, read the tag, and display tag - 1.

![alt text](https://github.com/raquerod/calc/blob/master/images/Screen%20Shot%202017-04-02%20at%204.55.07%20PM.png "Calculator Functionality")

The same is done with the operations. A function listens to a button being clicked and gets the tag, depending on the tag, there is an operation that happens. 

Finally, the calculator looks like this

![alt text](https://github.com/raquerod/calc/blob/master/images/Screen%20Shot%202017-04-05%20at%2012.56.45%20PM.png "Calculator Finished")

