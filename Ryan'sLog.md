# 100 Days Of Code - Log

Starting Day Jan 3, 2017


<!--

### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)
**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.
**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.
**Link to work:** [Calculator App](http://www.example.com)

-->

**Link to work:** [Weather App](http://codepen.io/ryanmbarger/full/RoKbVd)

### Day 1: January 3, 2017 

**Today's Progress**: Added basic structure to the Weather App. Figured out the getLocation function

**Thoughts:** Need to get a better understanding up of to pull APIs. Been awhile since last working on Quoter API. Having trouble understanding all the pieces. 


### Day 2: January 4, 2017 

**Today's Progress**: I have the main portion for the OpenWeather API in the code.

**Thoughts:** Was having trouble getting the lat and long to be implemented into the API. But now how about 90% of the api results working. Just need to understanding the $.ajax operator better.




### Day 3: January 5, 2017 

**Today's Progress**: Got the API to pull weather data! 

**Thoughts:** Need to modify a little more so it doesn't show full decimals. I got stuck initially around getting the icon to show. I didn't realize that the Object was inside an Array. After the little fix, pulled the icons in easily, though I would like to put a better icon set as the default icons from OpenWeatherAPI are not the greatest.




### Day 4: January 6, 2017 

**Today's Progress**: Found a tutorial on adding a CSS Toggle. Used that template to modify and add to my project

**Thoughts:** It appears that codepen.io is not utilizing the jquery normally as the .toggle() is not functioning properly. Need to investigate further.



### Day 5: January 30, 2017 

After having to travel to North East for a close family members funeral, I am now getting back in the swing of things and continuing my journey.

**Today's Progress**: Had some issues with the previous toggle. Reverse Engineering another Toggle

**Thoughts:** Codepen will not allow the previous toggle to work. I am not sure if there is a setting I am missing, but when I copy the code out to another compiler it works. So I am using another tutorial, and trying to reverse engineer it so I can understnad it better.



### Day 6: January 31, 2017 


**Today's Progress**: Toggle is up and working now with modifications for color.

**Thoughts:** Toggle required a lot of code to get to work, but modifiying it was not to hard. Still need to fix so that it is inline with the F and C for temperature. But that is more cosmetic right now.

**Link to work:** [Weather App](http://codepen.io/ryanmbarger/pen/RoKbVd)


### Day 7: February 1, 2017 

**Today's Progress**: Trying to get toggle to change temperature when clicked, but I have not been able to get past this bug.

**Thoughts:** Not sure what exactly is causing the onclick to not fuction properly. Reached out to group for guidance.



### Day 8: February 2, 2017 

**Today's Progress**: Fixed the toggle click! Now switches between Farenheit and Celsius.

**Thoughts:** There were actually to issues. First I was using HTML's onclick funciton instead of the addEventListener function. Second, there was a function at the very top of my code that was continuing to fire and not allow the rest of the code to process. I commented that out and addEventListener function worked like a charm



### Day 9: February 3, 2017 

**Today's Progress**: Aligned the Toggle with the F and C. And made mobile responsive

**Thoughts:** Weather App is function properly on desktop browser, but won't work on the mobile site. It does look good on mobile site though with responsiveness working great!


### Day 10: February 4, 2017 

**Today's Progress**: GeoLocation is working except for on some mobile browsers.

**Thoughts:** GeoLocaiton is working OK, but is slow to respond from API.



### Day 11: Febrary 5, 2017 

**Today's Progress**: Switching to use IP Info instead of GeoLocation

**Thoughts:** ipinfo.io's api is very fast. It also doesn't need any feedback from the user to fire off request. 


### Day 12: February 6, 2017 

**Today's Progress**: Need to understand how Javascript is running through code. 

**Thoughts:** ipinfo.io's api is working, but doesn' fire til after the Weather API code. Can' understand why yet, as Weather API is positioned below. Tried using window.onload and $(document).ready to try to get Weather API to wait.


**Link to work:** [Wikipedia Viewer](http://codepen.io/ryanmbarger/full/jyvPEO)


### Day 13: February 7, 2017 

**Today's Progress**: Took a Pause from Weather App. It was working except for Chrome on Mobile. Started preliminary layout for the Wikipedia Viewer 

**Thoughts:** Getting odd error when using codepen. Won't show glyphicons on new pen, but when I forked an old pen and deleted everything glyphicons worked????


### Day 14: February 8, 2017 

**Today's Progress**: Moving along quickly with Wikipedia Viewer. Had to go find out how to setup GetSJON/Ajax call again :(

**Thoughts:** Kept getting error when calling wiki api. Everything looks corret, and when I pull within browser URL it works.


### Day 15: February 9, 2017 

**Today's Progress**: Used some more jQuery to push HTML .... appendTo() and empty(). Using JQuery was super easy. Now about 90% complete

**Thoughts:** Error yesterday was the api URL didn't have callback="?" put that in and JSON call was working like a charm.


### Day 16: February 10, 2017 

**Today's Progress**: Added Functionality for hitting "enter" key to search in addtion to the clicking search. Also made search results on put of results returned. No more Undefined results

**Thoughts:** Had to use trial and error until I found code to use the enter key as a click. (event.which?) need to understand why "Which"... Also used a for loop to out show up to 5 results and stop at 1 or 2 or 3 if data only had that many entries.


### Day 17: February 11, 2017 

**Today's Progress**: Started with the basic layout for the Twitch App.


### Day 18: February 16, 2017 

**Today's Progress**: Setup the basic connection to the API.

**Thoughts:** The API is getting data but I can't seem to get it to call multiples users.


### Day 19: February 17, 2017 

**Today's Progress**: Spent sometime changing the layout to get ready for the API data.


### Day 20: February 19, 2017 

**Today's Progress**: Finally figured out the hack that FreeCodeCamp had setup to prevent API keys didn't allow you to call multiple users at one time like the normal Twithc API. 

**Thoughts:** I'm having to re-order my code to accomodate for multiple calls.

Time to re-start. Time to do better
### Day 21: March 1st, 2017 

**Today's Progress**: Trying to fix the issue I am having with the var i = 0 that is not working inside the getJSON function.

**Thoughts:** Completely lost on this point.

### Day 22: March 2nd, 2017 

**Today's Progress**: Did a lot of research around scope of the var in the for loop

**Thoughts:** Still don't understand the scope and function. Looking to the forums


### Day 23: March 3rd, 2017 

**Today's Progress**: Couldn't get my inital funciton to work using the "i" variable in the for loop. Used instead a global variable as a counter.

**Thoughts:** Will need to go back and understand the scope better but figured a workaround for now.


### Day 24: March 4th, 2017 

**Today's Progress**: The getJSON is asynchronous. SO my function and second function is not firing at the correct time.  

**Thoughts:** Argggghhhh.


### Day 25: March 5th, 2017 

**Today's Progress**: Tried swapping out the getJSON for a $.ajax, it is functioning in correct time, but now giving me just data for the first user every time.   


### Day 26: March 6th, 2017 

**Today's Progress**: Researching $.ajax calls to get my app to work. 

**Thoughts:** Why!!!!
