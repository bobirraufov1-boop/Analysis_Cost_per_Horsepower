# Analysis_Cost_per_Horsepower

I built a quick data pipeline to figure out where you actually get the most horsepower for your dollar in the 2025 car market, with a focus on EVs and Hybrids.

Instead of just comparing raw prices, I created a **Cost_per_HP** metric (`Price / Horsepower`) to see which models deliver pure performance efficiency and which ones charge heavily for the badge.

## Quick Findings
* **EVs rule pure value:** Mass-market electric cars deliver huge performance per dollar. Models like the Tesla Cybertruck sit right around **$87/HP**.
* **Hybrids break the scale:** Hypercars and limited-run hybrids push prices into the $2.5M–$3.2M range, driving the cost per horsepower above **$3,000/HP**.
* **The Premium Gap:** There is a ~5x efficiency gap between utility-focused EVs and traditional luxury/premium setups.

## Visual
The plot (`Price vs Horsepower`) clearly shows the main cluster of high-efficiency EVs along the bottom, while a few extreme luxury hybrids blow past the $2.5M mark.

## Tools Used
* Python 3.12
* Pandas for data processing & metric engineering
* Seaborn / Matplotlib / Plotly for visualization
