# Dividend Discount Model (DDM) Analysis for AT&T

## Overview
This project explores the Dividend Discount Model (DDM) using AT&T's historical dividend and stock split data. The analysis includes:
- Extracting AT&T's dividends and stock splits.
- Calculating the dividend growth rate by summing stock splits per year and finding the median growth rate.
- Estimating the cost of equity using Beta (systematic and unsystematic risk), market return, and risk-free rate.
- Determining the fair share price using the last dividend and the calculated dividend growth rate.

## Methodology
### 1. **Extracting Data**
- Historical dividend data was retrieved and analyzed.
- Stock splits were accounted for to adjust dividend calculations.

### 2. **Calculating Dividend Growth Rate**
- The dividend growth rate was computed by summing stock splits per year.
- The median growth rate was used for a more stable estimate.

### 3. **Estimating Cost of Equity**
Using the Capital Asset Pricing Model (CAPM):

\[
\text{Cost of Equity} = R_f + \beta ( R_m - R_f )
\]

Where:
- \( R_f \) is the risk-free rate.
- \( \beta \) represents systematic and unsystematic risk.
- \( R_m \) is the market return.

### 4. **Fair Share Price Calculation**
Using the Gordon Growth Model (Constant Growth DDM):

\[
P = \frac{D_1}{r - g}
\]

Where:
- \( P \) is the fair share price.
- \( D_1 \) is the expected next dividend.
- \( r \) is the cost of equity.
- \( g \) is the dividend growth rate.

## Results
- The calculated dividend growth rate provided insights into AT&T’s dividend sustainability.
- The estimated cost of equity was derived using real market parameters.
- A fair value estimation for AT&T’s stock price was obtained.

## Credits
This project was inspired by the Coursera course taught by **[Ochilov](https://www.coursera.org/instructor/ochilov)**.

## Proof of completion
**verify here - https://www.coursera.org/account/accomplishments/verify/8GWWN4TW0NVM**
