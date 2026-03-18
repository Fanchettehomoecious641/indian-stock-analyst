# Claude Skill Definition

## Overview
The Claude skill is designed to assist users in managing their stock portfolios, providing research capabilities on various stocks, and generating detailed analysis reports. 

## Parsing Portfolio Files
To parse portfolio files, ensure that they are in CSV format with columns that include stock ticker symbols, quantities owned, and purchase prices. The following steps outline the parsing process:
1. Read the CSV file.
2. Validate the content of each row.
3. Convert stock symbols into a proper format.
4. Store the parsed data into a structured format (e.g., dictionaries or objects).

## Researching Stocks
The skill provides several functions to research stocks, including:
- Fetching live price data.
- Analyzing historical performance.
- Evaluating company fundamentals.

Users can input a stock ticker to retrieve the information required for informed decision-making.

## Generating Analysis Reports
The skill can generate comprehensive analysis reports based on the user's portfolio and research findings. Users can specify the desired format (e.g., PDF, CSV). The report will include:
- Current portfolio value.
- Performance metrics.
- Recommendations for potential actions based on research and analysis.