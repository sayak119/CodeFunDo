# Idea

## Problem

During and after natural disasters, the main problem that arises is chaos due to losing of family members and loved ones. In our country, due to high population, its easy to get lost in the crowd during such times. This in turn increases pressure on the rescuers to both rescue people from physical harm like debris and also to find the loved ones of the rescued people.

## Solution

Our solution: Setup an online checking database where individuals can upload photos of loved ones missing from disaster events. A user uploads a photo of their missing person to our application. Then, using **Microsofts Facial Recognition API** we search through the database and see if the missing person, or first responders uploaded a picture of the missing individual. If time permits, add **Twilio** to send messages.

If the missing person's image is found in the database both uploaders receive confirmation of their loved ones safety. It will connect family in a time of crisis and reduce pressure. To make it more easy to used, we will make it for mobile devices and both iOS and Android compatible using **react-native** and **expo-sdk**.

## Usage

* People (rescuers, rescue camp workers and us) will upload the photos of the people they want to find which will be added inn the database.
* Microsoft's Facial Recognition API will search through the database and check for the person.
* Twilio integration will send messages about their loved ones.
