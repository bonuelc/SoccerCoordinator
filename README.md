# Soccer League Coordinator in Swift
Treehouse iOS Techdegree Project #1

You have volunteered to be the Coordinator for your town’s youth soccer league. As part of your job you need to divide the 18 children who have signed up for the league into three even teams - Dragons, Sharks and Raptors. In years’ past, the teams have been unevenly matched, so this year you are doing your best to fix that. For each child, you will have the following information: Name, height (in inches), whether or not they have played soccer before and their guardians’ names.

The project has three major parts. For each part, choose ONLY from the tools we have covered in the courses so far:

- Native types and collections to store data (Dictionaries, Arrays, Ints, Strings, etc...)

- Accessing, appending and counting Arrays

- Accessing Dictionaries and Arrays

- Creating control flow

- Use of comparison operators

- String Interpolation

- Use of comments

Please don’t employ more advanced tools we haven’t covered yet, even if they are right for the job. (Yes, that means no classes, structs, tuples or filters on Project 1.) However, if you identify a place where a more advanced tool is appropriate, please mention that in a code comment.

Part 1: We have provided information for the 18 players in the Player Info spreadsheet. Please choose an appropriate data type to store the information for each player. In addition, create an empty collection variable to hold all the players’ data. Once you have decided on what tools to use, manually enter the player data so it can be used in Part 2.

Part 2: Create logic that can iterate through all 18 players and assign them to teams such that the number of experienced players on each team are the same. Store each team’s players in its own new collection variable for use in Part 3. (Please note: your logic should work correctly regardless of the initial ordering of the players and should work, if we theoretically had more or less than 18 players, so NO MAGIC NUMBERS!)

Also, if you would like to attain an “exceeds expectations” rating for this project, add logic to ensure that each teams’ average height is within 1.5 inches of the others.

Part 3: Create logic that iterates through all three teams of players and generates a personalized letter to the guardians, letting them know which team their child has been placed on and when they should attend their first team team practice. As long as you provide the necessary information (player name, team name, guardians’ names, practice date/time), feel free to have fun with the content of the letter. The team practice dates/times are as follows: Dragons - March 17, 1pm, Sharks - March 17, 3pm, Raptors - March 18, 1pm

When your complete code is run in a playground the letters should be visible in the right hand pane. If the code is run within an actual Xcode Project, the letters should be visible in the console.

As always, meaningful and concise code comments are expected. Your code should be written and refined in an Xcode playground or Xcode project, but be sure to upload it to GitHub, as per the instructions provided in the Soccer Coordinator Video Instruction, linked below.

Good luck and Happy Coding!

# Project Requirements

Manually create a single collection that contains all information for all 18 players. Each player should themselves be represented by their own collection.

Create appropriate variables and logic to sort and store players into three teams: Sharks, Dragons and Raptors. Be sure that your logic results in all teams having the same number of experienced players on each.

Provide logic that prints a personalized letter to the guardians specifying: the player’s name, guardians' names, team name, and date/time of their first team practice. The letters should be visible when code is placed in a XCode Playground or run in an XCode project.

As always, please add concise and descriptive comments to your code and be sure to name your constants, variables and keys descriptively.

OPTIONAL: Also, if you would like to attain an “exceeds expectations” rating for this project, add logic to ensure that each teams’ average height is within 1.5 inches of the others. (Please note, this feature only needs to meet the 1.5inch threshold for this set of players, not for all potential future sets of players.)
