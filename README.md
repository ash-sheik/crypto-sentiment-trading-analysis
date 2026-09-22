# Crypto Market Sentiment and Trading Performance Analysis
An analysis of the relationship between Crypto - Fear &amp; Greed Index and trading performance (PnL/Risk) using Python
## 🌟 The Big Idea
In trading, they always say "buy the dip" or "be greedy when others are fearful," but does that actually work for most people? I wanted to see if there was a real link between market emotions (the Fear & Greed Index) and how much money traders actually walk away with.

I took raw trading history, combined it with daily sentiment scores, and looked for patterns in the noise.

## 🔍 What the Data Told Me (Key Insights)
1. Greed is (Actually) Good for Profit
It turns out that when the market is in a "Greed" phase, traders in this dataset were significantly more successful. The average profit jumped to $87.89 compared to just $50.04 during "Fear" days.
2. Fear Makes People Do Crazy Things
When I looked at the risk distribution (the boxplots), I saw huge "outlier" dots during Fear days.
Most people trade small when they’re scared, but a few people go "all in." These are likely "revenge trades"—people trying to win back what they just lost. This leads to massive wins or (more likely) massive losses.
3. We Trade More When We’re Panicked
The data showed more trades happening during Fear, but the "quality" of those trades was lower.
Panic makes us busy, not productive. We click "buy" and "sell" more often when we're anxious, but we actually make more money when we're calm and the market is trending upward.

## 🛠️ How I Built This
I kept the tech stack focused and efficient:

Python (Pandas & NumPy): For the heavy lifting—cleaning the data and merging the two different datasets.

Seaborn & Matplotlib: To turn the rows of numbers into the charts you see in the visuals/ folder.

Jupyter Notebook: Where all the experimentation happened.

## 📂 What's Inside?
data/: https://drive.google.com/drive/folders/1_sbi4r_6SsnV-1Il6tFCqen_QEp1-ZLJ?usp=sharing 
Both the raw files I started with and the final cleaned version.

notebooks/: My step-by-step logic and code.

visuals/: The charts that prove the insights above.

## 🚀 Want to see for yourself?
If you want to run the analysis on your own machine:

Clone this repo.

Make sure you have pandas and seaborn installed.

Open the notebook and run the cells—the charts will generate automatically!

Project summary : https://docs.google.com/document/d/1l-xVouyi6Sv3hW3he6PcqSyH-DJaMqTUndb5SEiyWYI/edit?usp=sharing

## 👩‍💻 Author

**Ashiba B**  
Data Analyst | SQL | Power BI | Excel | Python  

[LinkedIn](https://www.linkedin.com/in/ashiba-data-analyst) | [Email](mailto:ashibab23@gmail.com)
