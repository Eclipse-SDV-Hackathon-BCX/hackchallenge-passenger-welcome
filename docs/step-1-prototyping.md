# Hack Challenge "Welcome Passenger"
## Step 1 - Prototype your use case

The digital playground : provides a interface between sdv(python) and VSS implementation, realized in Java script.
Digital Playground is a open web based playground for digital.auto dev and provides a rapid prototyping environment for the validation of ideas for Software-defined Vehicle using COVESA vehicle APIs and Python.

There are approximately 700 VSS API's in CVI (connected vehicle interfaces), we have facilitated a mapping between VSS and the 3d model of the Vehicle, more description follows like dependencies and implementation.

Projects Library : There are different usecases like Smart vipers, Happy dog.
The button 'open' would redirect to a new page with the code related to prototypical implementation and the user interface.

The dashboard consists of all the vehicle components and application components similar to mockups.

The run button executes all the VSS API's and specific API's used can be known clicking the CVI button.

Dev language : Python (used for mapping)
API : VSS

Test environment : 3D animation for API calls
Why are we using Digital playground?
Rapid protyping without custom setup requirements.
Ideal platform for SDV innovation challenges and to Communicate key solution concepts.
Software defined vehicle  : helps in exploration and validation.

There are different types of API's Sensors and Actuators.
CVI catalogoue and Prototyping : CVI catalogoue provides the information about all the vehicle API's (sensors, actuators and branches).
and Protoyping provides the different vehicle models.

The different vehicle models provides further information to the usecases related to them, for example smart trailer corresponds to usecase ideal for problem statements related to smart trailer, and similarily smart truck Vehicle model corresponds to problem statement related to Truck.

The landing page includes three options, the Prototype navigates to the different uses case, corresponding to various Vehicle models.
Exploring the Vehicle models and the pertaining usecases to get a better understanding.

-	Software-defined Vehicles (SdV) provide the means to create new customer and vehicle experiences by enabling developer to deploy QM applications on the vehicle which interact with the different vehicle sensors and actuators via standardized APIs. QM here means “Quality Manged”, i.e. we are not talking about fully hardened, ASIL-type of vehicle control applications, but rather about higher-level applications.
-	The digital.auto playground provides a rapid prototyping environment for such QM SdV applications, utilizing the COVESA VSS set of vehicle interfaces. COVESA is the Connected Vehicle Systems Alliance, which defines the Vehicle Signal Service catalogue.
-	A quick introduction for how to use the playground to build SdV prototypes can be found here: LINK to overview video
-	A key feature of the playground is the ability to create new plugins, which usually represent UX widgets or remote server communication to enhance the vehicle mockup experience in the playground. A detailed description of how to use and create plugins for the the digital.auto playground can be found here: …LINK TO PG DOC / Wiki
-	For the BCX hackathon, we have identified one specific use case as the foundation for the hack challenges, namely the “Passenger Welcome” use case
-	The idea of the “Passenger Welcome” use case is that the driver (or a passenger) is detected while he is approaching the vehicle.
-	Based on this information, the SdV Welcome-application could control a sequence of events, such as welcoming the passenger with a special lighting sequence (using lights outside and/or inside the car), automatically opening the door, adjusting the seat position according to driver preferences, the same for steering wheel position, HVAC, music, etc. – there is no limitation to the creativity in this hackathon
-	To help BCX hackers to get started quickly, we have added a number of widgets to simulate related elements of the vehicle – like doors, seats, light, etc. – and made them available in the playground here: LINK (this will require TAGs to filter plugins by tag)
-	Feel free to use the playground to:
o	Start tinkering with the default “Passenger Welcome” Plugins
o	Add your own Plugins with addition widgets for additional car features (maybe an antenna waving a warm “welcome”…?
o	Use plugins for remote connectivity to connect to real hardware, like the Car Seat provided by Bosch ETAS
o	Use the playground “wishlist” feature to add additional VSS sensors and actuators which you need but are not yet part of the COVESA standard






