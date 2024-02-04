# Make the quiz app interactive

In this step our main goal is to make the quiz interactive, to calculate the score and display the answer state when the user selects an option. 

## 1: Create a function to countdown score
Set the default value of the timer to 50. When the user clicks on the start quiz button, we will start the timer and decrement the timer by 1 every second. 

When the timer reaches 0, we will stop the timer and display the completed page. When timer hits 0, you would have to show the quiz completed dom element that we have built in the last step along with the form to enter the name. 

## 2: Verify the correctness of the option

Once a user clicks on an option in the quiz question, we need to evaluative if the chosen option is correct or wrong. We would use the `answer` key to check whether the correct option is chosen. 

If the correct option is chosen then we will not disturb the timer, if the chosen answer is wrong, We will have to decrement the score by `10`. 

If the correct option was chosen, display the text `Correct!` for 1 second, and if the option chosen was incorrect display the text `Incorrect!` for 1 second. You can make use of `setTimeout()` to unmount / hide the text after 1 second. 

