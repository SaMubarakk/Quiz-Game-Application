# Quiz Game Application

## Overview
The **Quiz Game Application** is a client-server system implemented in C that allows multiple users to engage in a real-time quiz. It utilizes TCP/IP sockets for communication, enabling simultaneous connections and interactive gameplay.

---

## Features
- Multi-user support: Multiple clients can connect and play simultaneously.
- Real-time feedback: Users receive immediate feedback on their answers.
- Score calculation: Final scores are displayed for all users at the end of the quiz.

---

## Technical Details

- **Language**: C both for server & client
- **Networking**: TCP/IP sockets for communication.
- **Multi-Computations**: Multi-threading to handle multiple clients.

---

## Getting Started

### Prerequisites
- C compiler (GCC, MinGW)
- Windows Terminal

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quiz-game-app.git
2. Compile Server/client codes:
   ```bash
   cd quiz-game-app
     gcc server -o server.c -lsw2_32
     gcc server -o server.c -lsw2_32
3. Run the compiled codes:

    Write `./server` afterthat `./client` each in a different Terminal tabs.
   
    Repeat `./client` to connect more clients.

   ---

   ## Contributing
   - **Contributions are welcome!**  Please open an issue or submit a pull request for any improvements.
       > **first level of development:**   We're working on implementing AI generated questions as well as giving the user the ability to choose the quiz level.
       
       > **second level of development:**  Add support for more players.
       
       > **third level of development:**   Enhance user interface with a GUI.
   
   ## Devolopers
   - MOHAMAD ALI ALCHIHABI   -2210206509 - Developer
   - SALEH MUBARAK           -2110206625  - Developer
     
