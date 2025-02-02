# azimr24-hw1 - Recipe Finder

Full-stack recipe search application using React and Flask with Spoonacular API integration.

## Setup

### API
Go to https://spoonacular.com/food-api/console#Dashboard and create an account. Get the api key and place it into a
.env file with the following structure: 

SPOONACULAR_API_KEY=your-api-key
FLASK_ENV=development

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
pip install -r requirements.txt
python app.py
```

### Frontend
```bash
cd frontend
npm install
npm start
```

Running the above code for backend and frontend in your terminal should run the website on localhost:3000.