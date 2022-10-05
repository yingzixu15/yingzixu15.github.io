---
layout: post
title:  "My parking spot finder API!"
tabname: My parking spot finder API!
date:   2022-10-04 20:54:49 -0400
categories: project
is_public: true
---
Hello everyone! Today my project [Montreal Parking Kitten](https://github.com/yingzixu15/mtl_street_parking_finder) has reached a happy milestone! Although it does not have a frontend interface yet, the signs API is finally ready and configured!

To test it out, you can head over to `mtlparkingkitten.info` and look at the breath-taking "Hello world" on pure blank background. I'm sure you are already amazed. :-) 

You can enter `mtlparkingkitten.info/api/signs/show-limit/5` to see what kind of data you should expect. The core functionalities are the following:
- showing all signs within distance in km;
- showing all signs within distance in km on a specific date (some signs contain information that are only valid during a date interval).

For example, you can use `mtlparkingkitten.info/api/signs/show-radius/long/-74.5/lat/45.5/distance/0.5` to obtain a list of parking signs that are within 0.5km distance from the coordinate (-74.5, 45.5). And if you use `mtlparkingkitten.info/api/signs/show-radius/long/-74.5/lat/45.5/distance/0.5/month/5/day/1`, you can see the signs that fits the aforementioned conditions, as well as being in effect on May 1. 

The project is not completed yet, but having the API ready is a big step and I'm very happy about it. Next, I will implement the frontend user interface, which will request information that is needed for the API, then display them nicely. Ideally I would also like to set up some static map display to mark the locations of these parking spots as well as the road they're on. 

Thank you for reading this, and I hope you all have a good day!