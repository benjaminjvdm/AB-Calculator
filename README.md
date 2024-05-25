# A/B Test Calculator by Moon Benjee (문벤지)

## Description

This Streamlit web application is designed for data analysts and marketers to evaluate the results of A/B tests. It provides essential statistical calculations and insights to help you understand whether your experiments have produced significant results.

## Features

- **Input Flexibility:**  Input either raw data (visitors and conversions) or directly enter conversion rates for both groups (A and B).
- **Statistical Rigor:** Performs a chi-squared test to determine statistical significance.
- **Zero-Conversion Handling:** Provides informative warnings if a group has zero conversions.
- **P-Value and Interpretation:** Clearly displays the p-value and interprets the results, indicating whether a statistically significant difference exists between the groups.
- **Effect Size (Lift):** Calculates and displays the lift, the relative improvement in the conversion rate of group B over group A.
- **Confidence Intervals:** Calculates and displays 95% confidence intervals for both groups' conversion rates.
- **Power Analysis:** If results aren't significant, estimates the additional conversions needed in group B to achieve significance at 80% power.
- **Visualization:** Presents a bar chart to visualize the conversion rates and their confidence intervals.
- **User-friendly Interface:**  Intuitive layout with tooltips for easy understanding of each metric.
- **Additional Metrics:**  Displays lift and confidence intervals in a separate tab. 

## Installation

1. Clone this repository: 
   ```bash
   git clone [https://github.com/benjaminjvdm/AB-Calculator.git](https://github.com/benjaminjvdm/AB-Calculator.git)
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the app:
   ```bash
   streamlit run ABC.py
   ```

2. The app will open in your web browser.
3. Enter your A/B test data in either raw or conversion rate format.
4. View the results and interpretations on the "Main Results" tab.
5. Explore additional metrics like lift and confidence intervals on the "Additional Metrics" tab.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.


## Contact

Moon Benjee (문벤지) - feel free to contact me on [LinkedIn](https://www.linkedin.com/in/benjaminjvdm/)
```

**Key Improvements:**

-   **Clear Description:** Explains the purpose of the app and its target audience.
-   **Detailed Features:** Lists out the app's capabilities.
-   **Clear Instructions:** Provides step-by-step installation and usage instructions.
-   **Encourages Contributions:** Invites collaboration from other developers.
-   **Contact Information:** Includes your name and a way to get in touch.

Let me know if you'd like any modifications or additions to the README.
