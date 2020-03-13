# UberAlt - July 2019
## A mobile alternative to Uber written in Android to practice coding ability
### About:
The Passenger Portal and Transport Provider Portal files contain gradle and script codes for Android applications which can interact and schedule rides, determine oneʼs current location in Google Maps, and alter oneʼs details which are available to other users on the application. Such applications ideally coordinate through the transmission of data via cloud storage, and Googleʼs Firebase Realtime Database software is included within the code. This cloud hosting platform enables both portals to upload the passenger/transport providerʼs location, destination (if applicable), description. Ultimately, the Passenger Portal would be able to access the array of Transport Providers, map their locations and index them from closest to furthest, and generate an optimized route for Transport Providers to follow to take Passengers to their destinations.
### Restrictions:
Unfortunately, the lack of cloud storage led to a variety of problems, including minimal data-related interaction between the two portals. Firebase is a weak platform, which is what makes it free and easily accessible, and thus it was impossible to store all of the features mentioned above (location, description, etc) without a more robust cloud host. Consequently, the “Schedule a Ride” and “Passenger Queue” buttons lead to temporary build pages which would ideally be filled with providers or passengers that fit the description above.
### Completed tasks:
The most significant part of each portal was creating a login and registration method which would save the username and password for repeated sign-ins from multiple devices. This method only required a key-value association between two strings (username/email and password), and so Firebase was a suitable option for this portion of the project. The application is powerful enough to remember if you have logged in already or not, and even offers password creation help to increase security.
### Incomplete tasks:
With more time and stronger cloud computing capabilities, one could look to finishing the aforementioned ride scheduling and passenger queue creation to define routes. Additionally, the details and maps GUIs have yet to be implemented, but are within Androidʼs capabilities and should not take more than one or two days to implement. In the future, one could look to creating mechanisms for modifying the passengerʼs locations and destinations, a history associated with each passenger containing their modifications, an emergency SOS button in case of distress, and even a rating system to determine which drivers are consistently performing up to task.
