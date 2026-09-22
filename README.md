# PowerPulse AI

A smart, user-friendly electricity bill prediction app built with Python and Gradio. It estimates your monthly electricity cost based on AC, fan, and other appliance usage, helping users make more informed energy decisions.

## ✨ Project Highlights

- Predicts electricity bills based on real usage inputs
- Simple and clean Gradio interface
- Fast, lightweight deployment for local or cloud hosting
- Ideal for demos, prototypes, and ML app showcases

## 🏠 About the Project

This project uses a trained machine learning model to forecast electricity bills from input values such as:

- AC units
- Fan units
- Other appliance units

The app loads a pre-trained model and provides a prediction in a clear, human-friendly format.

## 📁 Project Structure

```bash
.
├── app_gradio.py
├── requirements.txt
├── Electric_Bill_AC_Fan_Other_model.pkl
├── README.md
```

> Make sure the trained model file is present in the root directory before running the app.

## 🚀 Installation

1. Clone the repository:

```bash
git clone <your-repository-url>
cd Electricity-Bill-Prediction-Model-Depolyment-in-Gradio
```

2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the App

Start the Gradio app using:

```bash
python app_gradio.py
```

Then open the local URL shown in the terminal, typically:

```bash
http://localhost:7860
```

## 🧠 How It Works

The app takes three numeric inputs:

- AC Units
- Fan Units
- Other Units

It transforms the input values using polynomial feature preprocessing and passes them into the trained model. The final result is displayed as a predicted electricity bill amount.

## 📦 Dependencies

The project uses:

- Python
- Gradio
- Pandas
- scikit-learn
- Joblib
- NumPy

These are listed in [requirements.txt](requirements.txt).

## 🛠️ Example Usage

- AC: 3
- Fan: 4
- Other: 5

The model predicts an estimated bill based on these combined usage values.

## 📌 Notes

- This is a deployment-ready prototype for demonstration purposes.
- The performance depends on the quality and training data used for the machine learning model.
- You can extend this app by adding more fields, improved model tuning, or user-friendly charts.

## 👨‍💻 License

This project is for educational and demonstration use.

## 🙌 Acknowledgements

Built with Python, Gradio, and machine learning for intelligent energy prediction.
