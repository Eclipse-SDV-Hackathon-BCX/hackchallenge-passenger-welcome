# Hack Challenge 'Passenger Welcome'

The open and web based [digital.auto.playground](https://digitalauto.netlify.app/) offers a rapid prototyping environment to explore and validate ideas of a vehicle app which interact with the different vehicle sensors and actuators via standardized APIs via the COVESA [Vehicle Signal Specification (VSS)](https://covesa.github.io/vehicle_signal_specification/introduction/) without custom setup requirements. It  provides the opportunity:
- To browse, navigate and enhance the vehicle signals (sensors, actuators and branches) in the [CVI Catalogue]() mapped to a 3D model of the vehicle
- To build vehicle app prototypes in the browser using Python and CVI Catalogue
- To test the vehicle app prototype using the dashboard in browser with 3D animation for API call
- To create new plugins, which usually represent UX widgets or remote server communication to enhance the vehicle mockup experience in the playground. 
- To collect and evaluate user feedback to prioritize your development portfolio

## Step 1 - Prototype your idea of the 'Passenger Welcome' functionality

As first step open [digital.auto.playground](https://digitalauto.netlify.app/) and select [_Get Started_](https://digitalauto.netlify.app/model) in the Prototyping section of the landing page and select the Vehicle Model of your team.

__Note__: If you do not have a own Vehicle Model assigned to your team please contact the Velocitas Hack Coaches. It is important that each team use their own Vehicle Model and with that own prototype instance otherwise you would override the changes of the other team.

Now you have the option to check the existing vehicle signals by selecting the CVI Catalogue and validate if the required signales for your interpretation of the 'Passenger Welcome' functionality exists and how their are named.


<img src="../assets/CVI_Catalogue.png" alt="CVI Catalogue">


The next step would be to prototype your idea. To do so select _Prototyping_ and press on the right side the button _Open_ and go to the _Code_ section and start your prototype right away. 

<img src="../assets/code.png" alt="Code Section">

To test your prototype go to the _Run_ section, which opens the dashboard consists of all the vehicle components and application components similar to mockups. The _Run_ button executes all the VSS API's and specific API's used can be known clicking the CVI button. To get started quickly, we have added a number of widgets to simulate related elements of the vehicle – like doors, seats, light, etc. – and made them available in the playground here: LINK (this will require TAGs to filter plugins by tag)

<img src="../assets/run.png" alt="Code Section">

Feel free to add your own Plugins with addition widgets for additional car features (maybe an antenna waving a warm “welcome”…?) as described: [here](LINK to PG doc/wiki) or use the playground 'Wishlist' feature to add additional VSS sensors and actuators which you need but are not yet part of the COVESA standard.

__Next step:__ [Transfer your prototype into a working application](/docs/step-2-generating.md)






