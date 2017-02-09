
<p align="center"><img src="https://github.com/lakshmiDRIP/DRIP/blob/master/DRIP_Logo.gif?raw=true" width="100"></p>

**v2.54**  27 December 2016

DRIP Asset Allocation is a collection of model libraries for MPT framework, Black Litterman Strategy Incorporator, Holdings Constraint, and Transaction Costs.

DRIP Asset Allocation is composed of the following main model libraries:
* MPT Framework Model Library
* Black Litterman Model Library
* Holdings Constraint Model Library
* Transaction Cost Model Library

For Installation, Documentation and Samples, and the associated supporting Numerical Libraries please check out [DRIP] (https://github.com/lakshmiDRIP/DRIP).


 ##DRIP Core Technical Specifications

 * [Asset Allocation Library](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/AssetAllocation/AssetAllocation_v2.13.pdf)
 * [Fixed Income Analytics](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/FixedIncome/FixedIncomeAnalytics_v2.47.pdf)
 * [Transaction Cost Analytics](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/TransactionCost/TransactionCostAnalytics_v2.53.pdf)


**DRIP Supporting Technical Specifications**

 * [Spline Builder Library](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/SplineBuilder/SplineBuilder_v0.82.pdf)
 * [Numerical Optimization Library](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/NumericalOptimizer/NumericalOptimization_v2.05.pdf)
 * [Statistical Learning Library](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/StatisticalLearning/StatisticalLearningLibrary_v0.80.pdf)
 * [Machine Learning Library](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification/MachineLearning/MachineLearningLibrary_v0.92.pdf)


**Additional Documentation**

 * [DRIP GitHub Source](https://github.com/lakshmiDRIP/DRIP)
 * [DRIP API Javadoc](https://lakshmidrip.github.io/DRIP/Javadoc/index.html)
 * [DRIP Release Notes](https://github.com/lakshmiDRIP/DRIP/tree/master/ReleaseNotes)
 * [DRIP Technical Specifications](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/DRIPSpecification)
 * [DRIP External Specifications](https://github.com/lakshmiDRIP/DRIP/tree/master/Docs/External)
 * User guide is a work in progress!


**Samples (Asset Allocation)**

 * [Asset Liability Management](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/alm)
 * [Asset Allocation Core](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/assetallocation)
 * [Asset Allocation Excel](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/assetallocationexcel)
 * [Black Litterman Core](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/blacklitterman)
 * [Efficient Frontier MPT](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/efficientfrontier)
 * [He Litterman Intuition](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/helitterman)
 * [Idzorek User Confidence](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/idzorek)
 * [Asset Allocation Core](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/assetallocation)


**Samples (Transaction Cost)**

 * [Mean-Variance Execution](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/almgrenchriss)
 * [Nonlinear Impact Function](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/almgren2003)
 * [Market Impact Estimator](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/athl)
 * [Optimal Numerical Execution](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/execution)
 * [Liquidity VaR Objective](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/lvar)
 * [Principal Agency Execution](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/principal)
 * [Bayesian Trend Drift Analysis](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/trend)
 * [HJB Based Adaptive Trajectories](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/almgren2009)
 * [Adaptive, Static, and Rolling Horizon Trajectories](https://github.com/lakshmiDRIP/DRIP/tree/master/org/drip/sample/almgren2012)


**Features**

###MPT Framework Model Library

 * MPT Core Mathematical Model
 * CAPM Asset Pricing

###Black Litterman Model Library

####The Black Litterman Model

 * Canonical Black-Litterman Reference Model
 * Computing the Equilibrium Returns
 * Specifying the Views
 * View Distribution in the Asset Space
 * Specifying Omega
 * Omega Proportional to the Variance of the Prior
 * Using Confidence Inteval for Omega
 * Omega as the Variance of Residuals from a Factor Model
 * Using Idzorek's Method for Omega
 * The Estimation Model
 * Theil's Mixed Estimation Model
 * The PDF Based Approach
 * Using Bayes' Theorem for the Estimation Model
 * The Alternate Reference Model
 * The Impact of Tau
 * Calibration of Tau
 * Black Litterman Model Implementation Steps
 * Extensions to the Black Litterman Model

####Black Litterman Model Attributions

 * Analysis of the Unconstrained Optimal Portfolio
 * Impact of an Incremental Projection
 * Projection Distribution Dependence on Parameters
 * Black Litterman Intuition Numerical Examples

####Incorporating User Specified Confidence Levels

 * Estimating the Excess Returns Distribution
 * Reverse Optimization of Expected Returns
 * The Black Litterman Model
 * Building the Inputs
 * Fine Tuning the Model
 * Method for Incorporating User-Specified Confidence Levels
 * Implied Confidence Levels
 * The Tilt-Based Intuitive Approach

####Simplified Black Litterman Surplus Optimizer

 * Black Litterman Surplus Optimizer Inputs
 * Cash Flow Projections and Liability Returns

###Transaction Costs Model Library

####Execution of Portfolio Transactions - Optimal Trajectory

 * Defining a Trading Strategy
 * Price Dynamics
 * Temporary Market Impact
 * Capture and Cost of Trading Trajectories
 * Linear Impact Functions
 * The Efficient Frontier of Optimal Execution
 * The Definition of the Frontier
 * Explicit Construction of Optimal Strategies
 * The Half-Life of a Trade
 * Structure of the Frontier
 * The Utility Function
 * Value-at-Risk
 * The Role of Utility in Execution
 * Choice of Parameters
 * The Value of Information
 * Drift
 * Gain due to Drift
 * Serial Correlation
 * Parameter Shifts
 * Numerical Optimal Trajectory Generation

####Non-linear Impact and Trading-Enhanced Risk

 * The Model
 * Nonlinear Cost Functions
 * Objective Functions
 * Almgren (2003) Example
 * Trading-Enhanced Risk
 * Constant-Enhanced Risk
 * Linear-Enhanced Risk
 * Almgren (2003) Nonlinear Example Sample

####Market Impact Function/Parameters Estimation

 * Data Description and Filtering Rules
 * Data Model - Variables
 * Trajectory Cost Model
 * Permanent Impact
 * Temporary Impact
 * Choice of the Functional Form
 * Cross-Sectional Description
 * Model Determination
 * Determination of the Coefficients
 * Residual Analysis

####Optimal Execution of Program Trades

 * Efficient Frontier Pricing of Program Trades
 * The Efficient Frontier Including Discount
 * Performance Measures
 * Annualization
 * Definition of the Information Ratio
 * Applications of the Information Ratio

####Bayesian Trading with a Daily Trend

 * Price Motion Using Bayesian Update
 * Bayesian Inference
 * Trading and Price Impact
 * Optimal Trading Strategies
 * Trajectory by Calculus of Variations
 * Optimality of the Bayesian Adaptive Strategy
 * Stochastic Optimal Control Treatment

####Cost Adaptive Arrival Price Trading

 * Adaptive Strategies - Trading in Practice
 * AIM/PIM, and Prospect Theory
 * Market Model and Static Trajectories
 * Non-dimensionalization
 * Small Portfolio Limit
 * Portfolio Comparison
 * Single Update - Mean and Variance
 * Almgren and Lorenz (2007) Results Replication
 * Continuous Response - Numerical Results Comparison

####Optimal Trading in a Dynamic Market

 * Limitations of Arrival Price Frameworks
 * The Liquidation Problem
 * The Cost of Trading
 * Constant Coefficients
 * Coordinated Variation
 * Rolling Time Horizon Approximation Strategy
 * Small Impact Approximation
 * Dynamic Programming - Fully Co-ordinated Version
 * Log-Normal Model and Non-dimensionalization
 * Constant Market
 * Long Time Asymptote
 * Dynamic Programming - Custom Volatility and Liquidity
 * Log-normal Volatility/Liquidity
 * Coordinated Variation of Volatility and Liquidity
 * Long/Short Time Asymptotic Behavior
 * HJB Based Numerical Solution
 * HJB Grid Time Discretization
 * HJB Grid Space Discretization
 * Almgren (2009, 2012) Solutions Replication

####Market Making Models

 * Width/Skew/Size Estimation Models
 * Market Making System SKU
 * Market Making Parameter Types
 * Intra-day Pricing Curve Generation Schemes
 * Mid-Price Models
 * Width Models
 * Skew Models
 * Size Model
 * Heuristic Controls
 * Flow Analysis


##Licence

Apache 2.0


##Contact

lakshmi@synergicdesign.com
