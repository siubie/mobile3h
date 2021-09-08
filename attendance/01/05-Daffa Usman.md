Android
Android is a software stack of mobile devices. The tools and APIs to develop apps are provided by SDK.
Components of Android consist of Applications, Application framework, Libraries, Android runtime, and Linux Kernel.
Applications are ships with core set of apps, written in Java. And developers have access to core APIs such as views used to build application, content providers, resource manager, notification manager, and activity manager.
Libraries are the resources needed to develop an application. For example like programming languages, media libraries, surface manager, web engine, 2d graphics engine, hardware or software acceleration, BMP and vector fonts, database engine, etc.
Runtime and Kernel includes core set of libraries which provide most of core Java libraries. Each app runs its own process.
Main Components of Android :
a.	Activities -> Single page user interface where most apps have multiple activities, and callable from other apps if allowed.
b.	Service -> Background service that has no user interface and started or stopped by activities.
c.	Content Provider -> Manages shared set of application data whether to be private or not and performs data handling functions.
d.	Broadcast Receiver -> Listens to system wide (intent) broadcasts. Intents allows apps to use components of others.
User Interface :
•	A place to display android activity.
•	Built from View and ViewGroup object instances of the View class.
Input Events :
•	Defined to inform the system of user interaction.
•	Event listener is defined and registered with the View object.
Application Menus consist of 2 menus, Options menu which is when the application is running (accessed by pressing MENU button on the device.) and Context menu which is for displaying specific information about an item (accessed by pressing hold down an object).
