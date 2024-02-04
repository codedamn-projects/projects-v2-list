# Save score to local storage

Now that we have made the quiz questions Interactive, in our last step of this project we will create a key and store the score and name in localStorage. 

## 1 : Storing details when name is filled. 
On the quiz completed screen when the user attempts to fill the name and submits the form. You would have to handle the submit event of the form to fetch the data using the key `leaderboard` and store the data as an array of objects and stringify it. 

## 2: Displaying the fetched data in the leaderboard. 

Now that we have the array of objects with us. We can generate a simple leaderboard element and add the list of users to the leaderboard text. 

## 3: Reset Quiz button 
The reset quiz button will be shown to the user's at the end of the leaderboard allowing the users to attempt the quiz again. 

This button will reset all the changes we've made to the DOM nodes, we can essentially achieve this by triggering a reload in the page or by removing all the nodes that we've inserting (the hard way). 

Congratulations, you have successfully built a fully functional quiz app. You have completed the project and learned and implemented a lot of new things starting from handing different states and a lot of DOM Manipulation. Submit this project using the `Submit Project` button on the bottom left of your page to get a personalised Code Report for your code and suggestions for some improvements that can be made. 

Take up the next [project](https://codedamn.com/projects) and start building