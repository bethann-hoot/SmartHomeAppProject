## Smart Home App
The problem isn't that smart home tech doesn't exist, it's that managing multiple devices means juggling multiple apps. Our solution was a cross-platform app where accessibility was part of the design from the beginning. We wanted anyone living in the home to be able to use it, whether that's a 70 year old grandma or her teenage grandkids.

## Features
If you aren't logged in, you would sign in to your account or create a new account. Once you were logged in you would land on the room layout page first where you would design your room layout and drag and drop different smart home devices into the different locations within the room. You can also label the room and the different devices for easy identification. From the hamburger menu you can navigate to the room layout, devices, settings, and the FAQ/tutorial pages.

From the Settings page you can set your personal preferences and update your user name and password. Settings include a light and dark mode, adjustable font sizing for accessibility, color themes, and a push notification toggle.

## Tech Stack
Flutter (Dart), Android Studio, local storage for account persistence

## My Contributions
I handled the initial mockups for our application with sketches and explanations of buttons/fields on each page. I collaborated with Damir to choose the default color scheme of the application. I was responsible for wireframing and coding the settings page, as well as the login and account creation pages. The code for the settings page also handled the global settings for the entire app.

## Team
Anthony handled the wireframing and coding of our room layout page. He ensured that both rooms and devices could be added, moved, resized, and deleted as needed. 

Damir collaborated with me for the overall color scheme and look of the application. He also wireframed the devices page and the FAQ/Tutorial page. He coded the hamburger menu, devices page, and the FAQ/Tutorial page.

## Running Locally
This project was developed and demonstrated using Android Studio and has not been deployed. To run it locally, you'll need Flutter and Android Studio installed.

## Future Considerations
Device connectivity would be the first priority for future development. Actually scanning for and communicating with smart home devices is what would make this app functional beyond a prototype. From there, refining and streamlining the existing design, and finally expanding the theming system to allow for more customization options beyond the two current color schemes.

