# Sharpe-ratio-calculator

Sharpe Ratio Calculator (Python Basics + NumPy & AI)

This project demonstrates how to calculate and interpret the Sharpe ratio — a key measure of risk-adjusted portfolio performance — using core Python concepts:

Variables

Loops

Functions

NumPy

Formula
𝑆
ℎ
𝑎
𝑟
𝑝
𝑒
=
𝑅
𝑝
−
𝑅
𝑓
𝜎
𝑝
Sharpe=
σ
p
	​

R
p
	​

−R
f
	​

	​


Where:

𝑅
𝑝
R
p
	​

 = Annualized portfolio return

𝑅
𝑓
R
f
	​

 = Risk-free rate (2% used by default)

𝜎
𝑝
σ
p
	​

 = Portfolio volatility (standard deviation)

Example

For a portfolio with an annualized return of 12%, volatility of 10%, and a 2% risk-free rate:

𝑆
ℎ
𝑎
𝑟
𝑝
𝑒
=
(
0.12
−
0.02
)
/
0.10
=
1.00
Sharpe=(0.12−0.02)/0.10=1.00

This means the portfolio earned 1 unit of excess return for each unit of risk.

What I Practiced

Writing reusable functions to calculate return, volatility, and Sharpe ratio

Using loops to process multiple simulated return values

Applying NumPy for vectorized math and performance

Strengthening Python fundamentals while learning a key portfolio management metr
