## Mars Weather Station

Josh Shears
Tauheed Cyrus Ali
Praise Olaniyi

## Description

A weather application for the planet Mars, tracking weather for the past 7 days.
Problem Statement: To track weather on another potential habitable planet in our solar system, and to better understand how weather differs between Earth and Mars

## Objectives

o Let the user look up Mars weather for the past 7 days (sols)

o Show each day’s high, low pressure and sky condition in a card that is easy to read

o Pull the data live from NASA via JSON, and show a clear message if the request fails (data not available requested by user, API error)

o Let the user filter, sort, and save what they are interested in.

o Put the code on GitHub, each member owns work they wrote

## Key Features

o User Interface: Two tabs, Weather and Watchlist. A form to pick how many of the most recent days to show, a sort menu and a °C/°F button.

o Core Functionalities: One card per day showing the sol number and Earth date, the air high and low, the ground high and low, the pressure and the trend word NASA sends with it, the sky condition, the UV level, the Martian month, and sunrise and sunset with the length of daylight worked out from them. Sort the cards by latest, coldest, warmest or highest pressure.

o Summary Bar: The coldest and warmest day in view, the average pressure, and the biggest gap between a day’s high and low.

o Watchlist: A Save button on every card adds that day to the Watchlist tab, which keeps its contents when the page is reloaded.

o Advanced Features: async/await with try...catch, a live NASA API call, two classes with one extending the other, and event delegation for the Save and Remove buttons.

o Collaboration: The code lives in a shared GitHub repository, with one file per member so the work stays separate.

## API

o NASA Curiosity (MSL) weather feed:
https://mars.nasa.gov/rss/api/?feed=weather&category=msl&feedtype=json

o Documentation:
mars.nasa.gov/msl/weather
