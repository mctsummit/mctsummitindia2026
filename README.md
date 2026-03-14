QuadGrid Showdown (Python)

QuadGrid Showdown is a 4×4 “tic‑tac‑toe style” game: two players alternate placing marks, and the first to complete 4-in-a-row wins (horizontal, vertical, or diagonal).
We won’t call it Tic Tac Toe in the app name—but the mechanics are essentially tic‑tac‑toe on a 4×4 board.

🧩 Objective
Build QuadGrid Showdown end-to-end with GitHub Copilot using Python. You will implement:

A 4×4 grid game (core logic)
A desktop UI with Tkinter
Convert it into a Web App (Flask or Streamlit)
Add winner detection + reset
Improve styling + alignment
Add a login page with auth flow
Follow best practices: decouple business logic from UI

✅ What Participants Will Deliver
By the end, your repo should contain:

A working game with winner detection, draw detection, reset
A UI version in Tkinter
A web version in Flask or Streamlit
A login gate before accessing the game page
Code structured with separated layers (logic vs UI)
A README.md describing how to run both UI and web versions

Hackathon Tasks (Detailed Instructions + Expected Output)

✅ Task 1 — Implement QuadGrid Showdown (4×4 Grid Game Core)
Goal
Implement the core game mechanics (4×4 “tic‑tac‑toe style” gameplay).

Acceptance Criteria

Correctly alternates X and O
Prevents invalid moves
Board state updates properly

✅ Task 2 — Add Desktop UI using Tkinter
Goal
Create a playable UI using Tkinter.

Acceptance Criteria

UI reflects the board state correctly
No crashes on rapid clicking
UI calls only core logic for gameplay rules

✅ Task 3 — Make it a Web App (Choose Flask OR Streamlit)
Goal
Build a browser-based version of the same game.

✅ Task 4 — Winner Detection + Reset
Goal
Implement win detection, draw detection, and reset functionality across all UIs.

Acceptance Criteria

Correct winner detection (including diagonals)
Draw detection when board full and no winner
Reset reliably restores initial state

✅ Task 5 — Better Styling + Alignment
Goal
Improve visual clarity and alignment.

Acceptance Criteria

Visual alignment is noticeably improved
No overlapping elements
Works on common screen sizes

✅ Task 6 — Add Login Page + Auth Flow
Goal
Add a login page. On successful login, route to the game page.

Acceptance Criteria

Auth state stored safely:

Streamlit: session_state
Flask: session


Logout clears auth state and returns to login

✅ Task 7 — Best Practice: Decouple Business Logic from Front End
Goal
Ensure the core game engine is reusable in both Tkinter and web versions.

