Readme File for 6.859 Assignment 4 by Shane Weisberg: National Parks to Avoid the Crowds

Usability:
Important Note: Works best on chrome.
Update: If the layout seems off (axes and plot title in weird places), try zooming out and refreshing. Clearly some issue with the the absolute vs. relative positions. Something to work on...
Note: If the map is on top of the points, click the button and it will be fixed. Sorry.

Instructions:
Explore the map and graphs to find your next national park adventure!
Hover over points on the map and bar graphs to see details (Note: all graphs are plotted using a logarithmic scale).
Click on points to visit NPS websites. 
You may notice the map background is obscuring the datapoints. Click on the button in the top left to reorder the layers.
Clicking this button will also return the usage instructions to the screen at any time.

Sources:
All data from National Park Service Website 
Images from google maps

Design Decisions
I wanted to create a visualization that would allow for people to virtually explore the 61 national parks in the US to pick out a location for their next outdoor adventure. (Sorry to the Virgin Islands and American Samoa, whose parks did not fit on the screen.)
With parks limiting capacity and being overcrowded last year due to covid, I wanted to specifically focus on the number of visitors in each park and how likely you are to run into crowds.
Of course, there's more to these parks than just avoiding people, so I wanted to give people a sense for these parks by including images and links to the park websites to encourage further exploration.
In terms of the graphs, I used bar graphs to represent total visitors, visitors per 1000 acres, and visitors per season. 
I decided to sort the visitors graph in decreasing order as I felt this was an intuitive and aesthetically pleasing choice.
Rather than sort the bottom bar graph, I kept these in the same order to encourage comparison between the two. It's clear from this that there are some parks like Yellowstone which have high numbers of visitors but are also big enough to avoid being overcrowded (of course, this assumes uniform density, which is certainly not the case for most parks, including Yellowstone.)
The seasonality bargraph, which updates automatically as the users move their mouses around, is sorted by time, which is a natural choice, I think.
Another important design decision, and one I went back and forth on, was the axis scales. All three bar graphs use logarithmic scales, which make them less intuitive and make comparisons within graphs harder, I think.
That being said, I felt this was the right choice because the emphasis of this assignment was on interactivity, and using linear scales would have led to several very small bars that would be difficult to interact with. If this were a static visualization, I would have used linear scales.
In terms of interactivity, nothing particularly complex is going on here, but I think the hovering actions work well for the map setting. I wanted to focus on the whole visualization working together, and the linkage between the map and the graphs works really well.
You can hover over a point on the map and the bar graphs will all react, or you can hover over the bars and the map will react. The image and seasonality graph will react to each other aspect of the visualization.

I want to thank classmates who gave really helpful feedback for the following suggestions that I incorporated:
--Graphing visitors by season
--Removing text from overlaying the images (as these were originally a traditional tooltip) and placing it below the image for improved readibility and image viewability
--Including a park tagline in this description
--Leaving the images on the page even after the mouse leaves a point, instead of going back to being invisible on mouseleave
--Encouragement to push throgh the pain to use emojis to represent the different park types. This was annoyingly difficult but I think it worked out well.

In terms of the development process, this was certainly a bumpy road getting here, but by the end, things were moving much quicker, which I think is a sign of improvement.
Figuring out how to get the map to work was an absolute nightmare and resulted in one very frustrating saturday (including missing watching arguably the best basketball game of the year, if not ever)
This was a combination of my own incompetance and a lack of good resources on the web. It's nice to see all of Mike Bostock's beautiful maps, but following along and interpreting his code is non-trivial.
Once that was out of the way, the rest of the process was much more pleasant/less frustrating. Adding the interactivity wasn't too bad; the tough part was making sure each aspect of the visualization had access to the information it needed.
I'm sure the way I ended up doing this was less than ideal in many ways, but the functionality is there.
Going forward, I'll have a better idea of bad habits to avoid earlier and this should make a big difference.
Figuring out the best way of debugging also made the end of the process easier.
In terms of hours, this probably took me somewhere between 24-48 hours of work total. It's a wide confidence interval, but I wasn't really keeping track, mostly for my own mental health and sanity. It definitely took longer than I would have preferred, but a lot of that, like I said, was slamming my face against the keyboard trying to get the map working.

Thanks for reading and I'm looking forward to getting feedback.




