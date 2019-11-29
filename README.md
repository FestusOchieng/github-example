Applied Data Science Capstone
Peer-graded Assignment: Capstone Project - The Battle of Neighborhoods

Festus Ochieng

IBM Data Science Professional

Now that you have been equipped with the skills and the tools to use location data to explore a geographical location, over the course of two weeks, you will have the opportunity to be as creative as you want and come up with an idea to leverage the Foursquare location data to explore or compare neighborhoods or cities of your choice or to come up with a problem that you can use the Foursquare location data to solve.

1:INTRODUCTION/BUSINESS PROBLEM

• A customer, David, wants to open a new burger joint in Bogotá, Colombia.
• Due to Bogotá’s high diversity and very large size, he asked me for help in order to find the best spot to place the burger joint.
• Bogotá has 20 different Localities (Districts) and we aim to find the best one.
• We need to choose a Locality that has good amount of customers and low amount of competition.

DATA

• To help David in his search we will need to access following data:
• The Localities of Bogotá, Colombia from Wikipedia: https://es.wikipedia.org/wiki/Anexo:Localidades_de_Bogot%C3%A1
• The coordinates (latitude, longitude) ot these Localities of Bogotá from Open Street Map APIs
• From Foursquare we will need following venues data:
• the burger joint venues of the Localities
• the offices venues of the Localities
• the high schools venues of the Localities
• the universities venues of the Localities
• We will then leverage the data in order to determine which locality is the most appropriate in order to locate the burger joint.
Methodology
• For each locality, all office, school, university and burger joints venues data have been collected from Foursquare.
• Then for each locality, the sums of the office, school, university and burger joints were computed.
• For each of this 4 categories, a weight (or penalty) has been defined according to what David considers the most important.
