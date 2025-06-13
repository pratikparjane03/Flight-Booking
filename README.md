# 🛫 AeroPredict and Flight Booking

AeroPredict is a Django-based web application designed to provide users with flight delay predictions and a simplified flight booking experience. It uses machine learning for delay predictions and offers a seamless user experience for searching and booking flights.

## 📌 Features

- ✈️ Flight Delay Prediction using ML
- 🗓️ Search and Book Flights
- 👤 User Registration & Authentication
- 📊 Admin Panel for Managing Flights & Users
- 🧾 Flight Booking History

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite3
- **Machine Learning**: Scikit-learn (assumed)

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- pip
- virtualenv (optional but recommended)

### Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/aeropredict.git
cd aeropredict/myproject

# Create virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create superuser for admin access
python manage.py createsuperuser

# Run the server
python manage.py runserver
