# 🌱 Carbon Estimator AI 🌍

A data-driven web app that estimates an individual's carbon footprint based on real-world lifestyle habits — with feedback, insights, and suggestions for a more sustainable future. Built with love using Python, machine learning, and Gradio 💡

## 🚀 Why This Project?

Climate change is real — but most of us don’t know how our daily actions contribute to it.  
**Carbon Estimator AI** helps users visualize and understand their personal carbon emissions while offering actionable suggestions to reduce them.

## ✨ Key Features

- 🔢 Predicts your carbon footprint using real lifestyle input
- 📊 Visualizes your emission breakdown by category (e.g., food, transport, utilities)
- 🌍 Compares your emission level with global averages
- 💬 Gives personalized feedback and suggestions to reduce emissions
- 🎨 Interactive, responsive UI built with Gradio
- 🔒 Entire pipeline (data cleaning → model → predictions) wrapped in a robust ML pipeline

## 🧠 How It Works

1. **Dataset**: Used the [Carbon Emission.csv](https://www.kaggle.com/datasets/onesource/individual-carbon-footprints) from Kaggle  
2. **Preprocessing**: Cleaned missing data, handled categorical variables, encoded necessary features  
3. **EDA**: Identified key influencers of emissions through feature correlation and visualization  
4. **Modeling**: Trained a `Random Forest Regressor` to estimate carbon emissions  
5. **Deployment**: Built a Gradio UI and deployed the app on Hugging Face Spaces

## 📊 Model Performance

- **R² Score**: 91%

## 🖼️ Visual Features

- 📈 *Daily Emission vs Global Average* chart  
- 🌍 *Carbon Footprint Breakdown* graph  
- 🧠 Personalized emission **feedback**, **impact level**, and **reduction tips**

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Gradio for the UI
- Hugging Face Spaces for deployment
- Jupyter Notebook for development & visualization

## 🔗 Demo & Code

- 🚀 [Live App on Hugging Face](https://huggingface.co/spaces/Devalekka/carbon_estimator)  
- 📁 [Full Code on GitHub](https://devalekka.github.io/carbon-estimator/)


