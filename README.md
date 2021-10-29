# Project Overview

## Project Links

- [add your github repo link]()
- [add your deployment link]()

## Project Description

my project will be a simple idle game that uses game ticks to raise a current stat in x amount of time. it will have a character creation page that uses an api call with your name as a seed to return an avatar

## API
https://avatars.dicebear.com/api/bottts/nathaniel.svg
https://avatars.dicebear.com/api/bottts/micheal.svg
https://avatars.dicebear.com/api/bottts/evan.svg
https://avatars.dicebear.com/api/bottts/jason.svg

this api doesnt return a bunch of data like the other ones, just .svgs of those cute little guys. i plan on using the players name as a seed for my api call and use that as the players avatar

Use this section to include info about the API you have chosen and a code snippet of the data that it returns and is required for your project. 


```
{data: {} }
```


## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.

- [add link to your wireframes]()
- [add link to your react architecture]()


### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP EXAMPLE
- character creation 
- trainer iteration
- saves
- 

#### PostMVP EXAMPLE

- Add Shop and equipment
- add combat

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| splash page |entrance to choose name| 
| trainer bar(S) | this will display the actual idle bar| 
|stats page| display your current stats|
|equipment page| displays current equipment(even if there is none to aquire)


Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Also, put a gif at the top of your Readme before you pitch, and you'll get a panda prize.

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding saves | m | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 1| 2.5hrs | 2.5hrs |
| setting up compenents | H | 4| 2.5hrs | 2.5hrs |
| making trainers work | H | 15| 2.5hrs | 2.5hrs |
| calculating and displaying stats| H| 5 | | |
|adding shop| L | 5 hours | | |
|adding combat|L |1000 hours| | |
| Total | H | 40hrs| 5hrs | 5hrs |

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios, ReactStrap, D3, etc. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
