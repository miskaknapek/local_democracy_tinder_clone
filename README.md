# local_democracy_tinder_clone


### Quick intro to running the things ___
Basically it all runs in the browser, so you only need to have an ftp server that can serve up files, no browser-based scripting support is needed. 
You can also test things straight from your browser, without an ftp server. Just open a browser and ask the browser to lok at the index.html file. 


### Live example  ___
You'll find a live example, done for a test with Borås ( Sweden ) students . 
http://sourisr.kapsi.fi/boras/


### Modifying texts ___
If you want to modify things, eg adapt things to German, then you'll find some texts in the following files : 
- index.html
- js/demo_app.js
      -- in this file I've added the #TEXT hashtag to help you find where there are bits of text that appear on screen 
- js/app_screen_data.js
      -- this is where the questions and answers are located. 
       It's a JSON array with question+answer data. 
       The places which might well be relevant to you in each json entry, are : 
          - question : that's the main text, that describes the question/issue the parties voted on.
          - images : ( well, it's only one image, but there was space for several earlier ) this is the background image url. Do remember to have the image url in single quotes.
          - which_parties_voted_YES_for_this__as_list and which_parties_voted_NO_for_this__as_list : these are the texts for when one swipes right/left, or presses the X or <3 buttons at the bottom of the screen. 
           - Don't worry about the images related to voting YES/NO, these are leftovers from things that were supposed to be implemented but didn't. 

( The other files in the js library, the different jquery files, are libraries for screen interaction, that someone else has written, that I've not modified ).


### Credits 
Concept : Magnus Eriksson at RISE Interactive, 
CSS styling : Martin Törnros at RISE Interactive, 
CODE and some design : Miska Knapek at RISE Interactive.
 

### Fin ___
