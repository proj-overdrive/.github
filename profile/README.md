# SpotOn: Get up to Speed
<img width="1327" alt="image" src="https://github.com/user-attachments/assets/7a3eee7c-84d5-41cc-bc2e-63810db869f4">

What we are: SpotOn is the only app in Canada dedicated to connecting drivers seeking parking with homeowners who have under-utilized space. Our platform provides drivers with affordable and reliable parking solutions while empowering homeowners to monetize their property.

Product Page: https://spoton480.carrd.co/

Lyssna Usability Test: https://usabi.li/do/b41120af9859/2d79

Lyssna Usability Test Results: https://app.lyssna.com/tests/b41120af9859/results/993ad60bf836

TestFlight Beta Testing: https://testflight.apple.com/join/RCYYjpxb


This Kotlin Multiplatform app provides a comprehensive solution for homeowners and renters, optimizing parking space utilization while ensuring a user-friendly experience. By leveraging shared code and native performance, the app can efficiently address the parking needs of urban users while creating a new income stream for homeowners.


## Features

We use [AirTable](https://airtable.com/app2entj4klzsFxDn/tblEcrk8XWS0tI4Tw/viwjmX7JGQmWvBxIY?blocks=hide)
to keep a working set of features, as well as their development progress. Take a look here if you're
interseted in what's underway right now, and what's up next.

## Application

The SpotOn application is broken down into three parts.

![seng480arch drawio](https://github.com/user-attachments/assets/20b9835b-95cf-4043-9bd0-2bb31655edd0)

## Garage

This is the database for our application. It's ultimately responsible for how
out data is modeled and persisted.

To get up and running, clone the `garage` repo, and perform all steps included
in the `README.md`. You should now have a Docker container which contains a Postgres
database.

## Parkade

Parkade is the server-side buisness logic of our application which provides
RESTful API endpoints for all of our data.

To get up and running, clone the `parkade` repo, and perform all steps included in the `README.md`.
You should now have a web server running on `http://localhost:8080`.

## Cruiser

Cruiser is the client application user interface for our app. It targets iOS and Android.

To get up and running, clone the `cruiser` repo, and perform all steps included in the `README.md`.
Next, build either the iOS or Android target from within Android Studio.
You should now have a mobile application running in an emulator.
