# Visualising Grime
[About](https://Tom-R-Leppard.github.io/) | [Research](/research.md) | [Teaching](/teaching.md) | [Network Tutorials](/network_tutorials.md) | [CV](/cv.pdf) | [Visualising Grime](/visualising_grime.md)

For my dissertation, I studied the collaboraitons between Grime musicians. Grime is a UK-based rap genre that emerged from the east London reggae and Garage scene in the early 2000s. Broadly speaking, my dissertation investigated how network embeddedness is assciated with the career success of 122 Grime artists. I codded their collaborations with others in the sample on Spotify over a 22 year period (2001-2022). From this, I generated directed networks for each year. An outward connection represents artist A appearing on artist B's Spotify profile (working on B's songs). An inward connection represents B featuring on A's profile (featuring on their songs). Here is a small collection of various visualisations I have created to showcase some of my work on this genre of music. Some of the visualisations are interactive and will need to be opened as links. 

## Grime in 3D
### Communities of Atists
I ran some community detection on collaborations each year and related artists, here is a network of communities of artists who share listeners. To get the related artists, I used Spotifyr's "get_related_artists" function to obtain the artists that the listeners of these 122 artists also listen to. I then visualised this as network to artsts are connected to related artists.  
<iframe src="fans_coms_3D.html" width="500" height="300"></iframe>

### Group Synthesis Measure
This is another interactive networks from a few years of the genre. Feel free to click on, move, and scroll in or out of the visualisation. 
<iframe src="grime_2015_JS_RECIP" width="500" height="300"></iframe>
The colours of the nodes in this network represent a unique measure of synthesis I developed in my dissertation. Blue spheres represent "givers" — artists whose collaborations mostly appear on other artists' profiles, meaning they have more outward connections than inward. Green spheres represent "takers" — artists who receive more collaborations than they give, meaning they have more inward connections than outward. Purple spheres represent "reciprocators" — artists who give and receive collaborations in equal measure, maintaining a balanced exchange. Red spheres represent artists who have never collaborated with anyone in the network. 

## Grime Collaborations Overtime
This is an ndtv network movie depicting the collaborations of Grime artists over the 22 year period I observed. For this visual, I removed isolated artists from each year.You will need to click the link. Then press the play button on the bottom right. You can alter the speed at which the network chances by using te settings on the top right. 
<iframe src="GRIME-Network_noISO.html" width="500" height="300"></iframe>

## Grime Networks Overtime 
These line graphs illustrate the growth of Grime networks in terms of order (number of nodes) and size (number of edges). While there is a consistent increase in order, the size fluctuates more erratically. These indicate a steady expansion of the genre itself but a more erratic pattern in the collaborative connections between artists. 

![Size and Order](/Grime Visuals/GRIME_Cross_only_Size and Order.png)
