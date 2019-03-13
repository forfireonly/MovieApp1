# PopularMovies1

## The app:

Presents the user with a grid arrangement of movie posters upon launch.
Allows user to change sort order via a setting:
The sort order can is by most popular or by highest-rated
Allows the user to tap on a movie poster and transition to a details screen with additional information such as:
original title
movie poster image thumbnail
A plot synopsis (called overview in the api)
user rating (called vote_average in the api)
release date

![app_1](https://user-images.githubusercontent.com/29640816/54173438-93875f00-4447-11e9-9fb1-bea0fb9c9035.gif)

The app does not crash when there is no network connection

![no_internet](https://user-images.githubusercontent.com/29640816/54173529-f7118c80-4447-11e9-9415-7024cfbb9a9a.gif)

## Installing APP on your phone

To make a apk from this repo download android folder using git or any tool that you prefer.

And open android studio if don't have this download it from this link

If you don't have the android sdk with you then download android studio bundle

http://developer.android.com/sdk/index.html

For this you will need jdk . If you don't have this dowload it and install it.

http://www.oracle.com/technetwork/java/javase/downloads/index.html

And add the jdk path as JAVA_HOME in environmental variable.

And install your android studio.

Then open the android studio and import downladed repo earlier.

Android studio will resolve the dependencies and after all is done you can build an apk from it.

You can get the apk from the app-build-output-apk folder.

## API key

Follow directions to obtain personal API key on  https://www.themoviedb.org/

put your API key in MainActivity.java in line 40
public static String API_KEY = "YOUR-API-KEY";
