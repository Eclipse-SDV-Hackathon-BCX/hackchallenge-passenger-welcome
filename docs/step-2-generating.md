# Hack Challenge 'Passenger Welcome'

In the previous step you started with envision and prototyping your vehicle app that implements the 'Passenger Welcome' functionality. You tested the signals against mocked vehicle components. Now it's time to transfer it into your Development Environment and test it with real vehicle services. Here [Eclipse Velocitas](https://websites.eclipseprojects.io/velocitas/) comes into the game. We are providing a project generator that allows you to generate a Vehicle Application GitHub repository from your previously created prototype code based on our [vehicle-app-python-template](https://github.com/eclipse-velocitas/vehicle-app-python-template).

## Step 2 - Transfer your prototype into a vehicle application

In the 'Code' section of your prototype in the [digital.auto.playground](https://digitalauto.netlify.app/) you have the Button 'Create Eclipse Velocitas Project'.
If you press this button you will be forwarded to [GitHub](https://github.com/) to login with your GitHub Account and authorize _velocitas-project-generator_ to create the repository for you. After you authorized the project generator you will be redirected to the [digital.auto.playground](https://digitalauto.netlify.app/) and asked for a repository name (Which also is the app's name). After pressing "Create repository" the project generator takes over your prototype code, adapts it to the structure in the [vehicle-app-python-template](https://github.com/eclipse-velocitas/vehicle-app-python-template) and creates a new private repository under your GitHub User.

<img src="../assets/generate.png" alt="Project Generator">

If you would like to know what exactly the generator is doing, please have a look on the code: [velocitas-project-generator-npm](https://github.com/eclipse-velocitas/velocitas-project-generator-npm). Feedback is welcome :)

After the generation of the repository is completed a pop-up dialog with your repository URL will be displayed. The newly created repository will contain:

- _/app/src/main.py_ containing your modified prototype code
- _/app/AppManifest.json_ with definition of required services
- _/app/requirements.txt_ with definition of requirements
- _/.devcontainer_/ required scripts to install every prerequisites in Microsoft Visual Studio Code
- _/.github/workflows/_ with all required CI/CD pipelines to build, test and deploy the vehicle application as container image to the GitHub container registry

**Next step:** [Extend the your use case with the component you need for you use case](/docs/step-3-extending.md)
