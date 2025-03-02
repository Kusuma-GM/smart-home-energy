# Smart Home Energy Snapshot

A mini energy monitoring system for a smart home that demonstrates both front-end and back-end development skills. This project displays hourly energy usage data in a bar chart, allows users to set a daily energy budget, and provides alerts if consumption exceeds the set budget. It also includes a time range check to display usage over specific hours.

## Features

- **Dashboard**: Visual display of hourly energy usage using Chart.js.
- **Daily Budget**: Set a daily energy budget and receive an alert if the total usage exceeds the budget.
- **Time Range Check**: Check energy usage over a specific time period.
- **Responsive Design**: Modern, responsive UI built with Bootstrap.
- **Statistics**: Top stats include total usage, average usage, peak hour usage, and budget status.

## Tech Stack

- **Back-End**: Django, Django REST Framework
- **Front-End**: HTML, CSS, JavaScript, Bootstrap, Chart.js
- **Data Source**: Static JSON file (for demo purposes; can be replaced with a live API)


## Installation

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Kusuma-GM/smart-home-energy.git
   cd smart-home-energy
2. **Create a Virtual Environment and Activate It**
   python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
# source venv/bin/activate
3. **install Dependencies**
If you have a requirements.txt file, run:
pip install -r requirements.txt
Otherwise, manually install Django and Django REST Framework:
pip install django djangorestframework
4. **Apply Migrations**
   python manage.py makemigrations
   python manage.py migrate
5. **Run the Development Server**
   python manage.py runserver
6. **Open the Application**
   Open your browser and navigate to http://127.0.0.1:8000/

   **Usage**
   **Dashboard**: View the bar chart displaying hourly energy usage.
   **Set Daily Budget**: Enter your daily energy budget in the provided field and click the "Set Budget" button. The system will display an alert if the total daily usage exceeds your set budget.
    **Time Range Check**: (If implemented) Check energy usage for a specific time range.
   
   **Future Enhancements**
   Connect to a live API for real-time energy data.
   Add user authentication to manage personalized dashboards.
   Implement predictive analytics (e.g., AI forecasting).
   Integrate with IoT devices for real-time monitoring.
