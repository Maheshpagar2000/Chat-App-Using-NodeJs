# Real-Time Chat Application

This project is a real-time chat application developed using Node.js and Socket.io. It allows users to join chat rooms, send messages, share locations, and view a user sidebar. The server is built with Express and Socket.io, and the client uses HTML, CSS, and JavaScript. Templating is done with Mustache.js, timestamp formatting with Moment.js, and query parameter parsing with Qs.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

- **Server-Side:**
  - [Node.js](https://nodejs.org/): JavaScript runtime for server-side development.
  - [Express](https://expressjs.com/): Web application framework for Node.js.
  - [Socket.io](https://socket.io/): Real-time bidirectional communication library.

- **Client-Side:**
  - HTML/CSS/JavaScript: Web technologies for the client-side interface and functionality.
  - [Mustache.js](https://github.com/janl/mustache.js): Templating library for rendering HTML templates.
  - [Moment.js](https://momentjs.com/): JavaScript library for date and time formatting.
  - [Qs](https://github.com/ljharb/qs): Library for parsing and stringifying URL query parameters.

## Features

1. **Chat Rooms:**
   - Users can join different chat rooms based on their preferences.
   
2. **Real-Time Messaging:**
   - Send and receive messages in real-time within the chat rooms.

3. **Location Sharing:**
   - Users can share their current location with others in the chat.

4. **User Sidebar:**
   - View a sidebar displaying the list of users currently in the chat room.

## Setup

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/real-time-chat-app.git
    ```

2. **Install Dependencies:**
    ```bash
    cd real-time-chat-app
    npm install
    ```

3. **Start the Server:**
    ```bash
    npm start
    ```

4. **Open the Application:**
    - Open your web browser and navigate to: [http://localhost:3000](http://localhost:3000)

## Usage

1. **Joining a Chat Room:**
    - Open the application and enter a display name and room to join.

2. **Sending Messages:**
    - Use the message input form to send real-time messages to the chat room.

3. **Location Sharing:**
    - Click the "Send Location" button to share your current location.

4. **Viewing User Sidebar:**
    - The sidebar displays the list of users currently in the chat room.

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback.

## License

This project is licensed under the [MIT License](LICENSE).
