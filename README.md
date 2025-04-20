📄 Resume Job Role Predictor

Overview

This project is a machine learning-based web application that predicts the most suitable job role for a candidate based on their resume. It utilizes TF-IDF vectorization and a pre-trained classification model to analyze resume content and classify it into relevant job categories. The application is built using Python, Streamlit, scikit-learn, and joblib for model handling. The user-friendly interface allows candidates or recruiters to upload resumes and receive instant predictions.

🚀 Features


Upload Resume (PDF/DOCX) and extract text automatically.
Machine Learning-based Job Prediction using a trained model.
Interactive UI powered by Streamlit.
Custom Background Styling with an image.


🛠 Tech Stack


Languages & Tools: Python, Streamlit, Pandas, Matplotlib, Seaborn, joblib
Machine Learning Model: NLP
Background Customization: Styled using CSS and inline HTML in Streamlit


🎯 How to Use


Upload a resume (PDF or DOCX).
The app extracts the text and displays it.
Click on Predict, and the app will determine the best-fit job role.


🚀 How to Run the Project Locally

Clone this repository:

git clone <repository-url>

cd patient_drug_prediction

Install required dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

To use the app click here https://resumescreening-ganugapenta-anil.streamlit.app/



💾 Model Training & Updating



To update the model with new data:

Add new patient data to the UpdatedResumeDataSet.csv file.

Run app.py to train the NLP Model again and save the updated version.



📜 Acknowledgments


Streamlit for the interactive UI.

Pandas & Seaborn for data manipulation and visualization.

Scikit-Learn for Machine Learning implementation.

Final Output
link: https://resumescreening-ganugapenta-anil.streamlit.app/

If you find this project useful, feel free to ⭐ the repository and contribute!
