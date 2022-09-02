###ENVIRO


## Inspiration

Sustainability is one of the challenges that humanity must tackle in the near future. We aim to integrate augmented reality technology and artificial intelligence into an intelligent application with the goal of helping individuals find new ways to tackle this problem. 

## What it does

Enviro is an intelligent application that utilizes telemetry collected from a smartphone's camera in order to figure out ways to enhance sustainability and bring about beautiful environments by reducing urban sprawl. The app hooks directly into the camera system to reduce overhead and allow for the most precise measurements. It analyzes the scenery using the information gathered through the camera and aims to provide simple suggestions to the end user of ways that they could make their environment better, such as adding trees or reducing crowded weeds. Enviro is also capable of using augmented reality in order to superimpose models of possible additions onto the frame of view in order for the user to understand the endless possibilities of how they can transform their world.

## How we built it

This application was built around the echoAR augmented reality framework, which provides a console to add CAD models and visualize them in a deployed environment. We imported 3D models that we built using Tinkercad into the console, and then used the framework to create a test application using React JS and Apple's ARKit to demonstrate the .obj file. To create the application UI demo, we utilized Figma and Canva.

## Challenges we ran into

The main challenge was trying to utilize some of the binaries on the arm64 platform, as some of the core components such as cocoapods were written for x86-64 only. This critical mistake set development back a significant amount of time. 
