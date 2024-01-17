# AwesomeNBA
<img src="ScreenShots/logo.jpeg" width="10%"> 
Simple iOS App, done as a test task project for learning purposes in 2024 January.
<br>
Few keywords describing used tehnologies:
 - iOS-15
 - SwiftUI
 - MVVM
 - Alamofire
 - JSON
 - URLSession
 - Sync await
 - TabBar
 - NavigationView

[Description](#description)

[Implementation](#implementation)

[Demonstration](#demonstration)

## Description:
This App shows to User a lists of Data fetched from test API and helps to User to retrieve Teams list for the current NBA season, navigate accross them, search Player from list and see game scores for choosen Player's team or selected from the list Team. User also can sort Teams in the list by using provided Sorting options by pressing Sort button in the navigation bar.

Scfreen structure consist of two tabs (used TabBar), two pushable views and a sheet. For navigation it was used NavigationView an NavigationLink.

#### This app handles the following actions:

  1. Display the lists of Teams, Players, Games containing data, when it were successfully retrieved from API;

  2. It is possible to refresh data on each list on native iOS refresh action by swiping list down;

  3. It is possible to search a Player by his name or surname in the provided native Search field;

  5. Sorting of Team is availbale by presing on sort button. Currently have been implemented 3 sort option:
       - Sorting by Name
       - Sorting by City
       - Sorting by Conference

#### Disclaimers:

  1. As agreed by task description UI is simple as it is and focus of this task was not to create the impresive one. There no loading screens, empty state screens or failure;

  2. All possible NetworksError handled as simple as posible, with simple prints into XCode console;

  3. In accordance to Task descripton there is added Alamofire via Swift Package Manager. It is included only for demonstrational reasons and or real project it would;
  4. 
  5. There no Unit or UI tests included, due this project focus was not. But here was used Dependency Ijection and app project's structure is basically ready for adding tests. And it could be done easily on separate request.
<br>
<br>
  
## Implementation: 

0. The __App Icon__ and __App Title__:
1. 
<img src="ScreenShots/00_AppIcon.png" width="33%"> 
<br>

2. The __Launchig App__ - previews loading screen before initializing the App:

<img src="ScreenShots/01_LaunchApp.gif" width="33%">  
<br>
<br>

The App currently consists of two Tabs and 4 Screens in total. Below are presented all of them:

2. The __Teams Screen__ 2descriptionBelow:
  
<img src="ScreenShots/02_TeamsScreen.png" width="33%">  

Lorem Ipsum.

<br>
<br>

3. The __Players Screen__ 3descriptionBelow:
  
<img src="ScreenShots/03_PlayersScreen.png" width="33%">   

Lorem Ipsum.

<br>
<br>

4. The __Games Screen__ 3descriptionBelow:
  
<img src="ScreenShots/04_GamesScreen.png" width="33%"> 

Lorem Ipsum.
<br>
<br>

## Demonstration: 

1. Feature 1 demonstration:

<img src="ScreenShots/05_Navigation.gif" width="33%">   
   
2. Feature 2 demonstration:

<img src="ScreenShots/06_SortTeamsFeature.gif" width="33%">

3. Feature 3 demonstration:

<img src="ScreenShots/07_SearchForPlayerFeature.gif" width="33%">
