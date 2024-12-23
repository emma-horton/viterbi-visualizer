![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-Data%20Visualization-red?logo=d3.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Python%20Framework-lightgrey?logo=flask&logoColor=white)
# **Viterbi Algorithm Visualizer for Part-of-Speech Tagging** 🌍✨  

Welcome to the **Viterbi Algorithm Visualizer** – your interactive guide to understanding the Viterbi algorithm for part-of-speech (POS) tagging! This tool is perfect for linguists, students, and developers who want to delve into sequence modeling and Hidden Markov Models (HMMs).  

🌐 **[Try it out now!](https://partsofspeech-8f2cb5c28301.herokuapp.com)**  
*Note: Desktop-only access.*

---

## 🖥️ **What is the Viterbi Algorithm Visualizer?**
The **Viterbi Algorithm Visualizer** brings learning to life by letting you step through how the Viterbi algorithm works for POS tagging. With support for **English**, **Swedish**, and **Korean**, this tool demonstrates the algorithm’s effectiveness across diverse linguistic structures.

---

## ✨ **Features**
- **Interactive Visualization**: Observe the Viterbi algorithm in action as it computes the most probable sequence of POS tags for any given sentence.  
- **Multilingual Support**: Switch between English, Swedish, or Korean datasets to explore how linguistic differences impact the algorithm.  
- **Accuracy Metrics**:
  - **English**: 91.3%  
  - **Swedish**: 90.2%  
  - **Korean**: 79.2%  
- **Educational Focus**: Ideal for anyone curious about HMMs and sequence tagging.

---

## 🚀 **Get Started in 3 Steps**
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/emma-horton/viterbi-visualizer.git
cd viterbi-visualizer
```

### 2️⃣ Install Dependencies
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 3️⃣ Launch the Application
Run the application locally:
```bash
python app.py
```
Open your browser and navigate to `http://localhost:5001` to begin exploring!

---

## 🛠️ **How It Works**
The visualizer employs the **Viterbi algorithm**, a dynamic programming technique that predicts the most probable POS tag sequence for a sentence. Key components include:

- **Transition & Emission Probabilities**: Generated from annotated datasets in English, Swedish, and Korean.  
- **Final Output**: Presents the sentence annotated with predicted POS tags.

---

## 📚 **Data Sources**
This project extends the foundational work in [PartOfSpeech](https://github.com/emma-horton/PartsOfSpeech), using its pretrained models and datasets. The corpora used for POS tagging were preprocessed and trained to achieve high accuracy rates:

- **English**: 91.3%  
- **Swedish**: 90.2%  
- **Korean**: 79.2%

---

## 🛠️ **Future Improvements**
The following enhancements are planned for future iterations of the visualizer:  

- **Dynamic Programming Table**: Display step-by-step calculations of probabilities to improve user understanding.  
- **Enhanced User Interface**: Introduce more intuitive controls and visual cues.  
- **Expanded Language Support**: Add new languages with unique linguistic structures.  

---

## 🌟 **Contribute and Collaborate**
We’d love your help in enhancing this project! Here’s how to contribute:  

1. **Fork the repository.**  
2. **Create a new branch:**  
   ```bash
   git checkout -b feature-name
   ```
3. **Make your changes and commit them:**  
   ```bash
   git commit -m "Add a new feature"
   ```
4. **Push your branch:**  
   ```bash
   git push origin feature-name
   ```
5. **Open a pull request!**  

