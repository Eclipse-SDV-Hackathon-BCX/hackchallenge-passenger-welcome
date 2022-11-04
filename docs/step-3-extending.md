# Hack Challenge 'Welcome Passenger'

### Service Integration

Services can make sure, that when you write a VSS datapoint, something is actually happening. We prepared a seat and a light service. If your Velocitas application makes use of the `Vehicle.Cabin.Seat.Row1.Pos1.Position` and `Vehicle.Body.Lights.IsBackupOn`, `Vehicle.Body.Lights.IsHighBeamOn`, `Vehicle.Body.Lights.IsLowBeamOn` you are in for some real action. To learn more, visit the colleagues with the seat and lights hardware.

You can validate the interaction of the service with your vehicle app by adding your vehicle service to the /app/AppManifest.json, [start the services](https://websites.eclipseprojects.io/velocitas/docs/tutorials/quickstart/#starting-runtime-services) locally and [debug](https://websites.eclipseprojects.io/velocitas/docs/tutorials/quickstart/#debugging-vehicle-app) them.

### Modifying services

_Stormy weather ahead_
![Stormy](../assets/img/stormy.png)

You are adventurous and don't mind a little rough waters? Try modifying the existing services. For the seat service see [here for the seat service](https://github.com/boschglobal/kuksa.val.services/tree/feature/subscribe_actuator_targets/seat_service) and ask the local hack coaches for light service code

### Doing your own services

_Here be dragons_
![Stormy](../assets/img/dragon.png)

So you want to actuate your own service, when a VSS actor is written from your Velocitas app? Doing something on the fancy [JetRacer](https://www.waveshare.com/wiki/JetRacer_AI_Kit) that are floating around here somewhere, or abducting a smart light from the Building/IoT hackathon next door?

Congratulations: You came in the middle of an API rewrite in KUKSA.val. But this is a hackathon right? You wouldn't be here if easily scared. Here is what you need to do: You need to write an application that talks to KUKSA.val listening to changes of a _target value_ of some VSS datapoint and then doing whatever you want. You can achieve this by using [our new GRPC API](https://github.com/eclipse/kuksa.val/tree/master/proto/kuksa/val/v1) using any programming language of your choice (learn more about GRPC at https://grpc.io) or, alternatively, trying a [preview of our new Python API](boschglobal:romainletendart/new-proto-api). If you manage this, all new functionality is available directly in your Velocitas app, without any further integration/coding work on your part (assuming you limit yourself to datapoints defined in VSS 3.0).
In case of questions: Search for the KUKSA hack coaches at the event.

**Next step:** [Build and deploy to a device](/docs/step-4-deploying.md)
