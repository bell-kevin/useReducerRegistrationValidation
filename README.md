# Registration Input and Validation with useReducer and useContext

You worked on a project for registration input and validation at the end of Section 7. In that project, you used the useContext and useState hooks. In this project, you will use the useReducer hook instead of useState. You should end up with the same 7 screenshots as in the previous project, but the state of the variables will be handled differently in this project.

Begin by making a COPY of the previous project.

Where is state managed in that previous project? You should have the description and initialization of the state in the file for the user context, which uses useState and declares each state variable with its setter function. In this project, replace the useState hook and its work with the useReducer hook. Wherever you worked with the state variables in the project, there might be a need for changes to use the reducer function in this project. You should find that the changes in this project are not numerous or large.

Add a header on each page that specifies this is the project that uses the useReducer hook. Here are examples:

![reducer-1.PNG](https://github.com/bell-kevin/useReducerRegistrationValidation/blob/main/readMeExamplePictures/reducer-1.PNG)     ![reducer-2.PNG](https://github.com/bell-kevin/useReducerRegistrationValidation/blob/main/readMeExamplePictures/reducer-2.PNG)

![reducer-3.PNG](https://github.com/bell-kevin/useReducerRegistrationValidation/blob/main/readMeExamplePictures/reducer-3.PNG)     ![reducer-4.PNG](https://github.com/bell-kevin/useReducerRegistrationValidation/blob/main/readMeExamplePictures/reducer-4.PNG)

![reducer-5.PNG}(https://github.com/bell-kevin/useReducerRegistrationValidation/blob/main/readMeExamplePictures/reducer-5.PNG)

You don't need to take screenshots of the alerts after pressing the Yes or No buttons on the validation page.

Take 5 screenshots, as shown above.

Submission: Zip together the root folder and the 5 screenshots, and submit the single zipped folder.

![p]()

![p]()

![p]()

![p]()

![p]()

## How to:

Create one app. for both Android and iOS (Apple) using one computer alorithm for both apps. You'll need Visual Studio Code and Android Studio to get started:

https://code.visualstudio.com/download

https://developer.android.com/studio

If you want to see how your app. will look on iOS (Apple) devices, you'll need Xcode from the Apple app. store:

https://developer.apple.com/xcode/

To run the Xcode app, you'll need a fairly new Apple computer.

https://reactnative.dev/docs/environment-setup

https://reactnative.dev/docs/components-and-apis

https://reactnative.dev/docs/intro-react

Check out App.js here in the code files for the computer algorithm code.

## Storing Projects

When you complete a React Native project, you should keep it on your storage device for a little while. There are multiple instances where one project will be the basis of another project. The Udemy course keeps building on the projects, so you definitely need to keep those around until you are done with that project in the course.

BUT -- React Native projects are huge. There is a folder, node_modules, that takes up most of the space. If you keep every project you create in this course, you would need at least 20GB of space, probably more. How can you manage this terrible drain on your storage?

That node_modules folder is automatically added when you create a new project. Once you are done with the project, you can delete that folder, node_modules, and the size of your project will shrink dramatically.

This does not destroy the project. If you find you need to run an old project again, which no longer has its node_modules folder, open it in Visual Studio Code, open a terminal, and type "npm install". This will load the node_modules folder again, and the project is whole and ready to run.

Note that when you delete that folder, it takes a noticeable amount of time, far more than it takes to reload it.

A good practice for course maintenance is to keep the project in its full state until you are sure you won't be using it in the next few days, then delete the node_modules folder.

== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project. I have a [website](https://bellKevin.me) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the [Give up GitHub](https://GiveUpGitHub.org) campaign 
from [the Software Freedom Conservancy](https://sfconservancy.org) to understand some of the reasons why GitHub is not 
a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
email me at **bellKevin@pm.me** for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
