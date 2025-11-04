# 🥤 Streamlit + Snowflake Smoothie App

An interactive application built with **Streamlit** and **Snowflake** that lets you design your own fruit smoothie in a fun, dynamic way.  
It connects directly to a Snowflake database to fetch available fruit options, display nutritional information, and record your smoothie orders in real time.

---

## 🍓 Description

The **Smoothie App** is a practical example of how to integrate Streamlit with Snowflake to build data-driven web apps in minutes.  
Its purpose is to demonstrate how easy it is to connect both platforms while providing a clean and engaging user experience.

**Main features:**
- Modern and intuitive web interface powered by Streamlit  
- Direct connection to Snowflake for reading and inserting data  
- Custom fruit selection (up to five ingredients)  
- Automatic nutrition lookup through an external API  
- One-click order submission to the database  

---

## ⚙️ Installation

1. **Clone this repository:**

   ```bash
   git clone https://github.com/user/smoothie-app.git
   cd smoothie-app
2. **Create and activate a virtual environment::**


python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3. **Install dependencies:**

pip install -r requirements.txt
4. **Set up your Snowflake connection:**
Create a file named .streamlit/secrets.toml and include your Snowflake credentials:

user

password

account

database

schema

warehouse

🚀 Usage
Run the application:

streamlit run app.py
Open your browser:
Go to http://localhost:8501 and start creating your smoothie:

Enter your name

Choose up to five fruits

View the nutritional information

Submit your order to Snowflake with a single click

✨ A tasty example of how to combine data, visualization, and interactivity in one app.
