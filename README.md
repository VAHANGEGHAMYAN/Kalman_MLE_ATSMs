# Application of Kalman Filter in Asset Pricing: Estimation of No-Arbitrage Autoregressive Term Structure Model with Macroeconomic and Latent Variables
	
## Summary
    
In this project, I discuss and implement the estimation of an Affine Term Structure Model (ATSM) using the Kalman filter. The ATSM is a family of models that describe the relationship between interest rates and the time to maturity of bonds. This is achieved by establishing a relationship between bond returns and underlying state variables in the risk-neutral world, where all assets have a return equal to the risk-free asset.  Then, I transfer this relationship from the risk-neutral world to the real world by estimating the Radon-Nikodym derivative process that corresponds to the observed data.

These models are widely used in fixed-income pricing, risk management, and interest rate forecasting. They provide a framework to understand and predict the term structure of interest rates, which is essential for pricing bonds, options, and other fixed-income securities. I provide an illustrative explanation of the codes and show how to estimate parameters and compute the hidden states when you don't have the parameters. This includes the pricing of bonds and the estimation of latent factors that drive the yield curve. I also provide intuitive explanations of asset pricing concepts from my understanding in the blue boxes, which will be helpful for the reader. In appendix B, I provide an introduction and a small literature review for readers who find the topic interesting and want to understand it better. This project assumes the reader has some basic knowledge about finance and time series analysis. This project serves as a teaching material

**Keywords:** Kalman Filter, Affine Term Structure Models, Risk-Neutral Pricing

**Prerequisites:**
* Probability and Statistics
* Time Series Analysis
