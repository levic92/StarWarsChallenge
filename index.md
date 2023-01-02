---
layout: default
title: Star Wars Challenge
description: React Native app to better visualize Star Wars's planets
---

## Summary

Custom UI designed and mocked up using Sketch with the following screens:

1. List of planets
2. Planet Details
3. Settings

Technical Highlights:

1. Custom navigation animation transition using the image of the planet as a shared element
2. No 3rd party UI libraries were used (filter, search, select, pagination all implemented from scratch)
3. Light and Dark themes were created. This can be set automatically based on the phones current theme, or manually changed by the user
4. Planet's residents are queried from an external API. This data is also cached to the phone's local storage for offline use
5. Created 2 branches to demonstrate different data handling methods
  * One branch uses MobX-State-Tree
  * The other uses Redux Toolkit

## Screenshots

Jedi Theme            |  Sith Theme
:-------------------------:|:-------------------------:
![Light 1](/assets/images/1.PNG) |  ![Dark 1](/assets/images/D_1.PNG) 
![Light 2](/assets/images/2.PNG) |  ![Dark 2](/assets/images/D_2.PNG) 
![Light 3](/assets/images/3.PNG) |  ![Dark 3](/assets/images/D_3.PNG) 
![Light 4](/assets/images/4.PNG) |  ![Dark 4](/assets/images/D_4.PNG) 
![Light 5](/assets/images/5.PNG) |  ![Dark 5](/assets/images/D_5.PNG) 
![Light 6](/assets/images/6.PNG) |

## Demo

<video width="50%" preload="auto" muted controls>
  <source src="/StarWarsChallenge/assets/images/demo.mp4" type="video/mp4" />
</video>



# Technical requirements

1. Create a mobile only application displaying a list of planet cards using the `planets-ui.json` file.
2. Each card should contain the following data:
   * `name`
   * `terrain`
   * `climate`
   * `population`
   * `residents` (Number of known residents)

3. The data needs to be filterable and sortable as follows:
   * The user should be able to filter by `name` using a text field.
   * The user should be able to filter by `climate` using a dropdown field.
   * The user should be able to filter by `terrain` using a multiselect dropdown field.
   * The user should be able to sort data by `name`, `population` and `residents`.

Bonus.
1. Are you part of the dark side and cannot live without a dark theme? Let's make it!
2. Are you an old master that cannot process 60 planets at once? Let's add a pagination to remove noise from the Dashboard!

## Challenge requirements

1. Avoid UI libraries as much as possible and implement your own utilities, styles and UI components.
   * For example, we want the filter components implemented from scratch.
   * Copying in totality or partially a library is considered as using a UI library.
2. Know that a cleaner and high quality submission is worth more than a feature complete, but messy one.
3. Remember that as UI engineers, UIs are an integral part of our lives and good-looking UI is as important as a well functioning one.
4. Try to treat this as the base for an enterprise application. How do you setup state, business logic and code structure in your ideal application?
5. Feel free to choose any React Native stack that can accomplish these requirements.
6. Have fun and get creative!
