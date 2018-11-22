# Make Button, Make GIF
### correct-gif-pronounciation

ONCE AND FOR ALL, we will determine the correct way to pronounce ".gif". We will do this by calling gifs from Giphy and pausing them as we see fit.

![internet web surfing GIF](https://media0.giphy.com/media/eCwAEs05phtK/giphy.gif)

## OK, so we may never know...

If we are correctly pronouncing "gif". However, we can have plenty of fun in the meantime. This project incorporates the skills I have learned to this point, including (but not limited to) the following:

* Dynamically generating buttons from an array
* Sending a query to the Giphy API and selecting components from the response.
* Populating the page with these results.
* Using "click" and "this" functionality to modify elements on the DOM as they are interacted with
* Stimulating interactivity by allowing users to add their own gif searches and see them displayed.


## How does it work?

Using Jquery & Javascript, the page creates buttons from a pre-defined array. These buttons appear on the top of the page. 

Next, there is a text input form below the buttons allowing users to enter a new category of gifs. When they submit their category, the array is updated and the buttons are regenerated.

Finally, when a button is clicked, the Giphy API is queried and produces static images of the gifs, appended by their ratings. Upon click of any of the images, they will animate. Users can stop and start gifs to their heart's content.


# Special Thanks

* Jerome, Jimmy, & Sasha, for teaching me the fundamentals necessary to make this.
* Christie Byrne, for showing me the proper click listener syntax.
* My Wife, for reminding me how mobile un-friendly my project was.
