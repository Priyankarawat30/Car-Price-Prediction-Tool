# Old Car Price Prediction Tool

## Overview
The **Old Car Price Prediction Tool** is a machine learning-based web application that predicts the price of old cars based on various input features. This project leverages Python's data analytics libraries, machine learning algorithms, and a user-friendly web interface built with **Streamlit**.

## Project Author
**Priyanka Rawat**

## Technologies Used
- **Python**
- **Jupyter Notebook** (for model development and data analysis)
- **Pandas & NumPy** (for data manipulation)
- **Scikit-learn** (for machine learning model development)
- **Streamlit** (for creating the web interface)
- **Pickle** (for model serialization)
- **CSV Dataset** (CarDetails.csv)

## Dataset
The dataset used in this project is **CarDetails.csv**, which contains information about:
- Car name
- Year of manufacture
- Selling price
- Present price
- Fuel type
- Seller type
- Transmission
- Owner type
- Kilometers driven

## How It Works
1. Data is preprocessed using **Pandas**.
2. Machine learning model is trained using **Random Forest Regressor**.
3. The model is serialized using **Pickle**.
4. The Streamlit web app provides an interactive interface to enter car details.
5. The app predicts the approximate selling price of the car.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Priyankarawat30/Car-Price-Prediction-Tool.git
```

2. Install required libraries:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run app.py
```

## Future Improvements
- Improve model accuracy
- Add more features like car brand and condition
- Deploy on cloud platforms like Heroku or AWS

## Contributing
Feel free to raise issues or contribute to this project by making pull requests.

## License
This project is licensed under the **MIT License**.

---
### Contact
- GitHub: [Priyankarawat30](https://github.com/Priyankarawat30)
