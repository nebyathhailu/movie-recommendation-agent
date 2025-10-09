# Movie Recommendation Agent

This project is a Movie Recommendation Agent designed to help users discover movies tailored to their interests. The main implementation is provided as a Jupyter Notebook, optimized for interactive use in Google Colab.

## Features

- **Personalized Movie Recommendations:** Suggests movies based on user preferences and historical data.
- **Colab Integration:** Easily run the notebook in Google Colab—no local setup required.
- **Interactive Notebooks:** Modify, run, and visualize recommendation workflows directly in the browser.
- **Modular Design:** Adapt and extend the recommendation logic for various datasets and use cases.

## Getting Started

### Run in Google Colab

You can run the notebook directly in Google Colab by clicking the badge below:

<a href="https://colab.research.google.com/github/nebyathhailu/movie-recommendation-agent/blob/main/Movie_Recommendation.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Prerequisites (for Colab)

- A Google account
- (Optional) Your own copy of the IMDB Top 1000 dataset, uploaded to your Google Drive

### Steps

1. **Open the Notebook in Colab:**  
   Click the "Open in Colab" badge above, or [open the notebook directly](https://colab.research.google.com/github/nebyathhailu/movie-recommendation-agent/blob/main/Movie_Recommendation.ipynb).

2. **Install Required Libraries:**  
   The notebook will automatically install all necessary Python libraries:
   ```python
   !pip install pandas transformers torch langchain langchain-community nltk chromadb tqdm
   ```

3. **Mount Google Drive:**  
   The notebook will prompt you to mount your Google Drive, so it can access the dataset:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

4. **Upload or Place Your Dataset:**  
   Place your `imdb_top_1000.csv` in your Google Drive (e.g., `/MyDrive/imdb_top_1000.csv`). The notebook expects this default location, but you can modify the path if needed.

5. **Run All Cells:**  
   Use `Runtime > Run all` in Colab to execute the full workflow and interact with the recommendation system.

## Repository Structure

- `Movie_Recommendation.ipynb`: Main Colab notebook containing the code, instructions, and explanations.
- `README.md`: Project overview and instructions.

## Notes

- The notebook uses modern NLP tools and vector databases (LangChain, ChromaDB, HuggingFace Transformers).
- You can adapt the notebook to run locally in Jupyter, but Colab is the recommended and most convenient option.

## Contributing

Contributions are welcome! Please fork the repository, create a new branch for your feature or bugfix, and submit a pull request.

## Contact

- Repository: [nebyathhailu/movie-recommendation-agent](https://github.com/nebyathhailu/movie-recommendation-agent)
- Owner: [nebyathhailu](https://github.com/nebyathhailu)

---

*This README is a template based on available information. Please update details as you develop your project further!*
