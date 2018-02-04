---
publisher: {}
datePublished: '2018-02-04T16:28:52.005Z'
dateModified: '2018-02-04T16:28:37.865Z'
description: >-
  The first step in optimising vehicle performance is to measure: after all, it
  is not possible to improve things that can’t be measured in some way. Vehicle
  logs usually provide error codes and time stamps, and these can be used to
  identify trends, to see patterns across a fleet of vehicles, and thus as a
  source of information for maintenance planning. The same method can be used
  for examining errors reported from station systems, such as lifts, and also
  others causes of issues or delays.
via: {}
sourcePath: _posts/2017-11-03-use-case-vehicle-performance.md
title: System Performance
hasPage: true
inFeed: false
author: []
starred: true
datePublishedOriginal: '2018-01-11T23:38:03.322Z'
url: vehicle-performance/index.html
_type: Blurb

---
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/59bd6621-7be4-4284-9c99-ac4d4b72ab65.jpg)

# System Performance

The first step in optimising vehicle performance is to measure: after all, it is not possible to improve things that can't be measured in some way. Vehicle logs usually provide error codes and time stamps, and these can be used to identify trends, to see patterns across a fleet of vehicles, and thus as a source of information for maintenance planning. The same method can be used for examining errors reported from station systems, such as lifts, and also others causes of issues or delays.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/4131369b-f95c-43b7-949f-7e8018a24786.jpg)
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/159f5bca-d38a-4c0d-84e4-c1fcc7e4dc82.jpg)

There are additional possibilities, however: those log files also frequently contain other wdata, and so information can be derived by correlating across multiple system logs. For example, if a CBTC system outputs log files containing vehicle dynamic data (location, velocity, acceleration), and a train management system contains data such as motor information, these can be linked to provide possible "early warning" information (increased current draw for same performance achieved, for example). Statistical process control techniques can be used to model the performance of individual vehicles along a route, or to identify outliers: train operator behaviour can be used to determine training requirements. The screenshot shows an extremely simplified depiction of vehicle parameters during a journey: velocity and other parameters against location, or alternatively against journey times are obvious ways of visualising data, but it is also possible to show parameters against velocity, or any other measured parameter.
![](blob:http://localhost:8000/676611a8-7c4d-4e4d-9859-a23d96d96243)

One key thing with all of these visualisations is the requirement for consistent known factors: time has to be correlated across systems (or at least, a common and known offset used), and measures have to use known and consistent units. Derived parameters can be compared without necessarily knowing the constituent parts: although that is less than ideal, if a supplier does not provide detail of composite values, trends can be monitored and forecasts made.