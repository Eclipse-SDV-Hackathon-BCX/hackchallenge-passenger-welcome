# Eclipse SDV Hackathon on BCX2022

One-Pager ([PowerPoint](./assets/BCX_Onepager_passenger_welcome.pptx), [PDF](./assets/BCX_Onepager_passenger_welcome.pdf))

## Welcome to the 'Passenger Welcome' hack challenge! 

The idea of the 'Passenger Welcome' use case is that the driver (or a passenger) is detected while he is approaching the vehicle. Based on this information, your _Welcome Vehicle Application_ could control a sequence of events, such as welcoming the passenger with a special lighting sequence (using lights outside and/or inside the car), automatically opening the door or trunk, adjusting the seat position according to driver preferences, the same for steering wheel position, cabin temperature or air condition, etc. – there is no limitation to the creativity in this hackathon. What comes to your mind about how your own vehicle or a carsharing car should behave when a passenger approaches?


|<img src="/assets/PassengerApproaching.png" width="380">|<img src="/assets/PassengerWelcome.png" width="450">|
|-|-|

This hack challenge focuses on encouraging creativity, ideate ideas in the form of rapid prototyping in the playground of __digital.auto__ and transfer them easily to a working vehicle application trying out them on a devide using the Eclipse projects [__Velocitas__](https://websites.eclipseprojects.io/velocitas/), [__Kuksa__](https://www.eclipse.org/kuksa/) and [__Leda__](https://eclipse-leda.github.io/leda/) and, if applicable, [__SommR__](https://projects.eclipse.org/projects/automotive.sommr).

In this hack challenge, you can
- ideate your use case in easy way by using the provided playground,
- explore the Eclipse SDV ecosystem of open source projects, such as programming models, vehicle abstraction layer and protocol implementations.

Your hack team should have the following skills:
- Some development skills in Python
- Rudimentary Linux, git, shell skills are always a plus. 
- Some knowledge in network protocols such as MQTT is good.
- A bit of Docker, containerd, k8s experience would be good as well, for building your app as a container and deploy it to a container runtime on the device.


We would recomment the following steps for the hack challenge:

[Step 1 - Prototype your idea of the 'Passenger Welcome' functionality](/docs/step-1-prototyping.md)

[Step 2 - Transfer your prototype into a vehicle application](/docs/step-2-generating.md)

[Step 3 - Extend your application and test locally](/docs/step-3-extending.md)

[Step 4 - Build and deploy to a device](/docs/step-4-deploying.md)

You can test your prototype for example on the following hardware setups:

|<img src="/assets/img/suitcase_seat.png" width="335">|<img src="/assets/img/suitcase_lights.jpg" width="400"> | <img src="/assets/img/pican2_withnotes.jpg" width="330">|
|-|-|-|
|Sead Adjuster Suitcase |  [Bulli Lights Suitcase](https://github.com/Eclipse-SDV-Hackathon-BCX/hackchallenge-control-vehicle-lights) | Raspberry PI |

You can combine this hack challenge with the [HackChallenge: Control Vehicle Lights](https://github.com/Eclipse-SDV-Hackathon-BCX/hackchallenge-control-vehicle-lights) in case you ideate an implementation with lights.

Happy hacking!
