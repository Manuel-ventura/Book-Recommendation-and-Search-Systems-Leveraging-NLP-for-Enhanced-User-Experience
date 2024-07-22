# Enhancing Book Discovery: Building a Data-Driven Recommendation System with Goodreads Data

This project aims to enhance the book discovery process by leveraging a sophisticated recommendation system based on Goodreads data. The system analyzes user interactions and preferences to suggest books that align closely with individual tastes.

## Project Description

This Jupyter notebook-based recommendation system uses data from Goodreads to identify and suggest books based on similarity in user behavior and preferences. It integrates various datasets to compile a list of recommended books, ranks them based on frequency and ratings, and presents the results with enhanced interactivity.

## Datasets Used

The recommendation system utilizes the following datasets from Goodreads, which can be accessed [here](https://mengtingwan.github.io/data/goodreads.html#datasets):

- `goodreads_interactions.csv`: This dataset includes interactions between users and books, such as ratings and reading status.
- `book_id_map.csv`: A mapping file that links the internal book IDs used in other datasets to the book IDs used by Goodreads.
- `goodreads_books.json.gz`: Contains comprehensive metadata about books listed on Goodreads.

## Repository Structure

- `notebook.ipynb`: Contains all the code and documentation for the recommendation system.
- `data/`: This folder should contain all the datasets used by the notebook. Due to size and copyright, the datasets are not included in the repository but can be downloaded from the provided link.

## Setup and Installation

To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Manuel-ventura/Enhancing-Book-Discovery--Building-a-Data-Driven-Recommendation-System-with-Goodreads-Data.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Enhancing-Book-Discovery--Building-a-Data-Driven-Recommendation-System-with-Goodreads-Data
   ```
3. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
4. Download the necessary datasets from [Goodreads Datasets](https://mengtingwan.github.io/data/goodreads.html#datasets) and place them in the `data/` directory.
5. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## Contributing

Contributions are welcome! Please read the contribution guidelines in `CONTRIBUTING.md` before submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
