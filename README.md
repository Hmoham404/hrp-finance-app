<<<<<<< HEAD
# HRP Finance App

## Overview
The HRP Finance App is a web application designed to analyze financial data using the Hierarchical Risk Parity (HRP) method. It allows users to upload Excel files containing financial data, automatically detect relevant sheets, and perform various analyses, including calculating returns, correlations, and generating interactive dendrograms for visualization.

## Features
- **File Upload**: Users can upload Excel files containing financial data.
- **Automatic Sheet Detection**: The application detects and processes relevant sheets (e.g., USA/Tunisia, Pre-COVID, COVID, Post-COVID).
- **Data Analysis**: Calculates returns, correlations, and distances using the HRP method.
- **Interactive Visualizations**: Displays dendrograms and heatmaps for correlation and distance matrices.
- **Export Results**: Users can download analysis results in CSV or PDF formats.
- **User Authentication**: Secure access to the application with JWT-based authentication (optional).
- **Responsive Design**: Modern dashboard layout that works on both mobile and desktop devices.

## Technologies Used
- **Backend**: Django, Django REST Framework
- **Frontend**: Next.js, React, Tailwind CSS
- **Data Processing**: Pandas, NumPy, SciPy
- **Visualization**: Plotly.js or D3.js
- **Database**: PostgreSQL
- **Containerization**: Docker

## Project Structure
```
hrp-finance-app
├── backend
│   ├── api
│   ├── analytics
│   ├── core
│   ├── models.py
│   ├── manage.py
│   ├── requirements.txt
│   └── Dockerfile
├── frontend
│   ├── components
│   ├── pages
│   ├── services
│   ├── styles
│   ├── package.json
│   ├── tailwind.config.js
│   └── postcss.config.js
├── docker-compose.yml
└── README.md
```

## Setup Instructions
1. **Clone the Repository**:
   ```
   git clone <repository-url>
   cd hrp-finance-app
   ```

2. **Backend Setup**:
   - Navigate to the `backend` directory.
   - Create a virtual environment and activate it:
     ```
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```
   - Install the required packages:
     ```
     pip install -r requirements.txt
     ```
   - Run database migrations:
     ```
     python manage.py migrate
     ```
   - Start the backend server:
     ```
     python manage.py runserver
     ```

3. **Frontend Setup**:
   - Navigate to the `frontend` directory.
   - Install the required npm packages:
     ```
     npm install
     ```
   - Start the frontend development server:
     ```
     npm run dev
     ```

4. **Access the Application**:
   - Open your web browser and go to `http://localhost:3000` to access the application.

## Contribution
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details."# hrp-finance-app" 
=======
"# hrp-finance-app" 
>>>>>>> 0afcc4810d21a5705d67038cdd19d924ba3839d4
"# hrp-finance-app22" 
