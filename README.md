# Simple Article Sorting :star_struck: 📱

[![Generic badge](https://img.shields.io/badge/advance-html5-red)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/javascript-advance-brightgreen)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/react-framewrok-blue)](https://shields.io/)

***This new WebSite named 'Simple Article Sorting' is created by Biswarup Bhattacharjee, student of BTECH, in University of Engineering and Management, Kolkata.***

**Email Id: bbiswa471@gmail.com.** 

**Contact No: 916290272740.** 

<p align="left">
<a href="https://www.facebook.com/profile.php?id=100070395300810" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="biswa2210" height="30" width="40" /></a>
<a href="https://instagram.com/biswarup2210" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="" height="30" width="40" /></a>
<a href="https://github.com/biswa2210/biswa2210" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="" height="30" width="40" /></a>
</p>

## About :point_down: 

This is a website of my hackerrank solution. It is named as simple article sorting.

## Purpose :point_down:

<div align="justified">
     
I have made this website to practice react concepts.
     
</div> 

Create a basic article sorting application, as shown below. Some core functionalities have already been implemented, but the application is not complete. Application requirements are given below, and the finished application must pass all of the unit tests.

![sorting-app](https://hrcdn.net/s3_pub/istreet-assets/YkVzgbGgMj0cfT9P97s8jg/sorting-articles.gif)

The app has one component named Articles. The list of articles to be displayed is already provided in the app.

The app must have the following functionalities:

- The list of articles is passed to the App component as a prop in the form of an array of objects.
- Each article has the following three properties:
  - title: The title of the article [STRING]
  - upvotes: The number of upvotes for an article [NUMBER]
  - date: The publish date for the article in the format YYYY-MM-DD [STRING]
- By default, the articles should be displayed in the table ordered by the number of upvotes in descending order.
- Clicking on the "Most Upvoted" button should reorder and display the articles by the number of upvotes in descending order.
- Clicking on the "Most Recent" button should reorder and display the articles by date in descending order.
- You can assume that each article has a unique publish date and number of upvotes.

Your task is to complete the implementation of `src/App.js` and `src/components/Articles.js`.

The following data-testid attributes are required in the component for the tests to pass:

- The button to reorder and display the most upvoted articles must have the data-testid attribute "most-upvoted-link".
- The button to reorder and display the most recent articles must have the data-testid attribute "most-recent-link".
- Each article must be rendered inside a `<tr>` element that has the data-testid attribute "article".
- The title of each article must be rendered in a `<td>` element that has the data-testid attribute "article-title".
- The number of upvotes of each article must be rendered in a `<td>` element that has the data-testid attribute "article-upvotes".
- The publish date of each article must be rendered in a `<td>` element that has the data-testid attribute "article-date".

## Environment 

- React Version: 16.13.1
- Default Port: 8000

## Project Specifications 

**Read-Only Files**
- `src/App.test.js`

**Commands**
- run: 
```bash
npm start
```
- install: 
```bash
npm install
```
- test: 
```bash
npm test
```
