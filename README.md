# Index Fund Optimization Using Integer and Linear Programming

## Overview
This project addresses the challenge of index fund optimization to closely track the NASDAQ-100 index performance using a reduced number of stocks. Leveraging Integer Programming (IP) for stock selection and Linear Programming (LP) for determining stock weights, we aimed to balance precision, cost-efficiency, and diversification in passive equity management.

## Goal
The primary goal was to design an index fund that efficiently tracks the NASDAQ-100 using substantially fewer components. We formulated an integer program to select a specific number of stocks (m out of n) based on a similarity matrix and then used a linear program to determine the optimal stock weights to purchase for the portfolio. The performance was evaluated against the NASDAQ-100 index using data from 2019 and 2020, ensuring adaptability to different market conditions.

## Methodology
1. **Mapping Stock Synergy**: Computed a correlation matrix to understand stock relationships and inform portfolio construction.
2. **Initial Portfolio Construction**: Combined IP for selecting a subset of stocks and LP for weight allocation, with the aim of maximizing the similarity between chosen stocks and their representatives.
3. **Portfolio Analysis for Different 'm' Values**: Explored various portfolio sizes (m) to find the optimal balance between tracking performance and portfolio complexity.
4. **Comparison of Approaches**: Evaluated different stock selection and weight assignment methodologies to enhance the tracking accuracy of the NASDAQ index.
5. **Recommendations**: Based on the analysis, we recommended a 50-stock portfolio composition for an optimal balance between accuracy and manageability.

## Findings
The optimized index fund with 50 stocks showed a substantial alignment with the NASDAQ-100 index trends, indicating a strong potential for capital appreciation and positive returns. The portfolio's performance in 2019 and 2020 confirmed the effectiveness of our optimization strategy, although adjustments are considered to improve the fund's performance in varying market conditions.

## Team Members
- Santhosh Ramkumar
- Bhuvana Chandrika Kothapalli
- Gaytri Riya Vasal
- Jahnavi Angati

## Conclusions
Our findings suggest that the optimal number of stocks for the index fund is 50, providing a balance between tracking accuracy and manageability. This approach minimizes risk associated with over-exposure to a large number of stocks while ensuring significant representation of the NASDAQ index.

## Recommendations
- **Portfolio Composition**: A 50-stock portfolio is recommended for effective tracking of the NASDAQ index.
- **Weight Distribution**: An optimized weight distribution with an emphasis on highly representative stocks.
- **Balance Between Accuracy and Manageability**: The 50-stock portfolio offers an optimal compromise, minimizing tracking error and simplifying management.

This project underscores the potential of quantitative analysis in enhancing investment strategies and delivering consistent performance aligned with market benchmarks.
