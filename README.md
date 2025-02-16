# Queue Ticketing System

# Overview
  - This project implements a queue-based ticketing system in C++. It simulates a simple queue management system where customers are issued tickets, and they are served in the order they arrive. The system provides various functionalities such as issuing tickets, tracking waiting clients, serving clients, and displaying ticket details.

# Features
  1. **Issue Tickets** : Generate a new ticket with a unique number and timestamp.
  2. **Track Waiting Clients** : View the number of clients currently in the queue.
  3. **Serve Clients** : Remove the next client from the queue when served.
  4. **Display Queue Information** : Print details about the queue, including total issued tickets, served clients, and waiting clients.
  5. **Left-to-Right (LTR)** : Tickets displayed from first to last.
  6. **Print All Tickets** : View detailed ticket information for all clients in the queue.

# Class Structure
` clsQueueLine `
  -  Manages the queue of tickets.
  -  Tracks total issued tickets and average serve time.
  -  Provides methods to issue, serve, and display tickets.

` clsTicket `
  -  Represents an individual ticket.
  -  Stores details such as ticket number, issue time, waiting clients, and expected serve time.
