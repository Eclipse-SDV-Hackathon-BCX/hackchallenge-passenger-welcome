# Hack Challenge 'Passenger Welcome'

Tutorial Available also at [Velocitas Documentation](https://websites.eclipseprojects.io/velocitas/docs/tutorials/prototyping/).

The open and web based [Playground](http://playground.digital.auto) of _digital.auto_ offers a rapid prototyping environment to explore and validate ideas of a vehicle app which interact with the different vehicle sensors and actuators via standardized APIs specified by the COVESA [Vehicle Signal Specification (VSS)](https://covesa.github.io/vehicle_signal_specification/introduction/) without custom setup requirements. It provides the opportunity:

- To browse, navigate and enhance the vehicle signals (sensors, actuators and branches) in the _Vehicle API Catalogue_ mapped to a 3D model of the vehicle
- To build vehicle app prototypes in the browser using Python and the _Vehicle API Catalogue_
- To test the vehicle app prototype a dashboard in the browser with 3D animation for API calls
- To create new plugins, which usually represent UX widgets or remote server communication to enhance the vehicle mockup experience in the playground
- To collect and evaluate user feedback to prioritize your development portfolio

## Step 1 - Prototype your idea of the 'Passenger Welcome' functionality

As first step open [digital.auto.playground](https://bcx.digital.auto/) select [_Get Started_](https://bcx.digital.auto/model) in the Prototyping section of the landing page and select the Vehicle Model of your team.

> **_NOTE:_**  If you do not have an own Vehicle Model assigned to your team please contact the Velocitas Hack Coaches. It is important that each team uses their own Vehicle Model and with that their own prototype instance, otherwise you would override the changes of the other teams.

Now you have the option to check the existing vehicle signals by selecting the _Vehicle APIs_ and validate if the required signals for your interpretation of the 'Passenger Welcome' functionality exist and how they are named.

<img src="../assets/CVI_Catalogue.png" alt="Vehicle API Catalogue">

The next step would be to prototype your idea. To do so:

- Click on _Prototypes_ (in the top right toolbar),
- Create a new prototype, by clicking on _New Prototype_ and filling out the informations,
- Click on the _Open_ button (right side),
- Go to the _Code_ section and
- Start your prototype right away.

<img src="../assets/code.png" alt="Code Section">

To test your prototype go to the _Run_ section, which opens a dashboard consisting all vehicle and application components similar to mockups. The control center on the right side has an integrated terminal showing all of your prototyped outputs as well as a list of all called VSS API's. The _Run_ button executes all your prototype code from top to button. The _Debug_ button allows you to step through your prototype line for line.

<img src="../assets/run.png" alt="Run Section">

To get started quickly, the Digital.Auto team has added a number of widgets to simulate related elements of the vehicle – like doors, seats, light, etc. – and made them available in the playground.

Feel free to add your own Plugins with addition widgets for additional car features (maybe an antenna waving a warm “welcome”…?).

**Next step:** [Transfer your prototype into a working application](/docs/step-2-generating.md)
