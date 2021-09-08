# Android Fundamental

**Android** is a software stack for mobile devices that has SDK for providing tools and APIs to develop apps

## Main Component
Main Components of Android:
1. Activities
2. Services
3. Content Providers
4. Broadcast Receivers

### Activities
Activities is a single page UI. There is multiple activities inside the apps and it can be callable from other apps (with permissions)

### Services
Services has no UI, it runs in the backgrounds, and can be started and stopped by activities

### Content Provider
It manage shared set of application data. The data itself may be shared between apps or being private. Content provider also performs data handling function

### Broadcast Receiver
Broadcast Receiver, or similar with interrupt handler that redirects to appropriate activity or service, listens for system wide or intent broadcasts but there is a limits for intent filter.

> Intents allow an activity, service, or broadcast receiver to linked


## User Interface
UI displayed by an activity. It built from View and ViewGroup object instances. 

### View and ViewGroup
View objects are data structures that store content and layout parameters

ViewGroup objects act like container or layouts for one or more View objects. 

Sublass of layout:
- LinearLayout (Display view in linear direction either horizontally or vertically)
- RelativeLayout (Display view in relative position to each other)
- TableLayout (Display with rows and column. Example: for displaying button for the calculator)
- AbsoluteLayout
- FrameLayout
- ScrollView
    
### Input Events
Example:
- View.OnClickListener
- View.OnTouchListener
- View.OnKeyListener


# Intro Android 1

## Development and Building Process
1. UI Design with XML code
2. Application development with Java/Kotlin
3. Building with DSL Gradle
4. Testing
5. Deployment

## Testing Model
1. Unit Testing
    - Testing source code of **Java units**. Running on JVM using **JUnit**.
2. Integration Testing
    - Integration of **Java source code** and **resources (XML + binary)**. Running on JVM using **Robolectric**
3. UI Testing
    - Testing **executable application**. Running on real device or emulator using **Espresso** or **MonkeyRunner**