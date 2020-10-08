This is 50th screencast, called "50. React Meme Generator Capstone Project"
https://scrimba.com/course/glearnreact


/**
* Create the boilerplate to get React to render something on the screen
* Render an <App /> component, which you'll need to create separately
*/

/**
* Create 2 new components - Header and MemeGenerator
* Header will only display things
* MemeGenerator will be calling to an API and holding on to data
* Each should be in their own file of the same name
*/

/**
* Initialize state to save the following data:
*      top text
*      bottom text
*      random image (intialize with "http://i.imgflip.com/1bij.jpg")
*/

/**
* We'll be using an API that provides a bunch of meme images.
* 
* Your task:
* make an API call to "https://api.imgflip.com/get_memes" and save the 
* data that comes back (`response.data.memes`) to a new state property
* called `allMemeImgs`. (The data that comes back is an array)
*/

/**
* Create 2 input fields, one for the topText and one for the bottomText
* Remember that these will be "controlled forms", so make sure to add
* all the attributes you'll need for that to work
*/

/**
* Create the onChagne handler method
* It should update the corresponding state on every change of the input box
*/

/**
* Create a method that, when the "Gen" button is clicked, chooses one of the
* memes from our `allMemeImgs` array at random and makes it so that is the
* meme image that shows up in the bottom portion of our meme generator site (`.url`)
*/