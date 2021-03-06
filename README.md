# CitySearch (MVVM-C) Example
It's simple CitySearch app that's developed using MVVM-C pattern. 

## Why MVVM-C
**MVVM** is a design pattern that is widely used in the iOS application development. It take the data presentation and buisness logic of showing data to **View out of ViewController** making it clean, reuseable and small. ViewModel **binds data** to to UI elements and changes UI as soon as data changes. ViewController's responsibility is to notify ViewModel about the events that occur on the UI so ViewModel can react to those event accordingly. 

Combining **co-ordinator** with it, further reduces ViewController's responsibilty by taking out the navigation logic from it too and making it completely dumb and reusable.

## Benefits
- Avoids Massive-ViewControllers
- Keep UI as dumb as possible
- Define single responsibility to each module
- Works best with reactive-frameworks
