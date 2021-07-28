Everyone knows these typical coding challenges. 
So, if you have experience in software development, it will take you just a short time to solve them.

But even if you never solved coding challenges like ours, you can still do some research on the web.
But please, do not ask other people to assist you. 
The only thing that really matters for us is to see how you and only you can solve technical challenges.

## Challenge #1:
Write a function in JavaScript that reverses and outputs a given string or number.
You can use any methods including built-in ones.

Examples:
```js
reverse('hello') // Output: olleh
reverse(1234.56) // Output: 65.4321
```


## Challenge #2:
Set up a simple NodeJS server application that listens on port 7777.

Your application should respond to a client GET request to the /hello endpoint with "Hello!"
If you provide an optional 'name' query parameter, the response should change to "Hello, {name}!"
For every route other than /hello, it should respond with a 404 Not Found.

Use any server framework of your choice. We recommend to have a look at ExpressJS.
No frontend is required, you can communicate with your server from the console/terminal.

Example request:
```js
curl --request GET 'http://localhost:7777/hello'
```

Output:
```
Hello!
```

Example request:
```js
curl --request GET 'http://localhost:7777/hello?name=user'
```

Output:
```
Hello, user!
```


Example request:
```js
curl --request GET 'http://localhost:7777/wrongpage
```

Output:
```
404 Not Found
```


## Challenge #3:
This challenge requires some basic experience with React.

Please use the Random User API (https://randomuser.me/api/) to get JSON response containing generated user information.
Create a basic React or Svelte frontend application that displays a list of up to 10 users on the first page with their avatar, first and last name, email address, city and country. 
Feel free to add some other relevant information, but keep the overview light and simple.

After clicking on the user's name or picture, the app should redirect you to a new page where complete user information provided by Random User API is displayed.

This page should look more or less like a personal profile page including a larger image of a user and some of the relevant personal information.
Feel free to decide which information to display and how to design the page. 
Some basic styling with CSS/SCSS is optional and brings bonus points. You can use existing libraries like Bootstrap or similar.

When you navigate to the previous page with a list of people, it should not load new profiles, but keep the previous profiles in place. 
You can apply any persistence strategy of your choice, we would suggest React.useContext Hook or Redux.

What we are looking for is how you are able to retrieve and process data from the 3rd party service, what would be your approach to persist the data, and how can you apply refactoring to handle code duplications.
Do not spend much time on perfecting the CSS, very basic knowledge in CSS and HTML are sufficient for this task.
