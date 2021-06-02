# GithubAppMVVM
 [![Platform](https://img.shields.io/badge/platform-Android-green.svg)](http://developer.android.com/index.html) [![Kotlin](https://img.shields.io/badge/kotlin-1.4.32-orange.svg)](http://kotlinlang.org) [![Gradle](https://img.shields.io/badge/gradle-4.0.0-%2366DCB8.svg)](https://developer.android.com/studio/releases/gradle-plugin)

## App Feature
- Search User On Github
- Add Favorite User
- Delete Favorite User
- User Favorite
- Reminder At 9:00 AM
- Localization
- Content Provider 
## ConsumerApp
- Subsribe Favorite User From Main App
## MVVM Architecture 
<p align="left">
    <img src="images/mvvm.png"
        style="margin-right: 20px;"
    />
</p>
   Android Architecture Components (MVVM) is one of the patterns released by Google. This collection of libraries helps you to design robust, testable and easily manageable       applications. The image above, is a big picture of Architecture Components. Each component has its own function. If broken down into components:
- View: It can be said as a UI controller or Fragment and Activity that serves to display data or perform actions in the UI.
- ViewModel: Provides data to the UI. Acts as a communication center between the Repository and the UI. The ViewModel function retains data from configuration changes.
- LiveData: Observable data holder class. Always holds/save latest version data. Notifies the observers when the data has changed. The UI component only observes or observes      relevant data and will not stop or continue to observe.
- Repository: You use the Repository to manage multiple data sources, such as network, local or cache origin.
- Room: Source of data from local database. Room is a library that provides an abstraction layer over SQLite to enable more robust database access by leveraging the power of SQLite.
- Rest Client: Data source originating from the network, such as Rest API, Firebase or other client data. 
