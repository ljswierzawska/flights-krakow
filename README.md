# The Kraków Flights Website

### Summary
This project creates an auto-updating website that retrieves data about arrivals and departures at Kraków-Balice, the second busiest airport in Poland, after Warsaw’s main airport. It’s also just 10 minutes from my house, and I’ve probably taken more flights from here than I can count — basically what I call my second home.

The data is retrieved from the airport's official website that maintains a dynamic schedule of flights with separate tabs for arrivals and departures. Here is the link: https://krakowairport.pl/pl

The table on the website shows arrivals and departures for the current day, depending on the time of the day. The table is also supposed to highlight delayed and cancelled flights. The auto-updates every hour. 

### New Skills
I'm completely new to HTML so it was a fun excercise, especially manipulating the html script to make the website prettier. Also, I had no clue you can use Pandas to scrape data like that! That's very cool...

### What works
I followed a tutorial made by one and only Jonathan Soma, which from scratch explains how to build a website like that. All the steps were successfully implemented. The link to the tutorial is here: https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://www.youtube.com/watch%3Fv%3DQNKxzkNpsko&ved=2ahUKEwjMkdy10cWRAxVrgv0HHW-EH98QtwJ6BAgREAI&usg=AOvVaw2jR5qcpJivNHWyPy017VIS

I played around with some aesthetic choices in the HTML file. For that, I needed ChatGPT. 

### What needs improvement
I’m not sure the color-coding for cancelled or delayed flights will actually work. In Datawrapper, to highlight certain rows based on a column, you need to specify exactly which values classify them as such. When I wrapped up this project, there were no delayed or cancelled flights, so I couldn’t test it.

Ideally, I’d like a widget that counts delayed and cancelled flights. I understand this would require a separate data source that logs all flights and refreshes daily, but I’m not sure how to connect that to an HTML script.
