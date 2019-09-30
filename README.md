## File structure
I have opted for a very lightweight single stylesheet called into index.html file which seems appropriate.

## HTML structure
I have looked where possible to use semantic html elements to simulate a website that is looking to adhere to best organic SEO practices. 


## CSS structure
I have used basic CSS with no pre-processors and pre-fixed where necessary to behave on modern browsers. 
I have adopted the BEM (Block, element, modifier) naming scheme to my css to begin a framework that ensures the css codebase is maintainable as it scales. 

I have used flexbox, which has been supported by all browsers for many years, to ensure predictable box sizing for shrink and expand with
regard to the news stories area. It also maintains the gutters between the image and its supporting text, unlike floats, in news-stories__item.

I have decided to overflow-x to deal with the tables responsive layout. After some research there is two popular methods for this. The first
is to use overflow as I have done, and maintain the native semantic tabling markup that html5 provides. The second was to use flexbox to
change the orientation of the table to vertical on mobile. I dislike this solution because it introduces a lot more code which needs to be
maintained, and also looks rather poor as the size of the table increases. This is entirely up to subjectivity however, happy to hear another opinion!
