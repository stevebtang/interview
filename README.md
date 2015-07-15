Create a library that does lookups on a dataset.
Instructions
-----
locations.csv contains a list of locations around the world. Each location maps to a unique ID, and each location has a parent id.
What we want to do is create a library which people can use to lookup location information, given either a name or an id.

This library should be able to provide the following functionality

1. Id -> Location Info
Example
If we pass in ID 1012873, we would want the information about Anchorage, Alska, United States

2. Location Info -> Id
Example
If we pass in Anchorage, Alska, United States, we would want to get back the ID 1012873

3. Given a parent ID or Name, lookup all "children" locations.
Example
If we pass ID X, we return all locations that have the Parent ID X.

Please create a library to do the above. Provide (short) documentation for usage. 

Language : Python/Java
