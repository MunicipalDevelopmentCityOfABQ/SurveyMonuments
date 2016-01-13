# Survey Monuments

Rewriting the [Geodetic Control and ARTGN: Create Datasheet Application](http://www.cabq.gov/gis/map-views/geodetic-control-and-artgn).

This application was developed by a vendor. In updating and moving data, the application needed to be rewritten. We took the task on in-house. The HTML is a copy of the vendors original page that was rendered server side. Working with that, we wrote the code using JavaScript to query endpoints and populate the data client side. Lot's of `document.getElementById("x").innerHTML="some string"`

The original application worked fine, but only provided access to active monuments. After recreating the service, we are modifying the front end to include all monuments - active, destroyed and abandoned, 




