# MapChat

Authors: Rohit Kumar, Isaiah Discipulo, Boice Wong, and Zeeshaun Jawaid

Inspiration:
Our project was inspired by the lack of cellular data infrastructure in developing nations. Because of this many services, 
like banking have transitioned to SMS-based platforms. Cursory research showed that this transition has not been extended to include map 
services, like Google Maps. We believe that access to these services would improve the day-to-day lives of people that wouldn't have had 
access to these services previously.

What it does:
This program allows users to send text messages to a host email, which analyzes the content and fulfills the user's request. 
We currently have four main functionalities: Address, Directions, Elevation, and Weather. Address stores the current location of a user,
indexed by their phone number. Directions returns the steps to arrive at a specified destination address, using the current location as a 
starting point. Elevation returns the how high a specified address is above sea level. Weather returns the weather conditions and 
temperature (celsius) at a specified address.

How we built it:
Our program is built mostly in Python, making use of the googlemaps and the pyowm modules. We also created a host email account through 
gmail, to send and receive SMS-messages. We created a Linux virtual machine using Amazon Lightsail to host our Python scripts.

