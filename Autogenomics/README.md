#Hello-world
tutoricals series
Hello World! Build Your First iPhone App
You may have heard of “Hello World” program if you have read any programming book before. It has become the traditional program for first-time learner to create. It’s a very simple program that usually outputs “Hello, World” on the display of a device. In this tutorial, let’s follow the programming tradition and create a “Hello World” app using Xcode. Despite its simplicity, the “Hello World” program serves a few purposes:
It gives you a better idea about the syntax and structure of Objective C, the programming language of iOS.
	•	It also gives you a basic introduction of the Xcode environment. You’ll learn how to create a Xcode project and create user interface with the built-in interface builder.
	•	You’ll learn how to compile a program, build the app and test it using the Simulator.
	•	Lastly, it makes you think programming is not difficult. I don’t want to scare you away. 
You may have heard of “Hello World” program if you have read any programming book before. It has become the traditional program for first-time learner to create. It’s a very simple program that usually outputs “Hello, World” on the display of a device. In this tutorial, let’s follow the programming tradition and create a “Hello World” app using Xcode. Despite its simplicity, the “Hello World” program serves a few purposes:
	•	It gives you a better idea about the syntax and structure of Objective C, the programming language of iOS.
	•	It also gives you a basic introduction of the Xcode environment. You’ll learn how to create a Xcode project and create user interface with the built-in interface builder.
	•	You’ll learn how to compile a program, build the app and test it using the Simulator.
	•	Lastly, it makes you think programming is not difficult. I don’t want to scare you away. 
Start Coding!
1.First, launch Xcode. If you’ve installed Xcode via Mac App Store, you should be able to locate Xcode in the LaunchPad. Just click on the Xcode icon to start it up.
2. Once launched, Xcode displays a welcome dialog. From here, choose “Create a new Xcode project” to start a new project:

3.Xcode shows you various project template for selection. For your first app, choose “Single View Application” and click “Next”.

This brings you to another screen to fill in all the necessary options for your project.
You may have heard of “Hello World” program if you have read any programming book before. It has become the traditional program for first-time learner to create. It’s a very simple program that usually outputs “Hello, World” on the display of a device. In this tutorial, let’s follow the programming tradition and create a “Hello World” app using Xcode. Despite its simplicity, the “Hello World” program serves a few purposes:
	•	It gives you a better idea about the syntax and structure of Objective C, the programming language of iOS.
	•	It also gives you a basic introduction of the Xcode environment. You’ll learn how to create a Xcode project and create user interface with the built-in interface builder.
	•	You’ll learn how to compile a program, build the app and test it using the Simulator.
	•	Lastly, it makes you think programming is not difficult. I don’t want to scare you away. 
Take a Look at Your First App
Before we go into the coding part, let’s first take a look at our version of the “Hello World” app. The final deliverable will look like this
Your First iPhone App – Hello World
It’s very simple and shows only a “Hello World” button. When tapped, the app prompts you a message. That’s it. Nothing complex but it helps you kick off your iOS programming journey.
Start Coding!
First, launch Xcode. If you’ve installed Xcode via Mac App Store, you should be able to locate Xcode in the LaunchPad. Just click on the Xcode icon to start it up.

Once launched, Xcode displays a welcome dialog. From here, choose “Create a new Xcode project” to start a new project:

Xcode – Welcome Dialog
Xcode shows you various project template for selection. For your first app, choose “Single View Application” and click “Next”.

Xcode Project Template Selection
This brings you to another screen to fill in all the necessary options for your project.

Project Options for Hello World App
You can simply fill in the options as follows:
	•	Product Name: HelloWorld – This is the name of your app.
	•	Company Identifier: com.test – It’s actually the domain name written the other way round. If you have a domain, you can use your own domain name. Otherwise, you may use mine or just fill in “edu.self”.
	•	Class Prefix: HelloWorld – Xcode uses the class prefix to name the class automatically. In future, you may choose your own prefix or even leave it blank. But for this tutorial, let’s keep it simple and use “HelloWorld”.
	•	Device Family: iPhone – Just use “iPhone” for this project.
	•	Use Automatic Reference Counting: [checked] – By default, this should be enabled. Just leave it as it is.
	•	Include Unit Tests: [unchecked] – Leave this box unchecked. For now, you do not need the unit test class.

Click “Next” to continue. Xcode then asks you where you saves the “Hello World” project. Pick any folder (e.g. Desktop) on your Mac. You may notice there is an option for Source Control. Just deselect it. We’ll discuss about this option in the later tutorials. Click “Create” to continue.

As you confirm, Xcode automatically creates the “Hello World” project based on all the options you provided. The screen will look like this:


Familiarize with Xcode Workspace
Before we move on to code your app, let’s take a few minutes to have a quick look at the Xcode workspace environment. On the left pane, it’s the project navigator. You can find all your files under this area.
As you select the file, the editor changes to an Interface Builder and displays an empty view of your app like below:

In the lower part of the utility area, it shows the Object library. From here, you can choose any of the UI Controls, drag-and-drop it into the view. For the Hello World app, let’s pick the “ Button” and drag it into the view. Try to place the button at the center of the view

To edit the label of the button, double-click it and name it “Hello World”.


Try to run the app again and you should have an app like this:

For now, if you tap the button, it does nothing. We’ll need to add the code for displaying the “Hello, World” message.
Coding the Hello World Button
In the Project Navigator, select the “ViewController.h”. The editor area now displays the source code of the selected file. Add the following line of code before the “@end” line:
Next, select the “ViewController.m” and insert the following code before the “@end” line:

Forget about the meaning of the above Objective-C code. I’ll explain to you in the next post. For now, just think of “ButtonAction” as an action and this action instructs iOS to display a “Hello World” message on screen.
Connecting Hello World Button with the Action
But here is the question:
How can the “Hello World” button know which action to invoke when someone taps on it?
Next up, you’ll need to establish a connection between the “Hello World” button and the “ButtonAction” action you’ve just added. Select the “main Storyboard” file to go back to the Interface Builder. Press and hold the Control key on your keyboard, click the “Hello World” button and drag to the “File’s Owner”. Your screen should look like this:
write Code some  alertview controller to show message than run your app just tap on button and show message which write in alert view.
Test Your App
That’s it! You’re now ready to test your first app. Just hit the “Run” button. If everything is correct, your app should run properly in the Simulator.
Congratulation! You’ve built your first iPhone app. It’s a simple app however, I believe you already have a better idea about Xcode and how an app is developed.
