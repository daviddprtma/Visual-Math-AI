<div align="center">
<h3 align="center">3rd Winner - Visual Math AI 🖌️</h3>
<p align="center">
An AI handwriting math solver with an interactive canvas
</p>
</div>

# Winner 3rd place Hackathon of Visual Math AI 🎉🏆

You can see the 3rd winner Hackathon of this project in below⬇️

<br>

![](https://github.com/daviddprtma/Visual-Math-AI/blob/2a8beab219d33970b5fe4dd2c7806f09b16418e8/stackup%20march%20hackathon%20winner.png)

<br>

![](https://github.com/daviddprtma/Visual-Math-AI/blob/96e52419ba1ec40fe99ada33021819bbc60bbba6/email%20stackup%20march%202025%20hackathon%20winner.png)

## Why Visual Math AI 🖌️✅

Visual Math AI  is an AI-powered math solver that allows users to draw mathematical expressions on a canvas and get instant solutions within the help of Gemini AI and integrates Gemini for solving expressions, which are then converted to LaTeX for make a draw become knownable to recognize so stackie can draw the mathematical problem & get to solve the problem just a second.

## Built With

- [React](https://react.dev/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Gemini AI](https://aistudio.google.com)
- [Python](https://www.python.org/)

## Features
- Interactive canvas: Draw mathematical expressions directly to the canvas.
- Gemini AI Powered Solver: Using Gemini 1.5 Flash to solve the mathematical problem.
- Real Time Feedback: Get the real time feedback after you write on the canvas and it will get the display result after you draw.

## Project Structure
## Frontend
- src/main.tsx: Main program for the React application.
- src/screens/home/index.tsx: Main screen where the canvas and solver logic are implemented.
- src/components/ui: Contains UI components like CommandBox and CommandBoxRun.
  
## Bckend
- main.py: Main point for the FastAPI application.
- apps/calculator/route.py: Contains the API route for processing images.
- apps/calculator/utils.py: Utility functions for analyzing images using AI.
- schema.py: The Pydantic models for request validation.

<h3>Prerequisites</h3>

- [NodeJS v14 or higher](https://nodejs.org/en/download)
- [Python v3.8 or higher](https://www.python.org/downloads/)
- Npm or yarn installed to your machine
### Installation

- Frontend 

1. Clone this repository
```sh 
git clone https://github.com/daviddprtma/Visual-Math-AI.git
cd Visual-Math-AI/frontend
```

2. Install dependecies
```sh
npm install
```

3.  Start the development server
```sh 
npm run dev
```

- Backend
1. Navigate to backend directory: 
```sh 
cd Visual-Math-AI/backend
```

2. Create a virtual environment & activate the environment: 
```sh 
python -m venv venv
source venv/bin/activate  #if using windows do this source venv/Scripts/activate
```

3. Install the dependecies:
```sh
pip install -r requirements.txt
```

4. Run the main.py file:
```sh
python main.py
```

# Usage

1. Open your browser and navigate to http://localhost:5173/.
2. Draw a mathematical expression on the canvas.
3. Press run to get the solver and see the results on the canvas.
4. Press reload if you want to clear the canvas.


<h1>Configuration</h1>

### Frontend 
- Vite Configuration: Located in vite.config.ts.
- TypeScript Configuration: Located in tsconfig.json.
- Environment Variables: Configure in .env file.
```yaml 
VITE_API_URL=http://localhost:8900
```
### Backend
Environment Variables: Configure in .env file.
```yaml
GEMINI_API_KEY=your_api_key_here
```

# Video Presentation
For the video presentation, see it in below ⬇️
<br>
<br>
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/oDZLG4nFIwY/0.jpg)](https://www.youtube.com/watch?v=oDZLG4nFIwY)

