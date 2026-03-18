🎓 Student Exam Performance Predictor
A Machine Learning web application that predicts a student's Math score based on various factors like gender, ethnicity, parental education, lunch type, and test preparation.
________________________________________
🚀 Features
•	📊 Predicts student Math score
•	🧠 Uses trained Machine Learning model
•	🌐 Interactive web interface using Flask
•	⚡ Fast and simple predictions
•	🎨 Clean and user-friendly UI
________________________________________
🛠️ Tech Stack
•	Frontend: HTML, CSS
•	Backend: Flask (Python)
•	Machine Learning: Scikit-learn
•	Data Processing: Pandas, NumPy
•	Model Serialization: Pickle (.pkl)
________________________________________
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/rushikeshmadas04/first_Ml_Project.git
cd student-performance-predictor
2️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows
# OR
source venv/bin/activate   # Mac/Linux
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the application
python app.py
________________________________________
🌐 Usage
1.	Open browser:
http://127.0.0.1:5000
2.	Go to prediction page
3.	Fill student details
4.	Click Predict
5.	Get predicted Math score 🎯
________________________________________
📊 Input Features
•	Gender
•	Race/Ethnicity
•	Parental Level of Education
•	Lunch Type
•	Test Preparation Course
•	Reading Score
•	Writing Score
________________________________________
🧠 How It Works
1.	User inputs data through web form
2.	Data is converted into DataFrame
3.	Preprocessing pipeline transforms input
4.	Trained model predicts Math score
5.	Result is displayed on UI
________________________________________
📦 Model & Pipeline
•	Preprocessing handled using preprocessor.pkl
•	Model loaded from model.pkl
•	Predictions done via custom pipeline (PredictPipeline)
________________________________________
📚 Acknowledgement
This project is inspired by and built while following the Machine Learning playlist:
👉 https://www.youtube.com/playlist?list=PLZoTAELRMXVPS-dOaVbAux22vzqdgoGhG
Additional improvements such as UI enhancements, bug fixes, and project structuring were implemented independently.
________________________________________
👨‍💻 Author
Rushikesh Madas
•	💼 Aspiring AI Engineer
•	🚀 Passionate about Machine Learning & Web Development
________________________________________

