# Real-Time Notification System with SignalR

This project demonstrates the implementation of a real-time notification system using ASP.NET Core and SignalR. It allows clients to receive instant updates pushed from the server, providing a seamless and responsive user experience.

## Features

- **SignalR Hub:** The project includes a SignalR hub (`NotificationHub`) that facilitates real-time communication between the server and connected clients.

- **Client App:** A simple client application that establishes a SignalR connection and displays incoming messages in real-time.

- **Server Controller:** A server-side controller (`ServerController`) responsible for handling user requests and broadcasting messages to connected clients.

- **Model:** The `Notification` model class defines the structure of the notification messages.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/signalr-notification-system.git
   cd signalr-notification-system
## Usage
   - Open the client application (ClientNotification.cshtml) in your browser.
   - Enter a message in the form and click "Create."
   -The message will be instantly broadcasted to all connected clients and displayed in real-time.

### Technologies Used
          ASP.NET Core
          SignalR
          JavaScript
          HTML
          CSS

##  Acknowledgments  
         - Special thanks to the ASP.NET Core and SignalR teams for their excellent frameworks and documentation.
