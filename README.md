##About Movies You Like
This is a simple application that provides the user with movies they might like based 
on a movie they already like. This was created as a way for myself and friends to quickly find a movie to watch based on movies we already like.

Jquery was used to grab the json data and handlebars.js was used to template the received data.

There are several views included

*   index. - Contains simple form.

*   related.html - Grabs the title for the liked movie and displays best related movies.
*   exactMovie.html - Same as related but grabs id of movie instead of the title and displays related movies.
*   view.html - Contains information for a specific movie.

## The Javascript
The javascript portion is very straightforward. I am using jquery to pull the json data from the movieDB. I am using handlebars.js to render the json data onto my html views.

The main javascript is in the main.js file. You'll see that there are two sections to the code. The first is the logic, grabbing the data and deciding what needs to happen to it. The second portion is simply rendering out the data onto the page.

My goal is to make the code even smaller and faster. My goal was to separate the two concerns and i feel this approach works well, but I am always open to new ideas.
	

###Note
 This is a pretty early draft of the movie site. I plan to add a lot more to it when i have time.
 Feel free to help. 