                                                    Android Fundamental


	Android is a mobile operating system, This operating system is used on various devices such as mobile phones, 
    tablets, smartwatches, and internet of things from various vendors. Android uses the SDK to provide tools and 
    APIs for developing applications.
 
How to Apply
	Ships with core set of apps, written in Java
	Developers have access to core APIs

Libraries
	C/C++
	Media libraries – A/V, images
	Surface manager – 2D/3D graphic layers
	LibWebCore – web browser engine
	SGL – 2D graphics engine
	3D – hardware or software acceleration
	FreeType – BMP and vector fonts
	SQLite – database engine

Main Components
	Activities
	Services
	Content Providers
	Broadcast Receivers

Content Provider
	Manages shared set of application data
	Data may be shared between apps or be private
	Performs data handling functions

User Interface Basics
	Recall the basic unit of an Android application is an Activity
	An Activity displays the user interface
	User Interfaces are built from View and ViewGroup object instances of the View class
	View objects are data structures that store content and layout parameters 
	Subclass  “widgets” provide user interface objects

Application Menus
	Two types of menus
    	accessed by pressing the MENU button on the device
    	accessed by pressing and hold down on an object
	Options menus allow users quick access to an application’s functions, preferences and settings
	Structured using a View hierarchy
	Handle their own events, no need to register event  listeners
	Selections handled by methods
	Items for menus can be declared in an XML file like an application layout


Sensor Constants
	public static final float GRAVITY_EARTH = 9.80665
	public static final float LIGHT_FULLMOON = 0.25
	public static final float MAGNETIC_FIELD_EARTH_MIN = 30.0
	public static final float PRESSURE_STANDARD_ATMOSPHERE = 1013.25
	public static final float GRAVITY_THE_ISLAND = 4.815162
	public static final float GRAVITY_DEATH_STAR_I = 3.5303614E-7

Bluetooth
	Bluetooth Adapter
	Local radio state
	Discover devices
	BluetoothServerSocket
    	Receives connection requests
    	Returns a BluetoothSocket when connected
	BluetoothSocket
    	InputStream object
    	OutputStream object


