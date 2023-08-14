# Login Sample

-I created this repository for user login/registration using Jetpack Compose.

Libraries Used
--------------
* [Architecture][10] - A collection of libraries that help you design robust, testable, and maintainable apps.
  * [Lifecycles][11] - Create a UI that automatically responds to lifecycle events.
  * [Navigation][12] - Handle everything needed for in-app navigation.
  * [ViewModel][13] - Easily schedule asynchronous tasks for optimal execution.
  * [Coroutines][34] - A coroutine is a concurrency design pattern that you can use on Android to simplify code that executes asynchronously.
  * [Flow][14] - Works very well with coroutines, provides us with cold streams which can be transformed using well known reactive operators.
* [UI][20] - Details on why and how to use UI Components in your apps - together or separate
  * [Jetpack Compose][21] - A basic unit of composable UI.
* Third party and miscellaneous libraries
  * [Retrofit][30] for turns your HTTP API into a Java interface
  * [Gson][31] for convert Java Objects into their JSON representation
  * [Hilt][32] for [dependency injection][33]
  * [Lottie][35] for Animations.


Architecture
--------------
The app uses [MVVM architecture][10] to have a unidirectional flow of data, separation of concern, testability, and a lot more.

![Architecture](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)
