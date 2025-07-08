# Real Estate Price Analysis – Linear Regression Visualizer

This interactive web app allows you to explore linear regression and correlation in real estate data, such as price vs. square footage, bedrooms, distance to city, property age, and year built. You can add your own data points, load example datasets, and visualize the best-fit regression line, residuals, and confidence intervals.

## Features

- **Interactive Plotting:** Click to add data points and see how the regression line updates.
- **Dataset Selection:** Choose from several real estate datasets with different correlation strengths.
- **Manual Regression:** Adjust the slope and intercept sliders to see how the regression line changes.
- **Prediction Tool:** Enter an X value to predict the corresponding price using the regression model.
- **Prediction History:** View the last 5 predictions in a table.
- **Outlier Detection:** Outliers are highlighted in red.
- **Residuals & Confidence Interval:** Toggle display of residuals and confidence intervals.
- **Responsive UI:** Works well on both desktop and mobile devices.

## How to Use

1. **Open `linear-regression.html` in your browser.**
2. **Add Points:** Click on the plot area to add data points.
3. **Load Dataset:** Use the dropdown to load a sample dataset.
4. **Adjust Regression:** Use the sliders to manually adjust the regression line, or click "Reset to Best-Fit Line" to revert.
5. **Predict:** Enter a value for X and click "Predict" to see the predicted price and update the prediction history.
6. **Toggle Features:** Use the buttons to show/hide residuals and confidence intervals, or clear all points.

## Datasets

- **Strong Positive:** Price vs. Square Footage
- **Weak Positive:** Price vs. Bedrooms
- **Strong Negative:** Price vs. Distance to City
- **Weak Negative:** Price vs. Property Age
- **No Correlation:** Price vs. Year Built

## Technical Details

- **Tech Stack:** HTML, CSS, JavaScript, [p5.js](https://p5js.org/)
- **No build step required.**
- **All logic is contained in `linear-regression.html`.**
