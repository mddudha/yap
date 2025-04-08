# Yap - A Chat Application

Yap is a real-time chat application built using **Spring Boot** on the backend and **STOMP.js** for real-time communication via WebSocket on the frontend. It allows users to send and receive messages in a modern chat interface, providing an interactive experience with instant updates.

## Features

- **Real-Time Messaging**: Send and receive messages instantly with WebSocket and STOMP.js.
- **Message Display**: Messages are neatly displayed with clear distinctions between sent and received messages.
- **WebSocket Integration**: Uses **STOMP protocol over WebSocket** for real-time communication.
- **Minimalist UI**: Clean and user-friendly interface with Bootstrap for styling.
- **Scalable Architecture**: Built with Spring Boot for easy scaling and extensibility.

## Tech Stack

- **Frontend**:
  - **HTML, CSS**: Used for creating the structure and styling of the chat UI.
  - **Bootstrap 5**: For responsive and modern UI components.
  - **JavaScript**: Handles the WebSocket connection and message handling using **SockJS** and **STOMP.js**.
  - **SockJS**: Used to handle WebSocket connections for browsers that do not support WebSocket natively.
  - **STOMP.js**: A JavaScript library for STOMP protocol communication over WebSocket, used to send and receive messages in real-time.

- **Backend**:
  - **Spring Boot**: Java framework used to build the backend of the application.
  - **Spring WebSocket**: Provides WebSocket support for handling message broadcasting.
  - **Spring Messaging**: For managing messaging between the frontend and backend over WebSocket.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Java 11 or newer
- Maven
- Node.js (for running the frontend)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/yap.git
