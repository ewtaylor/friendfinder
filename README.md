Compatibility based friendfinder:
a) The application will display the name and picture of the user with the best match overall.
b)The survey has 5 questions, answers to the survey questions are on a scale on how much the user agrees or disagrees.

Technical details: a) The application uses Express to handle routing
b)The server.js file uses the npm packages: express, body-parser, path.

The html-routes.js file should include two routes:
a) A GET Route to /survey which displays the survey page.
b) A USE route that leads to home.html which displays the home page.

The api-routes.js file includes two routes:
a) A GET route with the url /api/friends. 
-b) A POST route /api/friends. 

Compartison of the difference between the user's scores against other users' scores, question by question. Then will add up the differences to calculate the totalDifference.

Example:
User 1: [5, 1, 4, 4, 5, 1, 2, 5, 4, 1]
User 2: [3, 2, 6, 4, 5, 1, 2, 5, 4, 1]
Total Difference: 2 + 1 + 2 = 5
The person with the closest match will be the one with the "least" amount of difference.

The result will display the name and picture of the best match!
