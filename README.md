# Personalized Curriculum Recommendation System
  
This project is a full-stack web application designed to provide personalized curriculum recommendations based on a student's learning style, domain of interest, and level of knowledge. The system aims to enhance the learning experience by guiding users toward courses that suit their individual preferences using a structured rule-based approach.

## 🧑‍💻 Authors

**Mahitha S**, **Srinisha S**, **Gayathri J** , **Rithika S**
  
## 📌 Features

- User registration and secure JWT-based login system  
- Questionnaire-driven recommendation system based on:
  - Learning styles (Visual, Auditory, Kinesthetic, General)
  - Domain interests
  - Education level and prior knowledge
- Dynamic course recommendations using a rule-based logic
- Interactive and responsive dashboard for enrolled courses
- Real-time progress tracking and visualization of learning preferences
- Course search and filtering functionality
- Admin-friendly data storage using MongoDB

## 🛠️ Tech Stack

- **Frontend**: React.js  
- **Backend**: Flask (Python)  
- **Database**: MongoDB  
- **Authentication**: JSON Web Tokens (JWT)  
- **Styling**: Bootstrap, CSS3  

## 📂 Dataset

- Source: [Kaggle – Coursera Courses Dataset](https://www.kaggle.com/)  
- Enhanced to include:  
  - Learning styles classification (VAKG model)  
  - Cleaned and preprocessed data with 8,000+ course entries  

## 🧠 System Flow

1. User registers or logs in
2. Completes a four-step questionnaire
3. System recommends courses based on matched logic
4. User enrolls, tracks progress, and receives updated suggestions

## 📎 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/personalized-curriculum-recommendation.git
   cd personalized-curriculum-recommendation
   ```

2. Install backend dependencies  
   ```bash
   cd backend
   pip install -r requirements.txt
   python app.py
   ```

3. Install frontend dependencies  
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. Make sure MongoDB is running locally or connected via cloud
