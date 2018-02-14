# #100DaysOfCode Log - Round 1 - Nicola Hastings

The log of my #100DaysOfCode challenge. Started on Monday, 29th January, 2018

## Log
### R1D17
HTML and CSS base done for the Wiki Viewer in Codepen. The random article button is set up and working. Been playing with jquery animate to make the search field expand and contract. Need to design the look and feel next and get down to the wikipedia api.

### R1D16
Submitted the weather app codepen to Free Code Camp and moved on to the next project which is to build a wikipedia viewer. Had a look at the supplied links to the wikipedia api and researched other people's versions to see what the general idea is. Planned out ideas for Nicki's Wiki Viewer. 

### R1D15
Completed the weather app on codepen: https://codepen.io/nickihastings/full/payLxr/ very pleased with it. Managed to work out how to test for day and night and compare to the sunrise and sunset times to get a background image depending on day or night. Thought it would be harder than it was at the sunrise and sunset times in the api were provided as unix UTC times. But the api also provides the local time as well so it's just a matter of comparing. Did lots of tidying up on the look of the app and finally pleased with it.

### R1D14
Spent a good few hours on the weather app today and am very close to completing it. Wrote the code to change the background images depending on the weather codes returned. Seems a long winded way doing multiple if/else if statements, but there didn't seem to be an easier way. Tried switch but couldn't test the right conditions. Not sure if it is better to set up multiple background styles with the image information in the css and then use jquery to change the styles, or to set the images in an object in javascript and update the img attr with the correct image source. I did it the latter as it kept everything in the same place.

### R1D13
Struggling to keep up with this log and do code learning and work. Spent time sourcing background images and icons to use in the app. Got the Fahrenheit and Celsius buttons to work. Had a problem using <a> tags for the links as it caused the page to refresh instead of just changing the data and so the change never happened. Solved it by making buttons instead.

### R1D12
Did some PHP coding to solve a WordPress theme problem with WooCommerce, doesn't display categories and products very well on the shop page so always requires some theme hacking.

Added more data to the weather app and tested it with a different location via the VPN. All working. Took a bit of time to get the weather description from the api as it's provided as an object inside an object and I didn't realise. Still got to set up the change from Fahrenheit to Celsius buttons and also a bit of styling to do.

### R1D11
Better progress with the weather app. Wrote the ajax function to fetch the api data which works. Now updating the html with the new data. So far it knows my location and the temperature. Getting excited! Work in progress is here: https://codepen.io/nickihastings/full/payLxr/

### R1D10
Seem to be going backwards with the weather app rather than forwards. Realised that any api keys I planned to use would be exposed on codepen to the public which I don't think is a good idea. So, probably going to use the Free Code Camp weather api which apparently is a mirror of the openweathermaps api but with no need for keys. (They should have said that at the start.) 
Did a bit of troubleshooting on my VPS as a mailbox quota was not updating after it had been cleared, the cpanel was still showing over quota. It is meant to update every four hours so something was wrong. Client not happy. Managed to find a way of forcing the maildirsize file to regenerate through shell access to the server. Another snippet of unix code to add to my growing collection.

### R1D9
Slightly distracted by the Falcon Heavy Rocket launch tonight, but managed to get some coding in. Worked out a javascript function to get the geolocation properties from the browser, store them and then text the longitude and latitude readings in the console. Success. Here is the gist of the little function: https://gist.github.com/nickihastings/58d15a5790c0cc142479a76c9525758c

### R1D8
Decided to add a fade in transition to the background colour change of the quote machine as it's something I've not played with before. CSS3 makes it easy.

The weather app hasn't progressed so much as further research into the weather api revealed that the World Weather Online API is not a free one. Have chosen to go with the Dark Sky API instead, not least because it sounds cool ;-) It has a free option for 1,000 api calls a day. I doubt mine will ever get more than 5. Have read through the documentation and noted the complicated parts, such as changing celsius to fahrenheit. Also looked at how to get the geolocation information from a visitors browser, relatively easy although I am not sure how then to display it as an actual location.

### R1D7
Set up the html and css base for the weather app. Checked the options available in the World Weather Online api. Put together some resources ready to begin the hard work tomorrow.

### R1D6
Not much time today for coding so checked out the next challenge on Free Code Camp, read the rules and looked at the example. Making a local weather app next. Did some research on weather api's as didn't want to use the Free Code Camp one, and I find the weather fascinating. Had a little look into geolocating visitors and searched for some resources, fonts, and images.

### R1D5
The random quote generator is finally complete. Added the functionality to tweet out the quote using jquery and url encoding. Also added an array of colours so that the background colour changes randomly each time there is a new quote. Pretty pleased with the final result. Added a gist of the new jquery code including the tweet button here: https://gist.github.com/nickihastings/5b1e9b4d3bb6c0dedc76d3206d5a9954
Final codepen here https://codepen.io/nickihastings/full/BYappV/

### R1D4
FINALLY worked out why the api import was failing. It seems I didn't understand how to use mashape where the quote api was coming from and didn't have the correct information and credentials. So happy it is now working and I have random movie quotes! You can see the codepen here, still some work to do on it: https://codepen.io/nickihastings/full/BYappV/
I'm also trying to add as much code to github as possible to learn how it all works, so I have created a GIST with my javascript code. I don't know if this the correct way of doing, but it seemed like a good idea. https://gist.github.com/nickihastings/edbedf8166fa6862a98007031215fbc8

### R1D3
Had a frustrating hour of coding trying to get my ajax code to import an api and display quotes for the random code machine. Not working. Still not sure if there's something I'm doing wrong in codepen, or my code is wrong. 

### R1D2
Not much actual coding today, only an hour spent reading up on AJAX and JSON, any tutorials I could find. Every example is different, so for a newbie it's confusing. Hoping to get back on the code tomorrow.

### R1D1 
Started work on the Random Quote Machine from Free Code Camp, struggling a bit with JSON and AJAX, need to start again from scratch with some straight forward tutorials. Base html and css all set up now https://codepen.io/nickihastings/full/BYappV/. Decided to use the github 100-days-of-code log to track my progress and realising now how little I know about how to use github, fork, commit...!! I guess this will be a steep learning curve.
