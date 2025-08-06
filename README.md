
# 🌤️ Weather Condition Predictor

This is a simple Django web application that predicts weather conditions like sun, drizzle, rain, or snow based on the maximum temperature provided by the user. The prediction logic is based on patterns observed from the `seattle-weather.csv` dataset.

---

## ✅ How to Use

- Clone or download this repository  
- Run the Django server using `python manage.py runserver`  
- Go to `http://127.0.0.1:8000/` in your browser  
- Enter the **maximum temperature** (in °C)  
- Submit to see the predicted weather condition

---

## 🛠️ What It Does

- Accepts a single numeric input: `temp_max` (maximum temperature)  
- Uses simple if-else logic to determine the weather condition:
  - Above 30°C → **sun**
  - 20°C–30°C → **drizzle**
  - 10°C–20°C → **rain**
  - Below 10°C → **snow**
- Displays the predicted result on a separate result page

---

## 📌 Uses

- Educational demo of Django form handling and conditional logic  
- Great for beginners practicing basic data-driven web development  
- Can be expanded using machine learning or integrated with real-time weather APIs

---

## 🎯 Why I Made This

I created this project to understand how to:

- Handle form data in Django  
- Apply simple logic to user input  
- Dynamically render results on separate pages  

It also serves as a starting point for future projects involving data input and prediction.

---

## 🌐 Deployed Link

🔗 https://weather-prediction-l005.onrender.com

---

## 👩‍💻 About Me

Hi, I’m **Annam Purnima** — a B.Tech student at **Vignan’s Nirula Institute of Technology and Science for Women**. I love creating intuitive web apps that connect real-world data with simple logic.

- **GitHub:** [https://github.com/Purnimaannam](https://github.com/Purnimaannam)  
- **LinkedIn:** [http://www.linkedin.com/in/purnima20](http://www.linkedin.com/in/purnima20)

---

If you found this project useful, please ⭐ the repo and share it! 😊

---
