## Money Tracker

One day I had an urgent need to use a money tracker that I could use on my phone and my pc (on Windows and iOS), so instead of installing an existing app, I preferred to create one, because I am a dev, so I could create something while having fun doing it :) 
So I asked ChatGPT for some guidance, and it responded:

To create a money tracker app on Windows and iOS, I recommend using the following technologies.

#### MAUI 
You can use MAUI to build the user interface of your app, which will run on both Windows and iOS. 
You can use XAML to define the UI, and C# to handle the logic of the UI.

#### Firebase
You can use Firebase as your backend service for your app. 
Firebase provides a number of services such as authentication, storage, and a real-time database. 
You can use the Firebase SDK for .NET to interact with the Firebase services from your MAUI app.

#### .NET
You can use the .NET framework to build the logic of your app. 
You can use C# to interact with the Firebase SDK and handle the logic for the app.

#### ViewModels
You can use the MVVM architecture and create view models that will handle the logic of the app, and expose the data from the Firebase services in a format that can be easily consumed by the views.

#### Services
You can use Services classes to handle the interactions with the Firebase services, this way you can keep your code clean and separate the business logic from the views.

#### Dependency Injection
You can use Dependency Injection to inject the services into the view models, this way you can easily test the view models and the services.
Dependency Injection: You can use Dependency Injection to inject the services into the view models, this way you can easily test the view models and the services.

##### So, this is how MoneyTracker was born. 
