# 2d platformer engine prototype

A basic 2D platformer engine built from scratch, featuring moving platforms, physics, and controllable objects.
---

## Features

- Player movement: run, jump, and shoot  
- Simple physics interactions  
- Moving platforms  
- Ability to switch between controllable objects  

---

## Controls

| Action                  | Key(s)        |
|-------------------------|---------------|
| Move left               | **A** or |
| Move right              | **D** or |
| Jump                    | **Space**     |
| Shoot                   | **Left Click** |
| Switch controlled object | **Q** or **E** |

---

## Technology

- Written **from scratch in TypeScript**  
- Dockerized for simple deployment  
- Uses `tsc` (TypeScript compiler) to convert TS → JS before dockerization  
- Requires **Node.js** installed globally for compilation  

---

## Roadmap

Currently not planned to continue development.  
This project remains as an early prototype.
---

## Running Locally

1. Navigate to the `html` directory.  
2. If you don't have `tsc` installed globally, run:

    npm install

3. Compile TypeScript to JavaScript:

    tsc 
    or to watch for changes: tsc --watch

4. Serve the generated JavaScript using a Live Server extension or any static server.
   No need to run Docker for local development.