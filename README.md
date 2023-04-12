# Google-Chrome-Extension-for-Secret-Management


This is a Google Chrome Extension that generates a secret and stores it securely using encryption. The user must provide a password with confirmation to access the secret.

Installation
To install the extension, follow these steps:

Clone this repository to your local machine
Open Google Chrome
Navigate to chrome://extensions
Turn on Developer mode
Click Load unpacked
Select the cloned repository folder
The extension should now be installed
Usage
The extension window will pop up on installation. If the extension was not initialized before, it will generate and present a new secret to the user. The user will be asked to provide a password with confirmation.

Once the application is initialized, the extension will ask the user to log in. When the user is signed in, they will see the secret and have the option to regenerate the secret (which will replace the original secret) and log out.

When the user logs out, they will have the option to reset the extension state to a new-like application. On subsequent browser openings, the extension will not open a pop-up window. If the extension is initialized, it will face the user with the sign-in page. If the application was doomed or initialization was not complete, it will ask the user to proceed through the initialization process again.

Contact
If you have any questions or issues with this extension, please contact Amirhossein Rahnama at amirhosseinrahnama99@gmail.com.

License
This project is licensed under the MIT License - see the LICENSE file for details.
