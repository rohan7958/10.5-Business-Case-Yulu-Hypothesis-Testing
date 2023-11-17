# 10.5-Business-Case-Yulu-Hypothesis-Testing

# Yulu - Hypothesis Testing 🛴📊

Welcome to the Yulu Hypothesis Testing project! 🇮🇳

Yulu is India's leading micro-mobility service provider, committed to eliminating traffic congestion by offering unique shared electric cycles for daily commutes. 🚴‍♂️🛴

## About Yulu 🚀

Yulu operates in key locations, including metro stations, bus stands, office spaces, residential areas, and corporate offices, to make commuting smooth, affordable, and sustainable. 🏙️🏢

Recently, Yulu has faced challenges with its revenues, and they've partnered with a consulting company to understand the factors influencing the demand for shared electric cycles in the Indian market. This project aims to uncover these insights. 📉📈

## How You Can Help 🤝

Yulu is eager to find out:

1. Which variables significantly predict the demand for shared electric cycles in the Indian market?
2. How well these variables describe the electric cycle demand?

## Dataset 📊

### Column Profiling:

- `datetime`: Date and time
- `season`: Season (1: spring, 2: summer, 3: fall, 4: winter)
- `holiday`: Whether it's a holiday or not
- `workingday`: If it's a working day (1) or not (0)
- `weather`:
  1. Clear, Few clouds, partly cloudy
  2. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  3. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  4. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- `temp`: Temperature in Celsius
- `atemp`: Feeling temperature in Celsius
- `humidity`: Humidity
- `windspeed`: Wind speed
- `casual`: Count of casual users
- `registered`: Count of registered users
- `count`: Count of total rental bikes, including casual and registered users

## Concepts Used 📚

- Bi-Variate Analysis
- 2-sample t-test: Testing for differences across populations
- ANOVA
- Chi-square

## How to Begin 🏁

1. Import the dataset and perform exploratory data analysis to understand its structure and characteristics.
2. Establish relationships between the dependent variable, "Count," and independent variables like Workingday, Weather, Season, etc.
3. Select an appropriate test to determine:
   - If Working Day affects the number of electric cycles rented.
   - Whether the number of cycles rented differs in different seasons.
   - Whether the number of cycles rented differs under different weather conditions.
   - If weather is dependent on the season.

4. Set up Null Hypothesis (H0).
5. State the alternate hypothesis (H1).
6. Check assumptions of the test (Normality, Equal Variance). Use tools like histograms, Q-Q plots, or statistical methods like Levene’s test and Shapiro-Wilk test (optional).
7. Continue with the analysis even if some assumptions fail. Double-check using visual analysis and report wherever necessary.
8. Set a significance level (alpha).
9. Calculate test statistics.
10. Make a decision to accept or reject the null hypothesis.
11. Draw meaningful inferences from the analysis.

Let's work together to help Yulu make data-driven decisions and improve their micro-mobility services! 🚴‍♀️🔍💡

Feel free to contribute, collaborate, and create insights for Yulu's success! 🌟📈

Happy analyzing! 📊📚🛴👩‍💼👨‍💼
