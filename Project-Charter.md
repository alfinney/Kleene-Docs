# Kleene → Project Charter

Team: Vaastav Arora, Andrew Davis, Abigail Finney, Jesse Gallardo, Daniel Tracy, and William Tyler
Last updated: January 16, 2019

### Problem Statement

There are hundreds of music services out there: Spotify, Apple Music, and Soundcloud, just to name a few. With this many services, there is bound to be restrictions on what services carry what kinds of music and which artists. With Kleene, this issue will be a thing of the past. This application will allow a user to sign in to all their services and keep their music libraries all in one convenient location. Playlists are now easier than ever to maintain, as users will now have the option to include songs from different music services.



### Project Objectives

1. Create an iOS application to manage a user’s music. The application will initially support Apple Music, Spotify, and Soundcloud. The application will be written with Swift.

2. Implement a Firebase backend to manage user authentication and store user data. Firebase provides convenient APIs for user authentication, and a realtime database for data storage.

3. Create a system for combined playlists, which can include songs from multiple different services. The data for combined playlists will be stored in Firebase.

4. Allow support for transferring songs between music services.

5. Support playing tracks in-app. This feature will be highly convenient for users who want an all-in-one hub for their music.

### 


**Project Owners:** Vaastav Arora, Andrew Davis, Abigail Finney, Jesse Gallardo, Daniel Tracy, and William Tyler

**Developers:** Vaastav Arora, Andrew Davis, Abigail Finney, Jesse Gallardo, Daniel Tracy, and William Tyler

**Users:** People who use multiple music services or want to switch services conveniently

**Project Coordinator:** Nanxin Jin

### 


1. An iOS application frontend which will allow the user to sign in or create an account if necessary. It will then present the user’s combined library in addition to options to sign in to different music services. The application will be written in Swift and use each service’s respective API along with Firebase in order to gain access to the songs a user has and support additional features.

2. We will create a Firebase project in order to support user authentication, data storage, and any server functions to support the application.

3. We plan to use the Spotify, Apple Music, and Soundcloud APIs. In addition, Spotify’s iOS SDK and Apple Music’s MusicKit may be used where necessary to support this application.
