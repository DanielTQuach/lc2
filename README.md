# LC2 Social 1v1 Competitive Coding

A gamified, real-time competitive programming platform

## 🗺️ System Architecture
![System Design Diagram](./assets/system-design.svg)

## Core MVP Functionality (0 to 1 Scope)

### 1. The 1v1 Coding Arena
* **Direct Lobby Invites:** Users can generate a unique room link to invite a friend directly.
* **Blurred Progress Tracking:** Players see a blurred, real-time representation of their opponent's code length and typing activity to gauge progress without copying answers.
* **Spectator Mode:** The first player to pass all test cases wins the match and automatically switches to an unblurred spectator view of the remaining player.

### 2. Match Mechanics & Evaluation
* **Secure Execution:** User code is executed in an isolated, secure sandbox environment via Judge0/Piston APIs.
* **Language Support:** Launching exclusively with [Python] support.
* **Outcome States:** Matches end when one player successfully passes all test cases, or when the match timer runs out.

### 3. Data Tracking (Foundation for future ML)