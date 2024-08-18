# Wildfire Prediction Challenge

**Can you predict the burned area of wildfires in Zimbabwe?**

## Table of Contents
- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Project Structure](#project-structure)
- [Environment](#environment)
- [Accessing Data](#accessing-data)
- [Running the Code](#running-the-code)
- [Project Results](#project-results)
- [Team Members](#team-members)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Project Overview

This project is a submission for the Wildfire Prediction Challenge, where the goal is to create a machine-learning model capable of predicting the burned area in different locations across Zimbabwe from 2014 to 2016. The challenge leverages historical data, including climate variables, land cover, population density, and more.

## Project Objectives

1. **Accurate Prediction**: Develop a robust machine learning model capable of predicting the burned area with high accuracy.
2. **Feature Selection**: Identify and select the most important features that significantly contribute to the prediction, optimizing model performance.
3. **Model Interpretability**: Ensure that the model is interpretable, allowing stakeholders to understand which factors most influence wildfire spread and intensity.
4. **Scalability**: Design the solution to be scalable and adaptable to different geographic regions with varying environmental conditions.
5. **Resource Optimization**: Provide insights that can help optimize resource allocation for wildfire management and emergency response.
6. **Collaborative Effort**: Leverage the diverse expertise within the team to explore various approaches, test multiple models, and continuously improve the solution.

## Project Structure

- `data/`: Contains the dataset files
- `notebooks/`: Contains the primary Jupyter notebook where the entire data preprocessing, feature engineering, model training, and evaluation were conducted
- `requirements.txt`: List of required Python libraries used in the project
- `Wildfire Prediction Challenge Documentation.pdf`: Detailed project documentation, including methodology and results.

## Environment

This project was developed and executed in Google Colab.

## Accessing Data

The data files should be placed in the `data/` directory within your local project structure.

## Running the Code

1. **Install Required Libraries:** Use the `requirements.txt` file to install the necessary libraries.
2. **Open the Notebook:** Open the `Wildfire_Prediction_Zindi_Challenge.ipynb` notebook in your Jupyter environment or Google Colab.
3. **Run the Notebook:** Execute the cells in the notebook to reproduce the analysis and predictions.

## Project Results

  - **Public Score**: 0.019308177—This score was obtained by submitting the predictions to the competition's public leaderboard, which used a subset of the test data.
  - **Private Score**: 0.01821023—This score was revealed after the competition ended and was based on the remaining unseen test data. It provided a final assessment of the model's performance.

## Team Members

- [Maxwell Mogambi]()
- [Ethel Uchindami]()
- [Yousif Shaheen]()
- [Shamso Osman]()

## Acknowledgments

We acknowledge the organizers of the Wildfire Prediction Challenge for providing the data and the platform to participate, [Zindi](https://zindi.africa/).

Special thanks to my team members for their contributions to this project.

## License

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
