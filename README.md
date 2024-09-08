# Notes
This is a simple Note-taking app built using modern Android development tools and libraries such as Jetpack Compose, Hilt (Dependency Injection), MVVM Architecture, and Room Database. The app allows users to create, save, update, delete, and sort notes.

Features
Create Notes: Users can create new notes by providing a title and description.
Save Notes: Notes are saved locally using Room Database for persistent storage.
Delete Notes: Unwanted notes can be deleted.
Sorting Notes: Notes can be sorted by title or date created.
Tech Stack
1. <u>Jetpack Compose</u>
Jetpack Compose is used as the UI framework, allowing for a declarative approach to building user interfaces in Android. This makes the app modern and simple to maintain.

Declarative UI: Build UIs by describing how the UI should look at any point in time.
Composable Functions: Reusable components to build UI efficiently.
2. <u>Hilt (Dependency Injection)</u>
Hilt is used for dependency injection, making the app more scalable and testable by providing dependencies (like repositories or use cases) to the ViewModel and other layers of the app.

Simplifies Dependency Injection: Hilt reduces the boilerplate required for dependency injection.
ViewModel Injection: Easily inject dependencies into ViewModels.
3. <u>MVVM Architecture</u>
The app is built using the MVVM (Model-View-ViewModel) architectural pattern to ensure a separation of concerns, making the app more modular and easier to test.

Model: Represents the data layer of the app (Room Database).
ViewModel: Contains business logic and exposes data to the UI via state (StateFlow).
View: Jetpack Compose UI which observes the ViewModel and reacts to changes.
4. <u>Room Database</u>
Room is used as the local database solution to store the notes. It provides an abstraction layer over SQLite, making database operations easier and more efficient.

Local Data Persistence: Store notes offline in the local database.
Data Handling: Room integrates with LiveData and Flow for observing changes in the database.

# Usage
Open the app to view a list of saved notes.
Click on the Add button to create a new note by providing a title and description.
Save the note by clicking the save button.
Notes can be sorted by title or date using the sorting feature.
To delete a note, swipe or use the delete option.
Contributions
Feel free to fork the repository and submit pull requests. Any contributions that improve the app are highly appreciated.
# Happy coding! 😄
