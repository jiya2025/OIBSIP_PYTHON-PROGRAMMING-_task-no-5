# OIBSIP_PYTHON-PROGRAMMING-_task-no-5

🎯 **Objective:**

To **develop a basic real-time chat application** using Python, where two users can communicate through the command line. The goal is to understand the fundamentals of:

* Client-server communication
* Socket programming
* Multi-threading
* Real-time data exchange

This serves as a **foundational project** in networking and is ideal for students or beginners exploring backend development or computer networks.

🧰 **Tools & Technologies Used:**

| Tool/Library              | Purpose                                                                 |
| ------------------------- | ----------------------------------------------------------------------- |
| **Python 3.x**            | Main programming language                                               |
| **Socket module**         | Provides low-level networking interface for client-server communication |
| **Threading module**      | Enables sending and receiving messages simultaneously                   |
| **Command Line (CLI)**    | Interface to interact with the application                              |
| **Localhost (127.0.0.1)** | Testing environment for server-client setup                             |

🔄 **Steps Involved in Development:**

 1. **Understand the Client-Server Model**

* Learn how a server listens for incoming connections.
* Understand how a client initiates a connection to the server.

 2. **Develop the Server Script**

* Initialize a socket object.
* Bind it to a local host and port.
* Accept incoming connections.
* Handle multiple messages using a `while` loop and `recv()` method.

 3. **Develop the Client Script**

* Create a client socket.
* Connect to the server using the same host and port.
* Send messages from the client to the server using `send()`.

 4. **Use Multi-threading for Real-Time Chat**

* Use the `threading` module to:

  * **Thread 1**: Listen for incoming messages.
  * **Thread 2**: Allow the user to type and send messages.

 5. **Test the Application**

* Run the server in one terminal and the client in another.
* Send and receive messages.
* Implement exit conditions (e.g., typing "bye").

 6. **Add Basic AI-style Messages (Optional)**

* Friendly greetings like "👋 Hello from Server!".
* Formatting messages for better readability.

 ✅ **Expected Outcome:**

| Feature                        | Description                                                          |
| ------------------------------ | -------------------------------------------------------------------- |
| **Two-way real-time chat**     | Enables communication between a client and server.                   |
| **Socket communication**       | Demonstrates how Python can be used for network-level data transfer. |
| **Command line UI**            | Simple terminal interface without GUI.                               |
| **Threading for multitasking** | Send and receive messages without blocking either side.              |
| **AI-style prompts** (bonus)   | Adds human-like friendliness to enhance UX.                          |

