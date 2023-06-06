# Otaku Engine

![table](https://wallpapercave.com/wp/wp5257135.jpg)

Otaku Engine is a content recommendation system for anime enthusiasts. It leverages machine learning techniques to provide personalized anime recommendations based on user interactions and ratings.

## Project Overview

The Otaku Engine project aims to recommend anime to users based on their past reviews and interactions with different anime titles. The system utilizes the Surprise library, a Python scikit for building and evaluating recommendation systems.

## Dataset

The project uses two main datasets:

- `anime.csv`: Contains information about anime titles, including unique IDs and titles.
- `rating.csv`: Stores user ratings for different anime titles.

## Getting Started

To run the Otaku Engine project, follow these steps:

1. Clone the repository:

```
git clone https://github.com/kaifshaikhhhh/otaku-engine.git
cd otaku-engine
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```


3. Download the dataset files (`anime.csv` and `rating.csv`) and place them in the project directory.

4. Open the notebook `otaku_engine.ipynb`


5. Enter the user ID when prompted to receive personalized anime recommendations.

## Results and Evaluation

The project utilizes the Surprise library's SVD algorithm to train the recommendation model. The model is evaluated using cross-validation, measuring the Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) metrics.

The performance of the model can be observed in the console output during the cross-validation process.

## Example Output

Below is an example output of the Otaku Engine, recommending anime for a specific user:

### Example User ID: 5

Prediction Results:

| anime_id | pred_score | title                                          |
|----------|------------|------------------------------------------------|
| 11757    | 7.934198   | Sword Art Online                               |
| 2251     | 7.835651   | Baccano!                                       |
| 164      | 7.433971   | Mononoke Hime                                  |
| 5114     | 7.428781   | Fullmetal Alchemist: Brotherhood               |
| 11061    | 7.358139   | Hunter x Hunter (2011)                         |
| 339      | 7.344123   | Serial Experiments Lain                         |
| 11981    | 7.268309   | Mahou Shoujo Madoka★Magica Movie 3: Hangyaku n...|
| 820      | 7.239986   | Ginga Eiyuu Densetsu                           |
| 777      | 7.224165   | Hellsing Ultimate                              |
| 7785     | 7.174965   | Yojouhan Shinwa Taikei                         |



## Future Enhancements

The Otaku Engine project can be further improved with the following enhancements:

- Incorporating additional user features, such as demographics or genre preferences, for more personalized recommendations.
- Implementing a user interface to provide a user-friendly experience.
- Utilizing deep learning techniques for more advanced recommendation models.

## Contributing

Contributions to the Otaku Engine project are welcome! If you have any ideas, bug fixes, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
