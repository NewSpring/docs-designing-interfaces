# Invision

Invision is a prototyping and collaboration tool used by companies from Adidas to Netflix. At NewSpring, we use Invision primarily for creating prototypes that can be used for our user testing.

#### Getting Started
You’ll want to download the Invision sync tool which allows you to sync files between your desktop and their browser based application. Invision requires you to specify what kind of device you want your project to be. This obviously limits you from creating a responsive prototype and necessitates choosing what device you want to use to conduct your usability testing. It’s important to use a separate Sketch file for your prototype in Invision, here’s why:

1. Your working file will likely have many artboards as you have iterated over your design. While it is [possible](https://support.invisionapp.com/hc/en-us/articles/203009709-How-does-Sketch-artboard-syncing-work-) to prevent all of these artboards syncing to Invision, I have found it far easier to simply copy the final artboards into a new document.

2. You will invariably have to duplicate artboards in order to replicate the required functionality for the prototype. Keeping this duplication isolated helps keep you from artboard mayhem in your working file.

3. Having a separate file for the prototype also helps to guard against any potential goofs or undesired changes if DLT members have the prototype installed.

#### Creating The Prototype
Once your sparkly new Sketch file has synced with the Invision project, you should see all your artboards. You will need to drag the images around so they are in the correct order.

![invision-project1](https://s3.amazonaws.com/uploads.hipchat.com/21097/1894791/w6uxDUKofpsP7Gx/upload.png)


When you click on one of your screens you are able to see it rendered within the device (except desktop). By clicking on the "build" button (the second icon on the bottom tool bar) you are able to define hotspots on the page. These hotspots trigger actions, such as navigating you to another screen with a fade through animation.

![invision-screen](https://s3.amazonaws.com/uploads.hipchat.com/21097/1894791/fbzFlYBcZYPRKkO/upload.png)

Using the Build Tool you are able to achieve some other nice effects, such as a static nav bar and overlays. For global patterns you can create templates, which are particularly useful for elements like nav bars.

You’ll need to go through each screen, linking them together and defining the kind of animations you want. Typically it is best to default to the fade through, unless you are trying to demonstrate a specific movement linked to the functionality. For example, the music player sliding up from the bottom.

#### Make It Tall, Make It Proud
The goal with the prototype is to get as close as possible to a production-like experience so that the average user cannot tell the difference. This often requires the duplication of artboards and adjusting of animations, in order to mimic some of the more complex feature sets. While this additional work may seem fruitless, it’s precisely this attention to detail that will create the illusion of reality when conducting usability tests. This cannot be understated or undervalued.

When creating your prototype there will undoubtably be aspects of the application that have not been designed yet; we are using prototyping and testing a specific set of features or pages. One addition that goes a long way to aiding usability tests is the inclusion of an overlay saying something similar to:
“This Section Of The App Is Coming Soon”
The overlay should be triggered on any pieces of missing functionality. This helps avoid confusion on what pieces of the prototype do and do not work. Furthermore it reinforces the expectation that anything they are supposed to interact with will result in some kind of response.


