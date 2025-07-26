## Correlation Matrix
This model tracks the evolving relationship structure across macro assets, equity sectors, commodities, currencies, and crypto. It combines rolling correlation, beta statistics, and volatility-adjusted dispersion metrics to reveal when assets are moving together — and when they begin to decouple, posing either risk or opportunity.

- Visualizes pairwise linear relationships across 30+ assets.
- Color-coded heatmap instantly reveals high-correlation clusters vs. decorrelated outliers.
- Correlation shifts serve as a risk-on / risk-off sentiment gauge, useful for allocation and hedging.
  
![CorrelationMatrix](https://github.com/user-attachments/assets/a806e99c-406a-49e4-8b5f-85882b25af98)

## Beta and Correlation Stats and Conditional Visualizer

This Model computes beta vs the benchmark for for each asset, alongside rolling average and percentile ranks.
It displays how sensitive an asset is to the equity market, helping identify leading/lagging exposure.

### The Purpose:

- Detects structural breaks in asset relationships using time-based thresholds.
- Visual overlays on the benchmark price chart show periods where correlation or beta exceeded key thresholds.
- Helps identify when diversification breaks down, and when hedges may become ineffective

![image](https://github.com/user-attachments/assets/d3e3bcf0-3695-47e3-bbb8-0616a8edebbf)

## Correlation, Covariance & Beta Analysis 

### What is beta? 
Beta is the sensitivity of a dependent asset's return to an independent asset’s return, expressed in %. It represents the systematic risk of the asset and comes out of the Capital Asset Pricing Model (CAPM) framework. 

### Mathematical Derivations

##### If you break it down: 
Beta is the correlation multiplied by volatility ratio. Beta captures both the strength and the scale of how the asset moves relative to a benchmark. 

##### Applying Beta to The Process 
Beta can help us quantify the amount of hedges you need to transfer the risk from directionality to relative performance.The juice of the trade comes from what remains after the broad systematic risk is stripped away. When you strip out systematic risk, what is left is idiosyncratic alpha. 

One example of this is a dispersion trade: Dispersion just means that your trade thesis is about the misaligned relationships between assets. Perhaps you believe QQQ is overpriced to its beta. So you expect QQQ to underperform its historical beta expectations. In that scenario you would short QQQ and buy SPY in a beta-weighted dispersion. 

It’s important to understand that the historical algebra must hold true in order for this trade to be profitable. In other words, the relationship or beta in this scenario must hold true.  

##### Risk Remaining Model
In the Capital Asset Pricing Model (CAPM), the total risk of an asset equals the 
systematic risk (explainable risk by the benchmark) + Idiosyncratic risk (unexplained). 

Simpler said, the risk remaining just means the asset’s movement that is not explained by the benchmark you used. When correlation drops below a certain threshold, more than half of the asset’s variance is not explained by the benchmark – the lower the correlation, the less effective the hedge. It’s also critical to understand that the relationship between correlation and risk remaining is non linear. So even a small drop in correlation causes a big increase in residual risk. 

**You hedge with this formula:**
Hedge Notional=β×Position Size

## Correlation / Covariance 

#### Analyzing Asset Relationships

The covariance matrix serves as a crucial tool for understanding how assets interact with one another, providing valuable insights for designing a diversified portfolio that balances risk and return effectively.

#### Risk Assessment and Diversification

- **Diversification:** A key principle in risk management is to include assets with minimal or negative covariance to ensure they don't move in the same direction. In this case, while all the covariances between stocks are positive, their magnitudes vary. For instance, Stock A and Stock C have a relatively low covariance (0.000015), making them suitable candidates for diversification within the portfolio.
- **Volatility:** Evaluating variance values can highlight potential contributions to portfolio stability. Assets with lower variances, such as Stock B, tend to stabilize the portfolio, whereas those with higher variances, like Stock, can introduce greater risk but also the potential for higher returns.

### Portfolio Construction Strategies
Asset Allocation: When constructing a portfolio, assigning greater weight to low-variance assets can help minimize overall risk. Depending on your risk appetite, higher-variance assets can also be included in smaller proportions to enhance return potential.
- **correlation Insights:** Positive covariances among all assets suggest they generally move in the same direction. However, weaker correlations—indicated by lower covariance values—can help identify pairs of assets that complement each other, optimizing the risk-return balance.
- **Considerations:** It is always vital to understand that models built to demonstrate historical relationships- as do the correlation and covariance models- can eventually, and typically do eventually lose their predictive power. It is part of an evolving system.






## Project Archive 

| <a href="https://github.com/PatrickRych/Project">LandingPage </a>
| <a href="https://github.com/PatrickRych/Portfolio-Manager">Project Archive </a>
****

