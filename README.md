CS50 Final Project:  The Quest For Khazana
By:  Zaheer Hasan

    Hello there, my final project is a website/story called "The Quest for Khazana".  It's a short story where you choose your fate.  The story is my own and I coded it completely with HTML, CSS and JS.
    I based it off of the "Choose Your Own Adventure" book series by Edward Packard, R. A. Montgomery and Joe Stretch.  In my project the pages are represented by Panels(individual webpages) with choices at the
    bottom of each page taking the user to next panel.

FEATURES
- Similiar to the Choose Your Own Adventure Book Series
    - But in Web format thorugh multiple webpages
- Will begin with a starting webpage which has multiple options(Start, Manual and Credits)
    - The Start option goes to the first story Panel
        - Each panel has a stock image to help further desribe the scene, using a bootstrap carousel
        - Each HTML page will have appropriate bgm
        - Underneath each Carousel image is a card-type carousel which represents the choices to the user
    - Manual opens a pop-up text bubble bnreifly explaing how the website works
    - Credits leads to a simple credits page
- Has a main story path but only if the right choices are made
- Some choices leads to a "bad" end, thus having to restart
- The bottom banner of each page contains a copyright, HOME button and a music player, in that order.

CODING
- Each page is built using HTML and stylized using CSS
    - Three CSS pages are used:  One for the homepage, one for the panel pages and one for the credits page
    - The homepage has a video carousel playing in the background on autoplay
- The carousel features used for the story and the choices are enchanced using Javascript
    - Each carousel uses "data-interval="false" to prevent autoplay
    - The Panels.css page maintains a consistent size for each image used
- The bottom of each webpage has a nav bar.
    - Contains a copyright(using a symbol), a "button" for the homepage and an audio player set on autoplay
- Used many of Bootstrapts functionality as well