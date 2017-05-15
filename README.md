# Facebook Sydney Hackathon 2017 Data

[@szdc](github.com/szdc) and I competed in Facebook's Sydney Hackathon 2017 and developed a web application for viewing the suburbs in Sydney with the best access to public transport.
Here is the data that we mined from Sydney Trains for the Hackathon.

The data was mined using a Golang script that filled out all of the combinations of suburbs to suburbs.
Data was stored in a Cassandra cluster, and for the final web application was served out of Redis to ensure it was fast.

We leveraged React for the frontend, with [@szdc](github.com/szdc) developing many performance enhancements to the way the map and suburb polygons were rendered to ensure the map was displayed the same across a large range of devices.

**We came 3rd overall ahead of 25+ other teams.**

![Screenshot](screenshot.png)
