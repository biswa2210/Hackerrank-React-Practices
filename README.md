# Slideshow Application :star_struck: 📱

[![Generic badge](https://img.shields.io/badge/advance-html5-red)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/javascript-advance-brightgreen)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react-framewrok-blue)](https://shields.io/)

***This new WebSite named 'Slideshow Application' is created by Biswarup Bhattacharjee, student of BTECH, in University of Engineering and Management, Kolkata.***

**Email Id: bbiswa471@gmail.com.** 

**Contact No: 916290272740.** 

<p align="left">
<a href="https://www.facebook.com/profile.php?id=100070395300810" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="biswa2210" height="30" width="40" /></a>
<a href="https://instagram.com/biswarup2210" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="" height="30" width="40" /></a>
<a href="https://github.com/biswa2210/biswa2210" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="" height="30" width="40" /></a>
</p>

## About :point_down: 

This is a website of my hackerrank solution. It is named as Slideshow Application.

## LINK of full project: :point_right: . 

## Purpose :point_down:

<div align="justified">
     
I have made this website to practice react concepts.
     
</div>

## Folder Structure :point_down:
```bash
Slideshow Application
     ├── Phones.js
     ├── applePhones.js
     ├── events.js
     ├── index.css
     └── index.js
```           
## Screenshots :point_down: 

<div align="center">
    
<a href=""><img src="" width="400" height= "280"></a> <a href=""><img src="" width="400" height= "280"></a>

<a href=""><img src="" width="400" height= "280"></a> <a href=""><img src="" width="400" height= "280"></a>

</div>

## Environment 

- React Version: 16.13.1
- Node Version: ^12.18.3
- Default Port: 8000

## Project Specifications 

Create a basic slideshow application, as shown below. Application requirements are given below, and the finished application must pass all of the unit tests.

![Gif](https://hrcdn.net/s3_pub/istreet-assets/j3Q6jXZ3DOOPRlCs9hFcnQ/slideshow.gif)

Your task is to complete the implementation of `src/components/Slides.js` according to the following requirements:

- The Slides component takes an array of slides as a prop. Each element of this array denotes a single slide and is an object with 2 properties: string title and string text.
- On application launch, the first slide must be rendered.
- Clicking on the "Next" button shows the next slide. This button is disabled when the current slide is the last one.
- Clicking on the "Prev" button shows the previous slide. This button is disabled when the current slide is the first one.
- Clicking on the "Restart" button returns to the first slide. This button is disabled when the current slide is the first one.
- You can assume that the passed slides array contains at least one slide.


Initially, the file is filled with boilerplate code. Note the following:

- The "Restart" button must have `data-testid="button-restart"`.
- The "Prev" button must have `data-testid="button-prev"`.
- The "Next" button must have `data-testid="button-next"`.
- Each slide's title must be rendered as an `<h1>` element with `data-testid="title"`.
- Each slide's text must be rendered as a `<p>` element with `data-testid="text"`.

Please note that the component has the above data-testid attributes for test cases and certain classes and ids for rendering purposes. It is advised not to change them.

**Read-Only Files**
- `src/App.test.js`

**Commands**
- run: 
```bash
bash bin/env_setup && . $HOME/.nvm/nvm.sh && npm start
```
- install: 
```bash
bash bin/env_setup && . $HOME/.nvm/nvm.sh && npm install
```
- test: 
```bash
bash bin/env_setup && . $HOME/.nvm/nvm.sh && npm test
```
