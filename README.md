🍹 CocktailApp

Welcome to CocktailApp, an iOS application that lets users explore, save, and share a wide variety of cocktail recipes. Built using Swift, this app offers a delightful and user-friendly experience for cocktail enthusiasts.

Table of Contents

Features
Screenshots
Requirements
Installation
Usage
Project Structure
Contributing
License
Acknowledgements
Features

Browse Cocktails: Discover an extensive collection of cocktail recipes with images and detailed instructions.
Search: Find cocktails by name or ingredients.
Favorites: Save your favorite cocktails for easy access.
Random Cocktail: Get random cocktail suggestions.
Share: Share your favorite cocktail recipes with friends and family.
Screenshots




Requirements

iOS 13.0 or later
Xcode 12.0 or later
Swift 5.0 or later
Installation

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/cocktail-app.git
cd cocktail-app
Install dependencies:

This project uses CocoaPods for dependency management. If you don't have CocoaPods installed, you can install it using:

bash
Copy code
sudo gem install cocoapods
Then, navigate to the project directory and install the dependencies:

bash
Copy code
pod install
Open the project:

bash
Copy code
open CocktailApp.xcworkspace
Build and run the project:

Select your target device or simulator, and press the run button in Xcode.

Usage

Browse Cocktails:

Launch the app to view a list of popular cocktails.
Tap on a cocktail to see the detailed recipe and ingredients.
Search Cocktails:

Use the search bar to find cocktails by name or ingredient.
Save Favorites:

Tap the heart icon on a cocktail detail page to save it to your favorites.
Get Random Cocktail:

Tap the dice icon to get a random cocktail suggestion.
Share Cocktails:

Tap the share icon to share the cocktail recipe with your friends.
Project Structure

Model: Contains data models representing the cocktail recipes.
View: Contains UI components.
ViewModel: Manages the logic to bind data between the Model and View.
Controller: Contains view controllers that manage the views and handle user interactions.
Contributing

We welcome contributions to improve CocktailApp! To contribute, follow these steps:

Fork the repository

Create a new branch for your feature or bug fix:

bash
Copy code
git checkout -b feature/your-feature-name
Implement your changes.

Commit your changes:

bash
Copy code
git commit -m "Description of your changes"
Push to the branch:

bash
Copy code
git push origin feature/your-feature-name
Create a pull request on GitHub.

For detailed instructions, please refer to our Contributing Guide.

License

This project is licensed under the MIT License. See the LICENSE file for more information.

Acknowledgements

Thanks to TheCocktailDB for providing the cocktail API.
Special thanks to all contributors and users who have helped make this app better.
