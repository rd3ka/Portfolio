---
title: '"Yet Another" Applications'
description: 'List of some applications/programs already made but implemented/cloned and written by me for the purpose of learning'
dateString: April, 2020
---

# 🔗 [Yet Another Weather App](https://github.com/rd3ka/YAWeather)
![](../ss_01.png)

### Motivation
To strengthen the fundamentals of web development and web based technologies. Collaboration was also a core factor to consider since this project taught me to collaborate with other fellow developers.
>Huge shoutout to [Riya](https://www.github.com/buna26) for contributing weather specific codes to help map weather icon.

### Behind the Scene
For front end, this application uses tailwindcss. TailwindCSS makes styling easier and intuitive reducing the time it takes to write the front end. The backend uses vanilla JS for DOM manipulation. [wttr](https://wttr.in) is used to fetch weather data in JSON. Best part of wttr is that it has a huge list of weather properties in different formats w/o any API limitations or auth keys.

### Dependencies
If you want to add more feature and continue to develop. Please install these dependencies using npm. Node is a d-level dependency and should be installed 

```bash
npm -i tailwindcss 
```
In the package.json file add this line:
```json
"scripts": { 
"tailwind": "npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch"  
}
```
To compile tailwindcss into normal css:
```bash
npm run tailwind
```

# 🔗 [Yet Another Quiz App](https://github.com/rd3ka/YAQuiz)
![](../screenshot-04.png)

As the name suggests, YAQuiz is yet another basic `JavaScript` webapp working as a wrapper for [OpenTriviaDB](https://opentdb.com/).

### Motivation 
With the rapid growth of web and web based technologies, I started to think how important it has become to know about web-dev. And that is precisely why I started to learn about the web. I believe that learning through doing is greater than learning by consuming media or reading. Hence this webapp is the amalgamation of my knowledge about the web.
> Huge shout-out to [James Q Quick](https://github.com/jamesqquick) from whom this app is heavily inspired and who taught to build from scratch. You can find his original work [here](https://github.com/jamesqquick/Build-A-Quiz-App-With-HTML-CSS-and-JavaScript)

### Behind the Scene
For the front-end structure and styling, `HTML` & `CSS` is used and back-end is handled by vanilla `JavaScript`. Data is fetched using `fetch` API from [OpenTriviaDB](https://opentdb.com/). 

# 🔗 [Yet Another Email Administration System](https://github.com/rd3ka/YetAnotherEmailAdminAPI)

### Purpose
The main development of this project started back in the year 2021. This project is a guided
project from the [Udemy](https://www.udemy.com/course/practice-java-by-building-projects/) 
Certification Course "_**Practice Java By Building Projects**_" with my own take. It is also
my attempt to understand **High Level System Design** using `java`
