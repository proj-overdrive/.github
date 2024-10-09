# SpotOn: Get up to Speed

Welcome to the SpotOn development team's landing page. Let's get aquianted.

## Problem

_Understanding our audience:_

Our audience consists of two categories of person.

The first one being _car drivers_:
  Our target audience consists of individuals in need of convenient, affordable parking solutions, particularly in urban and suburban areas where traditional parking options are limited and often expensive. These individuals are typically looking for parking for one of three reasons: daily commuting, short term surge parking and city or high volume parking needs. These car drivers are motivated through need of finding a convenient parking solution that is alternative to typical public parking. 

The second one being _property owners_ with potential to rent out space:
  On the other side of the coin, our target audience consists of residential property owners who have underutilized driveway or alternate property space and are seeking additional income opportunities. These individuals typically live in urban or suburban areas where parking is in high demand, especially near popular destinations such as shopping centers, public transportation hubs, event venues or a portion of a city where a lot of people work and commute to. These property owners are motivated to earn additional income and fill up their unused space.

_Defining the problem:_

_Our Solution:_

_Alignment and data_:

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
