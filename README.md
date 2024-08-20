# NYC Schools SAT Performance Analysis README

## Overview
This project provides a Python script to analyze the SAT performance of schools in New York City. The analysis focuses on determining the best schools based on SAT math scores, the top 10 performing schools based on total SAT scores, and the borough with the highest standard deviation for total SAT scores.

## Dependencies
- Python 3.x
- pandas

## Dataset
The dataset, `schools.csv`, should contain the following columns:
- school_name: Name of the school.
- average_math: Average SAT math score for the school.
- average_reading: Average SAT reading score for the school.
- average_writing: Average SAT writing score for the school.
- borough: The borough in which the school is located.

The dataset should be placed in the root directory of the project.

## Usage

1. Place the `schools.csv` data file in the root directory.
2. Run the script. The script will:
   - Read the data.
   - Determine the best schools for math.
   - Calculate the total SAT score for each school.
   - Identify the top 10 performing schools based on the total SAT score.
   - Determine which NYC borough has the highest standard deviation for total SAT scores.
3. Analyze the results.

## Analysis Results

- `best_math_schools`: A DataFrame containing schools with an average math score of 640 or higher, sorted in descending order.
- `top_10_schools`: A DataFrame containing the top 10 schools based on the mean total SAT score.
- `largest_std_dev`: A DataFrame containing the borough with the highest standard deviation for total SAT scores.

## Future Improvements

- Extend the analysis to consider other performance metrics, such as graduation rates or college acceptance rates.
- Visualize the data using graphs and charts to provide a more intuitive understanding of the results.
- Integrate with a database for more efficient data storage and retrieval.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
