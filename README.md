# Market-Risk-Analysis-using-Value-at-Risk-VAR-A-Complete-Python-Toolkit
This report provides a comprehensive Python-based toolkit to estimate market risk using Value at Risk (VaR). It demonstrates three standard methods: Historical Simulation, Parametric  (Variance-Covariance), and Monte Carlo Simulation. The project can analyze single stocks or a  multi-asset portfolio
Project Objective
 To measure and compare different approaches to calculating Value at Risk (VaR) for individual
 assets and a portfolio of assets.
 Methodology
 1. Historical VaR: Based on actual historical returns without assuming any distribution. 2.
 Parametric VaR: Assumes returns are normally distributed and calculates VaR using mean and
 standard deviation. 3. Monte Carlo VaR: Simulates a large number of hypothetical outcomes using
 randomly generated returns.
 Portfolio-Level VaR Extension
 The toolkit supports portfolio-level VaR by computing the weighted average of asset returns and
 considering correlations between them. This allows risk analysts to better assess total portfolio risk
 rather than individual asset VaR in isolation.
 Sample Output (for AAPL)
 Method
 VaR (95%)
 Historical VaR-3.12%
 Parametric VaR-2.87%
 Monte Carlo VaR $5.41
 Conclusion
 This Python toolkit provides a flexible and practical solution for calculating Value at Risk (VaR) for
 single stocks and portfolios. The modular design makes it suitable for professional use in risk
 departments and academic projects
