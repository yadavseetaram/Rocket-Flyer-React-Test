# React Interview

A React project to retrieve, render and manipulate data returned from an API.

## Commands

- **npm install**: Install dependencies.
- **npm start**: Runs the web application in developer mode

## Project Structure

Feel free to create new files to help you complete these tasks. Additional dependencies can be installed, if you think they are necessary.

- `src/index.js` is your react entry point.

- `data` directory is a mocked-API which exposes methods to get message information and member information from a conversation.
  It has two publicly exposed functions `getMessages` and `getMembers`.

- Your tasks will be to add further logic to display and manipulate the data returned from these functions, without modifying `data/index.js`. Code addition should be unit tested.

## Tasks

1. Connect application to redux store.

2. Render the list of messages from the redux store 

3. Display the user's email when you hover over the message.

4. Display and format the timestamp of the message to be in a human readable format, e.g. `1st Jan 2020 17:00` 

5. Sort the messages by time

6. Enhance the solution by rendering the user's name under the message. Once clicked it will take you through to a grid page showing all the user's messages:

   - Display the title of the message

   - Display and format the timestamp of the message to be human readable, e.g. `1st Jan 2020 17:00`

## Submission

Please upload your solution to your github account as a public repository, and send the URL to us.
