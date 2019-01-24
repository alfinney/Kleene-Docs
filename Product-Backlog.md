# Kleene → Product Backlog

Team: Vaastav Arora, Andrew Davis, Abigail Finney, Jesse Gallardo, Daniel Tracy, and William Tyler

Last updated: January 23, 2019

### Problem Statement

There are many music services available, yet no service alone has all the songs that you like. Kleene is a tool that combines all the major music services you use into one, allowing you to enjoy all your songs in one application.


### Background Information

#### Target Users

Music listeners are bouncing between services to find the songs they enjoy. Some of the most prominent music services are Apple Music, Spotify, and Soundcloud, and they all have a selection of millions of songs. Yet none of these services can function as an all-in-one music tool because many times a specific song isn’t available on a specific service. Kleene will be made to serve those users who have their favorite songs sprawled amongst different services.

Music service providers will also be incentivized to be supported by Kleene because Kleene users will be less likely to try to pick a single service to stick with. Kleene users will be more comfortable using more services, increasing the amount of users a service has.

#### Similar Platforms

To the best of our knowledge, there are no other services that combine multiple music services in the manner that Kleene is going to. There are other applications, which provide some of the specific features that Kleene will provide. For example, SongShift is an iOS app with a freemium model that allows users to move playlists between services. SongShift is a freemium service which is rooted in moving playlists from one service to another

Another paid app, Houdini Playlist Transfer, offers roughly the same set of features as SongShift and is ranked #54 in Music on the Apple App Store. This demonstrates the potential of a well-built, all-in-one music application that offers a larger superset of features. Kleene will offer more transfer options, from one song to entire music libraries, for free.


### Requirements

#### Functional

| As a user, I would like to be able to                                    | so that                                                                          |
| ------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| register for an account                                                  | I can link multiple services and create combined playlists.                      |
| login to my Kleene account                                               | I can access my customized content.                                              |
| sign into supported music service(s)                                     | I can listen to the music I already enjoy.                                       |
| have access to basic features without registering                        | I can become comfortable with the app without the inconvenience of registering.  |
| play music within the app                                                | I can enjoy a smooth music listening experience                                  |
| create a playlist that combines songs from multiple services             |                                                                                  |
| delete my account and any associated data                                | I feel like my privacy and personal information are respected.                   |
| transfer a song, playlist, album, or library from one service to another | I can put most of my music in one service.                                       |
| toggle between light and dark modes (if time allows)                     | I can choose the theme of my app based on my environment or personal preference. |
| set a language of my choosing (if time allows)                           | I feel more comfortable using the app.                                           |




| Aspect        | Description                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Accessibility | The app will be accessible to those who have minimum comfort using technology. Intuitive icons, layout, and navigation will pave the way for a delightful user experience. The app will be designed keeping in mind that most people are right-handed by placing more important items on the right and less important on the left.                                                                |
| Design        | The iOS Application will adhere to [Apple's Design Guidelines][1]. The app will use [material icons][2]where appropriate in order to provide an intuitive user interface, where the icons’ meanings will be recognizable to most users. The app will display a launch screen on startup, and use other responsive design strategies so that the user never feels as if the app is not responding. |
| Security      | The development team will never compromise security in favor of a feature or a bug fix. The application will use [Firebase][3] for features that require authentication, database, or other server functionality. Kleene will not misguide users on how we use or handle their data.                                                                                                              |
| Theme         | The application will initially be built with a dark color scheme. This will be easier on users’ eyes and the devices’ power.                                                                                                                                                                                                                                                                      |



<!-- Links -->

[1]https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/

[2]https://material.io/tools/icons/?style=baseline

[3]https://firebase.google.com/
