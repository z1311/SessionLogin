# Session Login
The most common method to authenticate is entering passwords but the disadvantage of this method is shoulder surfing. Instead of
directly enetring passwords, one time password or session password can be used. In this project for everytime a user wants to login a new 
session password is generated and used for that login session only. It generates session passwords by considering a matrix. Its an
8x8 matrix which consists of 26 lower-case letters, 26 upper-case letters, 0-9 digits, and 2 special characters (@,_) which adds upto 64 characters
. The only constraint is that the password should be of even length.<br >
The following gif explains the way to enter session password considering original password "abcd".

![Webp net-gifmaker](https://user-images.githubusercontent.com/47830313/56092639-3fefb180-5edc-11e9-85e6-3a00268b2170.gif)
