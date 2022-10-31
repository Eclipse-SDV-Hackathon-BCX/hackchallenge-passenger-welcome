# Hack Challenge 'Passenger Welcome'

You started in the previous step with envision and prototyping your vehicle app that implements the 'Passenger Welcome' functionality. You tested the signal and tested it against mocked vehicle components. Now it's time to transfer it into your Development Environment and test it with the real vehicle services. Here comes [Eclipse Velocitas](https://websites.eclipseprojects.io/velocitas/) into the game. We providing a project generator that allows you to generate from your prototype code a Vehicle Application in a GitHub repository based on your vehicle app template repository.

## Step 2 - Transfer your prototype into a vehicle application

In the 'Code' section of your prototype in the [digital.auto.playground](https://digitalauto.netlify.app/) you have the Button 'Create Eclipse Velocitas Project'. 
If you press this button you get asked to authorize _velocitas-project-generator_ to create the repository for you. After you Authorize us we will be ask for repository name. After pressing the "Create repository" button the project generator creates the repository for you and transferes your prototype code.

<img src="../assets/generate.png" alt="Project Generator">

If you would like to know what exactly the generator is doing, please have a look on the code: [velocitas-project-generator-npm](https://github.com/eclipse-velocitas/velocitas-project-generator-npm). Feedback is welcome :)

After the generation of the repository is completed a pop-up dialog with your repository URL will be displayed. The newly created repository will contain:
- _/app/main.py_ with your prototype code transferred to your recommented app structure
- _/app/AppManifest.json_ with definition of required services
- _/app/requirements.txt_ with definition of requirements
- _/.devcontainer_/ required scripts to install everything in Microsoft Visual Studio Code 
- _/.gitHub/workflow/_ with all required CI/CD pipelines to build, test and deploy the vehicle application as container to the GitHub container registry

__Next step:__ [Extend the your use case with the component you need for you use case](/docs/step-3-exending.md)
