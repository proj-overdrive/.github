# SpotOn: Get up to Speed
![Screenshot 2024-10-30 at 11 32 56 AM](https://github.com/user-attachments/assets/2881aee5-609d-4893-9364-fd3b77308141)

What we are: SpotOn is the only app in Canada dedicated to connecting drivers seeking parking with homeowners who have under-utilized space. Our platform provides drivers with affordable and reliable parking solutions while empowering homeowners to monetize their property.

Product Page: https://spoton480.carrd.co/

## Current features: 
- User Login
- Map View with Search
- Create/ View Spots
- Spot Booking
- ...

## Features to come:
- Saved Spots
- Map Spot List
- Checkout
- ...




## Problem

_Understanding our audience:_

Our audience consists of two categories of person.

The first one being _car drivers_:
  Our target audience consists of individuals in need of convenient, affordable parking solutions, particularly in urban and suburban areas where traditional parking options are limited and often expensive. These individuals are typically looking for parking for one of three reasons: daily commuting, short term surge parking and city or high volume parking needs. These car drivers are motivated through need of finding a convenient parking solution that is alternative to typical public parking. 

The second one being _property owners_ with potential to rent out space:
  On the other side of the coin, our target audience consists of residential property owners who have underutilized driveway or alternate property space and are seeking additional income opportunities. These individuals typically live in urban or suburban areas where parking is in high demand, especially near popular destinations such as shopping centers, public transportation hubs, event venues or a portion of a city where a lot of people work and commute to. These property owners are motivated to earn additional income and fill up their unused space.

_Defining the problem:_

Target Audience:

Homeowners with driveways who have extra parking space.
Individuals looking for convenient and affordable parking solutions, particularly in urban areas or during events.

Core Problem:

Many homeowners have unused parking spaces in their driveways, while people often struggle to find convenient parking, especially in busy neighborhoods, near event venues, or during peak times.

Current Solutions:

Traditional parking solutions (like public lots) can be expensive and often lack availability.
Existing parking apps typically focus on public parking spaces and may not utilize private driveways, missing out on a valuable resource.
User Needs:

Homeowners need a simple way to monetize their unused parking spaces without extensive effort.
Renters need a user-friendly platform to find and book available parking spots quickly, with clear pricing and flexible time options.
Impact of the Problem:

Homeowners miss out on potential income from unused space.
Renters face frustration and higher costs when searching for parking, leading to stress and wasted time.
Unique Value Proposition:

The app connects homeowners with renters seamlessly, providing a user-friendly interface to list, find, and book driveway parking spots.
It offers features like real-time availability, secure payment options, user reviews, and flexible rental periods (hours or days).

_Our Solution:_

The proposed solution is a Kotlin Multiplatform app that enables homeowners to list their driveway parking spots for rent and allows users to search for and book these spots easily. The app will provide a consistent experience across both Android and iOS platforms, leveraging Kotlin's capabilities to share code and reduce development time.

Our app will include a variety of key features as well as user interfaces. 

This Kotlin Multiplatform app provides a comprehensive solution for homeowners and renters, optimizing parking space utilization while ensuring a user-friendly experience. By leveraging shared code and native performance, the app can efficiently address the parking needs of urban users while creating a new income stream for homeowners.

_Alignment and data_:

https://docs.google.com/spreadsheets/d/1ussPlMTlFAP6CS3SntBy9xUUGSbJNq31iLuj9b25Rrc/edit?usp=sharing

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
