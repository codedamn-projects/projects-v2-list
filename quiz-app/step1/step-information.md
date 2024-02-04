# Building the quiz layout

The best way to render the contents of the quiz questions is to create the DOM elements in JavaScript and append them to the page. This way we can dynamically change the content of the page without having to reload the page. We will also need to add event listeners to the buttons to check if the answer is correct or not.

## 1 : Creating the DOM structure in JavaScript 

You can choose to setup the Quiz Structure directly in the HTML and switch the view based on the start quiz button or you can directly manipulate the dom by adding and removing elements from JavaScript. 

As this is a beginner project, we wouldn't have to worry about choosing the best/the most performant approach. You can choose to do it either way.

You would have to construct the Question div followed by four buttons for the options for the quiz. 

## 2: Making the quiz question and options interactive. 

Using the given `questionData` array, you can construct the question and options for the quiz. You can maintain a variable to keep track of the current question.

Based on the user action on the click of a button we would have to display the next question to the user. You would have to increment the current question variable and display the next question details

## 3: Handling the last question. Show the Completed Page 

Once the user has selected the options for all the questions, we reach the last slide of the quiz, where we reach a critical condition (`questionData.length - 1`) This completed page should display the score (which we will calculate in the next steps) and a form to enter the user's name and submit button. 

## 4: Style the quiz page 

Style the quiz page so that the option buttons are accessible for clicking and the UI looks clean. Make the options container a flex container add the background color to the buttons (#218380). 

## 5: Create an element for displaying the answer value: (Correct / Incorrect) 

Create the DOM node to display the answer state. This could a simple paragraph tag that shares display the text `correct` and `incorrect`. We will make this element functioning in our next step