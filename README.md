# README #

### Author: Harpreet Dhillon, harpreet@uoregon.edu ###

---

### Purpose ###
* This application is for Project 5 of CIS 322 at University of Oregon.
* The purpose was to use mapping apis in conjuction with ajax calls to be able to add pins to a map.

### Application Specifics ###
* There is a [poi](/poi.txt) txt file that specifies a preset set of Points of Interest that will be placed on the map automatically and follow the format:
  * Description, Latitude, Longtitude
* There are two inputs that automatically update with the respect latitude/longitutde of the map after dragging, it can also be used to change the set of the map to a specific latitude/longtitude
* There is also a button that will return the map to the view of Eugene, Oregon

### Running the Application ###
* Test deployment to other environments including Raspberry Pi.  Deployment 
  should work "out of the box" with this command sequence:
  * `git clone <yourGitRepository> <targetDirectory>`
  * `cd <targetDirectory>`
  * `make configure`
  * `make run`
  * (control-C to stop program)
* The default port is 5000, so the webserver should be reachable at http://localhost:5000 , and also through its IP address.
 
### Testing the Application ###
 * There are no tests for this application other than accessing the webpage at http://localhost:5000 and seeing the map display.
