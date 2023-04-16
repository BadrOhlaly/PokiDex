This application is a Pokedex programmed in Java that leverages an HTTP API to retrieve and present information about various Pokemon species. 
The application's primary feature is a search functionality, which allows users to search for Pokemon by name. When a Pokemon is selected, 
a new layout is generated, displaying specific details, such as the Pokemon's weight, height, and various stats, including HP, attack, defense, and speed.
 Additionally, a GIF image of the selected Pokemon is displayed to provide visual context. Overall, 
the application is designed to be straightforward and user-friendly.

featrues: 

List of all Pokemon with their names and images.

Search bar to search for Pokemon by name.

Details page for each Pokemon showing their weight, height, and stats (HP, attack, defense, speed).
 
Technologies: 
The Android SDK serves as the backbone for the app's user interface and functionality, while the Java programming language is utilized as the primary tool for creating the app's logic. 
To display Pokemon images in the app, 
the Picasso and Glide image loading and caching libraries are employed. 
To ensure a consistent user interface is maintained across different versions of Android, the AppCompat and Legacy Support Library are utilized. Developers can create intricate and adaptable layouts with ease using ConstraintLayout.
 The app is tested using the JUnit and Espresso testing frameworks for unit and UI testing, respectively.
 Additionally, the CardView library is utilized to present Pokemon details in a Material Design card-like format.
