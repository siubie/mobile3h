First meeting learn about Android Fundamentals
What is Android?
    Software stack for mobile devices
    SDK provides tools and APIs to develop apps
Applications:
    -) Ships with core set of apps, written in Java
    -) Developers have access to core APIs
        ..Views used to build application
        ..Content providers – access data from other apps
        ..Resource manager – access to local strings, graphics
        ..Notification manager – display custom alerts
        ..Activity manager – manages app lifecycle
Main Components of Android
    - Activities
    - Services
    - Content Providers
    - Broadcast Receivers
Content Provider
    - Manages shared set of application data
    - Data may be shared between apps or be private
    - Performs data handling functions
Broadcast Receiver
    - Listens for system wide (intent) broadcasts
    - Intent filter limits which intents cared about
    - Similar to an interrupt handler
        -) Redirects to appropriate activity or service
