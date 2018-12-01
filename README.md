# final_project
Itis 2 a.m., and a drunk driver just drove through the front door of a house in Eagle Rock. There are injuries, as well as a fire that that was started when the car’s gas tank burst into flames upon impact. The neighbors, awakened by the noise, have called 9-1-1, and have been routed to a Los Angeles  Fire  Department  dispatcher.  The  dispatcher  needs  to  send  the  closest  engine  and paramedic unit(s) to the scene. But, who is closest? Minutes can mean lives are lost.
Eagle Rock is covered by the following fire stations:
---------------------------------------------------------------------
Station		Unit			Notes
---------------------------------------------------------------------
12 	
		Truck 12 		“Hook and Ladder”
		Rescue Ambulance 12  	EMT Ambulance
---------------------------------------------------------------------
2		Engine Company 42	Paramedic Engine
---------------------------------------------------------------------
55		Engine Company 55	Normal Engine
		Rescue Ambulance 55	ParamedicAmbulance
---------------------------------------------------------------------

As can be easily seen, finding the “shortest route”from the “closest”firestation to theincident is very critical. The City Council, recognizing the need, has put out a software development project to create software that will “find”the closest available unit and provide drivingdirections to the Engineer. Your company,being a “small and disadvantaged business”has been given the task of finding theshortest route from theclosest fire station to the address displayed on the dispatcher’s screen. Other contractors havebeen given other tasks.

The city has provided a “sanitized” XML file for the ZIP Codes 90041, 90042, and 90065 that contains street names, latitudes and longitudes of points on the street that will enable mapping, and  what  addresses  are  contained  on  the  portion  of thestreet. Some streets have multiple latitudes and longitudes as in they “curve”or “bend.” They have also give you an XML file with all of the fire stations in the city.

 As a “proof of concept,”you have been assigned to “cover”Eagle Rock’s three stations and all addresses within the Eagle Rock boundaries as shown below:

The data provided by the City of Los Angeles was “way too much,”so a program was writtento “weed  out”the  minimal  data  required  for  the  project.  However,  it  does  not  provide “who  is connected to whom,”nor distances. Distances can be calculated, but an “exhaustive”search must be done in order to create “nodes”for use with Dijkstra’s “Greedy”Algorithm.

This version of the Final Project has “built-in”Extra Creditof 500 points. You must accept input via a GUI that will “validate”that the address is one that can be responded to by one of the fire stations (meaning, within the borders of the picture above). Once validity has been established, the closest, in distance, firestation must be found, then the route must be calculated. Once calculated, theroute must be displayed upon a map within the GUI.

For  additional  Extra  Credit  (500  points),  the “weight”used  must be  able  to  be  changed  from “distance”to “time.”Times  can  be  calculated  by  the “average”speed  allowed  on  a  road;  for example, Colorado Boulevard is 35 mph, Townsend is 35 mph, La Roda Avenue is 15 mph, and so forth.The data necessary to calculate times is  partially available in the original file from the City (as in road types). Correlatingwith the California Vehicle Code, road speeds allowed can be easily found. (They are part of the test you took to get your driver’s license, and are in the Driver’s Handbook or at the DMV web page.)