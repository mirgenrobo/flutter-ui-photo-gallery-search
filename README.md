# Flutter UI challenge 1 - Photo gallery search
> Creator: Qani Ajdini

## About
This app is using Unsplash API as service to search the photos and Shared Preferences to register the favorite user photos in the cache memory. The model's classes were created to better represent an official development, the services classes are responsible for the boundaries of the system like the API and cache management library. The app is using BLOC pattern as an architectural pattern.

### Unsplash API
This app used [Unsplash API](https://unsplash.com/developers) as photo search Engine. It's free to use, so if you want to fork this repository and reuse the code, be sure to use your Access Key at this [classe](./lib/services/PhotosAPI.dart). Then the app will run perfectly. 

### Design and Implementation Details
The inspiration video just shows the User Experience when searching for some categories in the app. This app brings something more like Favorites Photos, Personalized Bottom Menu Bar, Image Details, API Request Structure and more.

## Design

![Design](./docs/inspiration.gif)

## Implementation

![Implementation](./docs/app-running.gif)