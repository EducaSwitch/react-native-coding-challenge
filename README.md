# React-Native Coding Challenge

## Idea of the App : Instant Search
The task is to implement a small app that will list Github repos as the the user searches in a search bar. 
You'll be fetching the sorted JSON data directly from the Github API (Github API explained down below). 

## Features
* As a User I should be able to list Github repos that match the search terms entered by the user. 
* As a User I should see the results as a list. One repository per row. 
* As a User I should be able to see for each repo/row the following details :
  * Repository name
  * Repository description 
  * Numbers of stars for the repo. 
  * Username and avatar of the owner. 
* [BONUS] As a User I should be able to keep scrolling and new results should appear (pagination or infinite scroll).
* [BONUS] As a User I should be able to click on a repository item and display the detail about the repo.


## Things to keep in mind 🚨
* Features are less important than code quality. Put more focus on code quality and less on speed and number of features implemented. 
* Your code will be evaluated based on: code structure, programming best practices, legibility (and not number of features implemented or speed). 
* The git commit history (and git commit messages) will be also evaluated.
* Do not forget to include few details about the project in the README (e.g explain choice of libraries, how to run it ...) 

## How to get the data from Github 
You need to use the Github GraphQL API <https://developer.github.com/v4/>

## Mockups
<img src="https://raw.githubusercontent.com/teopeurt/react-native-coding-challenge/master/screen-1.png" width="448">

<img src="https://raw.githubusercontent.com/teopeurt/react-native-coding-challenge/master/screen-2.png" width="448">

## Technologies to use 

* For styling: React Native Paper for styling <https://callstack.github.io/react-native-paper/>
* For fetching: Apollo Client <https://www.apollographql.com/client/>
* For state: Your preference. Context, Redux, Mobx, etc

