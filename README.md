# Viterbi Algorithm Visualizer for Part-of-Speech Tagging

Welcome to the **Viterbi Algorithm Visualizer**, an interactive tool designed to help users understand and explore how the Viterbi algorithm works for part-of-speech (POS) tagging. This application supports three languages: **English**, **Swedish**, and **Korean**. It builds upon the foundation of the repository [PartOfSpeech](https://github.com/emma-horton/PartsOfSpeech).

---

## 🎯 **Features**

- **Interactive Visualization**: Step through the Viterbi algorithm to see how it determines the most probable sequence of tags for a given sentence.
- **Multilingual Support**: Choose between English, Swedish, or Korean datasets to explore the algorithm's effectiveness across different languages.
- **Test Set Accuracy**:
  - **English**: 91.3%
  - **Swedish**: 90.2%
  - **Korean**: 79.2%
- **Educational Focus**: Designed for linguists, students, and developers who want to learn more about sequence modeling and HMMs (Hidden Markov Models).

---

## 📂 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/emma-horton/viterbi-visualizer.git
cd viterbi-visualizer
```

### 2. Install Dependencies
This project uses Python. Install the required libraries with:
```bash
pip install -r requirements.txt
```

### 3. Run the Application
Launch the application locally:
```bash
python app.py
```

Navigate to `http://localhost:5000` in your web browser to start exploring!

---

## 🛠️ How It Works

The application implements the **Viterbi algorithm**, a dynamic programming technique that computes the most probable sequence of POS tags for a given sentence. Key components include:

- **Transition and Emission Probabilities**: Derived from annotated training datasets for English, Swedish, and Korean.
- **Dynamic Programming Table**: Displays intermediate steps of the algorithm.
- **Final Output**: Shows the sentence with its predicted POS tags.

---

## 📚 Data Sources

This project builds upon the repository [PartOfSpeech](https://github.com/emma-horton/PartsOfSpeech), which provided pretrained models and training datasets for POS tagging.

The datasets used for evaluation are sourced from publicly available corpora for English, Swedish, and Korean. Further preprocessing and training have been done to achieve the following test set accuracies:

- **English**: 91.3%
- **Swedish**: 90.2%
- **Korean**: 79.2%

---

## 🛠️ Customization

You can extend or adapt the visualizer by:

- Adding new languages or datasets.
- Modifying the visualization logic for enhanced clarity.
- Tuning the model to improve accuracies for low-performing languages like Korean.

---

## 🌟 Contributions

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Special thanks to [original repository author](#) for their foundational work, as well as the creators of the corpora used for POS tagging.


<figure>
    <img src="images/POSinterface" alt="POSInterface" width="1000">
<!--     <figcaption>Part of Speech Tagging Interface</figcaption> -->
</figure>
