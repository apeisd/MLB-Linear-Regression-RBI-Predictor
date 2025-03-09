Overview

This project aims to model and predict Runs Batted In (RBI) in Major League Baseball (MLB) by exploring various player statistics (e.g., Home Runs, Doubles, Walks) and fitting a series of linear regression models with second-order and interaction terms. The final model helps illustrate which factors are most influential in a player’s RBI total.

**Project Objectives**:
1. Build an initial linear regression model (including only first-order terms) to see how basic features like G (Games), HR (Home Runs), X2B (Doubles), BB (Walks), etc., impact $\sqrt(RBI)$
2. Expand the model by including squared terms and interactions (e.g., $𝐺×𝐻𝑅$ to capture more complex relationships.
3. Use partial F-tests (ANOVA) to systematically drop unnecessary terms, arriving at a parsimonious final model.
4. Validate assumptions (normality, homoscedasticity, independence) through diagnostic plots and statistical tests (e.g., Shapiro-Wilk, Durbin-Watson, VIF).
