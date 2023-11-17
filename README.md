# Project Name

This project is built using JavaScript instead of Typescript for both the backend with Node.js and the frontend with React.js.
I have overlooked the instruction and due to time constraints I did not revised the project anymore. 
However the functionality of the app is good and successfully deployed in render.com.

## Project Structure

I used node.js for the backend and react.js for the frontend code. Each directory contains further subdirectories for organizing code logically.

## Development Environment Instructions

### Backend

1. In VSCode, open the Terminal.
2. Install dependencies using `npm install`.
3. Run the backend server using `npm start`.

### Frontend

1. In VSCode, open the Terminal.
2. Install dependencies using `npx create-react-app.`.
3. Start the React app using `npm start`.

## Execution Instructions
1. In using the TicTacToe Game App, just press the boxes and it will show the icon cross or circle according to the chance.
   If the user win the game, the app will display "Congratulations" message with player icon.
   And there is the reset button, when the user click na reset button the game will reset


## Compromises and Future Improvements

In the interest of time, some compromises have been made. Javascript was use instead of Typescript. 
Future iterations or additional time would allow for improvements in areas such as covertion from Javascript to Typescript and installation of react dev tools.

## Unhandled Error Cases

   * **# Error***
WebSocketClient.js:13 WebSocket connection to 'wss://tictactoegameapp.onrender.com:10000/ws' failed: 
    **# Here are a few steps to troubleshoot and fix the issue:**

1. Check the URL: Make sure that the WebSocket URL is correct. Verify the protocol (wss://), 
domain (tictactoegameapp.onrender.com), and port (10000) are accurate.

2. Server Configuration: Ensure that the WebSocket server is properly configured and running on the specified port (10000). 
If the server is not running, or if it's not configured to accept WebSocket connections, the client won't be able to connect.

3. Firewall and Network Issues: Check if there are any firewall or network issues preventing the WebSocket connection. 
Make sure that the specified port (10000) is open and accessible.

5. Server Logs: Look at the logs of the WebSocket server to see if there are any error messages 
or issues on the server side that could be causing the connection failure.

6. Browser Console: Check the browser console for additional error messages. 
There might be more details about why the WebSocket connection is failing.



