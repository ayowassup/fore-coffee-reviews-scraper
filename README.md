# Scraping "Fore Coffee" App Reviews on Google Play Store

This mini python project aims to scrape user reviews of the `Fore Coffee` application on Google Play Store. The project uses web scraping techniques to fetch review data, filter reviews by year, and save the results in CSV format.

## **About Fore Coffee:**
**Fore Coffee** is a popular coffee chain in Indonesia known for its innovative approach to coffee brewing and customer experience. The [Fore Coffee App](https://play.google.com/store/apps/details?id=coffee.fore2.fore) allows customers to order coffee for delivery or pickup, explore menu options, and take advantage of various promotions.

In this project, the Fore Coffee app ID (`coffee.fore2.fore`) is used to fetch reviews from the Google Play Store.

## **Project Steps:**

1. **Library Installation:** Installing the `google-play-scraper` library and importing all necessary libraries.
2. **Review Extraction:** Fetching all reviews for the "Fore Coffee" app from the Google Play Store.
3. **Date Filtering:** Filtering reviews to include only those from 2023.
4. **Data Transformation:** Converting the filtered reviews into a DataFrame and sorting them from oldest to newest.
5. **Export to CSV:** Saving the final results in CSV format, specifically to `/generated_data` folder.

## **Used Libraries:**

1.   `google-play-scraper`: For fetching review data from the Google Play Store.
2.   `datetime`: For manipulating date and time.
3.   `pandas`: For data manipulation.
4.   `numpy`: For numerical computing support.

## **Project Output:**
The final output of this project is a CSV file containing the reviews of the "Fore Coffee" app from 2023. The CSV file includes columns such as name, date created, reviews, and rating. The file is saved in the `/generated_data` folder.

## **How to Use:**

1. Clone this repository.
2. Ensure all required libraries are installed.
3. Open and run the Jupyter notebook (`Fore Coffee Google Play Reviews.ipynb`) in your preferred environment.
4. Execute the notebook cells to perform each step of the project.

Since GitHub does not render the output of Jupyter Notebooks directly, you can use external tools to view and interact with the notebook below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ayowassup/fore-coffee-reviews-scraper/blob/main/Fore_Coffee_Google_Play_Reviews.ipynb) [![View on nbviewer](https://img.shields.io/badge/View%20on-nbviewer-brightgreen)](https://nbviewer.jupyter.org/github/ayowassup/fore-coffee-reviews-scraper/blob/main/Fore_Coffee_Google_Play_Reviews.ipynb)

## **Disclaimer:**

This code was originally used for my undergraduate thesis but with a different mobile application. I'm sharing this code, including the addition of the review filtering feature by year. You may use this code for other applications as you see fit. For further usage, please refer to the documentation of the Google Play Scraper library on the following page: [https://pypi.org/project/google-play-scraper/](https://pypi.org/project/google-play-scraper/).

