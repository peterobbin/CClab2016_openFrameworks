# CCLab 2016 - oF
## week1
### What is openFrameworks
#### about oF
openFrameworks is an open source C++ toolkit designed to assist the creative process by providing a simple and intuitive framework for experimentation.
openFrameworks can be distributed as a desktop app, and iOS app. It can even run in a webpage!
#### What is open source, and what does it mean to you
openFrameworks is distributed under the MIT License. This gives everyone the freedoms to use openFrameworks in any context: commercial or non-commercial, public or private, open or closed source. While many openFrameworks users give their work back to the community in a similarly free way, there is no obligation to contribute.
Open source means you can use then for free!(YAY!) And you are free to contribute to it if you want to further develop or you found a bug. Be sure to give credit if you are using other people code!
### What is an IDE
An integrated development environment (IDE) is a software application that provides comprehensive facilities to computer programmers for software development. An IDE normally consists of a source code editor, build automation tools and a debugger. Most modern IDEs have intelligent code completion.
IDE is basically where you write your code and where you debug your app.
#### Xcode
Xcode is an integrated development environment (IDE) containing a suite of software development tools developed by Apple.
#### Visual Studio Community 2015
Microsoft Visual Studio is an integrated development environment (IDE) from Microsoft. It is used to develop computer programs for Microsoft Windows, as well as web sites, web applications and web services. Visual Studio uses Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, Windows Store and Microsoft Silverlight. It can produce both native code and managed code.
#### Oh I don’t use Mac or PC
Fancy! You can use QT Creator or Eclipse.
#### Which one is better?
Xcode is easy to start. But you should know and learn to use both of them. 
### Setting up the environment 
#### PC
1. Install Visual Studio Community 2015
2. Install Add-on to support openFrameworks
3. Download latest oF(0.9.4) for VS2015 from their website.
4. open the empty example in ```OF_ROOT/examples/empty```project by clicking on the .sln file. (This is called solution file)
#### MAC
1. Install Xcode 8
2. Download latest oF(0.9.4) for Xcode from their website.
3. open the empty example project in ```OF_ROOT/examples/empty``` by clicking on the .xcodeproj file.

### Getting used to the environment  
#### Editor
This is where you write your code. Like processing main window.
#### Project Files Manager
This is where your project files will be. To be noticed that these are just a reference to your files (Especially in visual studio). If you add a new file in Finder/Explorer, they won’t show up in here. 
#### Console/Debug Window
This is where the program will spit out things. 
#### Build/Run (Build/Debug)
##### What does building mean?
Everything in a computer is represented by a series of 1's and 0's (which themselves represent high and low voltages on transistors, but that's a topic for another time). When the computer runs a program, the program itself is made of a bunch of 1's and 0's.
However, since we still need humans to write our programs, putting everything in 1's and 0's (called machine language) would be very difficult. So we made higher level languages like Java and C# to write code in. These languages look a lot more like English, so they're a lot easier to write and maintain.
When you compile code, the compilor (usually another program) takes the program the human wrote, and converts it into the program the computer can understand (i.e. converts from Java to machine language). The very short version could be, yes, compile means to make the code executable.
[Source](https://www.reddit.com/r/explainlikeimfive/comments/233dq5/eli5_what_does_it_mean_to_compile_code/)
##### Build/Debugging
You have to build first. Even if you run debug, the IDE will build it and then start the app.
Building the project does not mean starting the application. Debugging means: first, building the animation; then start the animation; while the application is running, spitting out useful  information for you to know if there’s something wrong. 

##### Do it in PC
* Build -> Build Solution [F7]
* Debug -> Start debugging [F5]

##### Do it in MAC
* Product -> Build [CMD + B]
* Product -> Run [CMD + R]

#### Now run the project to see if everything works

### Practice
Let’s write a simple openFrameworks program


