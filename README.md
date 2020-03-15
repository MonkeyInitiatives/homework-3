# README #

## Password Generator ##
This is a simple password generator that allows a user to create a randomized password based on the number of lowercase, uppercase, numbers, and special characters. Passwords are created dynamically on input or by clicking the Generate Password button. All passwords are fully randomized and must be greater than 8 characters in length, but less than or equal to 128 characters. Once a password is generated, a user may then copy it to their clipboard with a click or tap.

### Goals and Methods ### 
It is 2020, and no one should be using the same password for every site. This site allows any user to generate a random password to their own specifications. By limiting the user to input criteria via HTML input forms, validation is made much easier; only integers between 0 and 128 are allowed, and a password is not generated unless it is between 8 and 128 characters in length. Further protection is applied by checking that all integers are non-negative, and no non-numeric characters are allowed in the input forms. Furthermore, the generated password can only be copied to the clipboard when a valid password is created. 

### Technology ###
This site was created in HTML with minimal inline CSS styling, and the Bootstrap CDN. All logic is written in javascript and is client-side, meaning no generated password is sent to anyone but the user.

### Installation ###
No installation is required. Please visit the link to use the site: [http://monkeyinitiatives.com/password-generator/](http://monkeyinitiatives.com/password-generator/)

### Issues ###
Currently none, but feedback is appreciated. 

### Site Images ###

Desktop:
![Desktop image example](https://github.com/MonkeyInitiatives/password-generator/blob/master/assets/images/readme-images/site-desktop.png?raw=true)

Mobile: 
![Mobile image example](https://github.com/MonkeyInitiatives/password-generator/blob/master/assets/images/readme-images/site-iphone.png?raw=true)