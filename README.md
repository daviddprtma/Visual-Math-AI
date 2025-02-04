
<br/>
<div align="center">
<h3 align="center">Visual Math AI 🖌️</h3>
<p align="center">
An AI handwriting math solver with an interactive canvas


  


</p>
</div>

## About The Project

Visual Math AI  is an AI-powered math solver that allows users to draw mathematical expressions on a canvas and get instant solutions within the help of Gemini AI and integrates Gemini for solving expressions, which are then converted to LaTeX for make a draw become knownable to recognize so stackie can draw the mathematical problem & get to solve the problem just a second.

## Built With

- [React](https://react.dev/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Gemini AI](https://aistudio.google.com)
- [Python](https://www.python.org/)


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

