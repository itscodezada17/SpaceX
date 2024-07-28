# SpaceX Android application
It is a SpaceX Android application, displays information about SpaceX launches, store and searches.

**API Used- https://api.spacexdata.com/v3/launches

# Features
Home Screen
Display a list of SpaceX launches.
  * Each list item should show the mission name, launch year, and rocket name.
  * Implement endless smooth scrolling to load launches seamlessly.

Detail Screen
Launch Detail Screen
 Detailed Information Screen:
  * When a user clicks on a launch item, navigate to a detail screen.
  * Display detailed information about the selected launch, including mission name, Mission Image,
    launch year, rocket details, launch site, and links to media and articles.

Search Tab
  Search Functionality:
  * Allow users to search for launches by mission name, launch year, and rocket name.
  * Display the search results.

Store Tab
   WebView:
   * Load the URL SpaceX Vehicles. (https://www.spacex.com/vehicles/falcon-9/)


# Technologies Used
1. LANGUAGE : Kotlin , XML
2. Architechture : MVVM , Single Activity using Fragments, Clean Architecture
3. Dipendency Injection : Hilt
4. Network Call : Retrofit
5. Image Loading : Glide
6. List items : RecyclerView
7. used Coroutines(for network calls)
8. Navigation: Jetpack navigation
9. Searilization : Gson


# Assumptions 
1. Focused on Code Quality and Architecture , Readability following best practices and design patterns

# ScreenShots


https://github.com/user-attachments/assets/13380be2-d2bd-4922-a2b6-176b37ad7cb0



<code><img height=400  src="https://github.com/itscodezada17/SpaceX/blob/master/media/home.png" alt="ss2"></code>
<img height=400  src="https://github.com/itscodezada17/SpaceX/blob/master/media/search.png" alt="ss2">
<img height=400  src="https://github.com/itscodezada17/SpaceX/blob/master/media/search1.png" alt="ss2">
<img height=400  src="https://github.com/itscodezada17/SpaceX/blob/master/media/searchByYear.png" alt="ss2">
<img height=400  src="https://github.com/itscodezada17/SpaceX/blob/master/media/store.png" alt="ss2">

  
# APK 
  APK - <a href="https://github.com/itscodezada17/SpaceX/blob/master/app-debug.apk" alt="APK Link"><img src="https://img.shields.io/badge/APK-DownLoadApk-yellowgreen"></a>
  
  Click on the button above and download from there.
