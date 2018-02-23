# 💪 Squats App 💪
### React Capstone Project, Epicodus

**Ginger Lee Kretschmer** -- _2018_

## Project Description and Goal

This a socially-minded application that is a curated workout program that will allow a group of users (a team) to join a 21-day workout challenge that will allow them to view a free youTube video for each day. After the workout is complete the user will add their name to the list of teammates who have completed the day's workout. Users will see all teammates who have completed the day’s workout.

The goal of this app is to leverage free workout content to a group of interested people and for them to be able to hold themselves accountable for the workout by seeing who has complete the workouts.

**Backstory**: The user in mind is a new mom who does not have much time to leave the house, who wants to get back in shape, and who also is on a budget. This is the very situation I was in last summer, and found myself using free youtube workout videos to get in short and quick home workouts, but without paying or being in a studio, it was hard to keep fully motivated and accountable. That experience and slight challenge to stay committed to the workouts gave me the idea to build a team workout app that uses the social aspect of a team to keep each other motivated. I am excited to build this because it encourages people to be active and healthy, and also builds community -- and it's fun!

## Minimum Viable Product Features
_A list of the absolute minimum features the project requires to meet_

#### HomePage:
**See User Name logged in:** Users will be able to see their name logged in at the top of the screen at all times. Logging in and out will be additional features after MVP.

**See Challenge Details:** Users will be able to view details of challenge.

**See Video List:** Users will be able to view all videos in a list for the challenge.

**See Team List:** Users will be able to view all team members signed up for the challenge.

**Click into any video:** Users will be able to click any video detail and be taken to video detail page (see below).

#### Video Detail Page:
  **Play video:** Users will be able to view and play the video of the day within the application in an iframe (iframe controls will allow user to play, pause, volume). Video will be stored in Firebase and will use a YouTube API.

  **View workout details:** Users will be able to view workout details, e.g. equipment, duration, intensity level, muscle group focus, etc. (these are hardcoded and stored in Firebase in the video object).

  **Mark workout as completed:** Users will be able to mark the workout completed. This action will add user name to the team leaderboard which shows who in the team has marked that workout completed

  **View team leaderboard:** User will be able to see which teammates, including themselves, have completed the workout video of the day.



## Tools, frameworks, libraries, APIs for MVP
* React (I want to do this in React Native, but will make that a refractor for Demo Day)
* Redux
* Jest (for unit testing)
* React Youtube NPM package
* YouTube Player API
* Firebase
* CSS - Styling and Animations
* Material UI/React Materialize

**If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.**


View previous/next video page - and all related details and actions listed above
View all videos list - new page of thumbnails of all videos in the challenge
Rebuild App in React Native
Allow user to login - perhaps using Auth0
Allow for multiple users
Create user profile page,
Show user information (name, image, tagline)
Show which videos they have watched
Challenge Badges for Completion
Show user progress/status for the challenge (how many workouts they have completed)
