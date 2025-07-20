# 🧠 AI-Powered Gender Prediction & Data Cleaning Project

This project is my first step into the world of **Artificial Intelligence (AI)** and **Data Science**. I used Python, Groq's LLaMA 3.3 model, and several data science tools to clean a dataset and predict missing gender values based on names using a language model.

---

## 🚀 What I Built

* 🧼 **Handled Missing Values** in a real-world customer dataset

  * Imputed missing ages with the mean value
  * Predicted missing genders using a Large Language Model (LLM)
* 🤖 **Integrated Groq API** with LLaMA 3.3-70B to predict gender based on first and last names
* 📊 **Visualized Age Distribution** using Seaborn
* 🗂️ Cleaned and exported the processed dataset to CSV

---

## 📁 Project Structure

```
project/
│
├── data/
│   ├── raw/
│   │   └── CEHHbInToW.csv              # Original dataset
│   └── processed/
│       └── CEHHbInToW_handled_missing_values.csv
│
├── 0_handle_missing_values.ipynb              # Jupyter notebook with full workflow
├── requirements.txt                    # List of dependencies
└── README.md                           # This file
```

---

## 📦 Technologies Used

* 🐍 Python
* 📘 Pandas, NumPy, Seaborn
* 🤖 [Groq](https://groq.com/) + LLaMA 3.3 model
* 🧬 Pydantic & Enum (for structure and validation)
* 📁 dotenv (for managing API keys)
* 📓 Jupyter Notebook

---

## 🧪 Example Output

```plaintext
jane Senevirathne : Female
shyaminda senevirathna : Male
...
```

---

## 📌 How to Run

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/llm-assisted-data-imputation.git
   cd llm-assisted-data-imputation
   ```

2. **Install dependencies:**

   ```bash
   %pip install -r requirements.txt
   ```

3. **Set your Groq API key:**
   Create a `.env` file and add:

   ```text
   GROQ_API_KEY=your_key_here
   ```

4. **Run the notebook:**
   Open `0_handle_missing_values.ipynb` in Jupyter and run all cells.

---

## 📌 Note

* This is a **learning project**, not a production-grade gender prediction model.
* The gender prediction uses an LLM and may not be 100% accurate — it's based on name patterns and stereotypes.

---

## 🧑‍💻 Author

**Shyaminda Senevirathna**
📧 [LinkedIn](https://linkedin.com/in/shyaminda) (update with your link)

---

## ⭐️ Star This Repo

If you liked this project or found it helpful, consider giving it a ⭐️ to show support!

