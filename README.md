# Star War API Wrapper
A wrapper project over swapi API

## Install Dependancy
npm preinstall


## Run the server
npm start



# API endpoints

## GET '/character/:name'
It returns an EJS view with data about the given character

## GET '/characters'
It returns raw JSON of 50 characters. It also support query param 'sort', valid value are [height]

## GET '/planetresidents'
It returns raw JSON in the form {planetName1: [characterName1, characterName2], planetName2: [characterName3]}. 
