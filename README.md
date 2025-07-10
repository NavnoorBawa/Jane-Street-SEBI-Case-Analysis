# Jane Street SEBI Case Analysis

## Overview

This model performs complete forensic analysis of Jane Street's market manipulation scheme using official SEBI order data. It reconstructs how they exploited Indian derivatives markets to generate ₹4,844 crores in illegal profits across 21 trading days.

## How The Model Works

### Data Processing
The model ingests raw trade data from SEBI's official order and transforms it into a complete timeline of Jane Street's activities. Every trade is mapped with precise timestamps, quantities, prices, and market impact calculations.

### Strategy Reconstruction  
The analysis identifies two distinct manipulation patterns:

**Intra-day Index Manipulation**: Jane Street artificially inflated index prices in the morning by aggressively buying underlying stocks, then built massive bearish options positions at favorable prices, and finally crashed the index by afternoon through aggressive selling.

**Extended Marking the Close**: Large directional trades concentrated in the final hour of expiry days to engineer favorable settlement prices for existing options positions.

### Cross-Asset Analysis
The model tracks coordination across multiple market segments simultaneously - cash equities, stock futures, index futures, and index options - revealing how Jane Street manipulated one segment to profit in another.

### Market Impact Quantification
Every trade's impact on Last Traded Price (LTP) is calculated, showing how Jane Street's aggressive trading created artificial price movements. The model separates Jane Street's price impact from natural market movements.

### Profit Attribution
The analysis breaks down how losses in underlying markets (₹61.6 crores on Jan 17, 2024) were deliberately incurred to generate much larger profits in options markets (₹734.93 crores), achieving 1,093% return on manipulation costs.

## What The Model Reveals

### Market Structure Exploitation
- **Liquidity Asymmetry**: Options market was 353 times larger than underlying cash market, allowing small underlying moves to create massive options profits
- **Leverage Amplification**: ₹4,370 crores in underlying positions controlled ₹32,115 crores in options exposure (7.3x leverage)
- **Settlement Engineering**: European-style options settlement based on closing prices created manipulation opportunities

### Manipulation Mechanics
- **Volume Dominance**: Up to 25.24% market share in individual banking stocks during critical windows
- **Price Engineering**: Systematic LTP manipulation through aggressive above/below market trading
- **Timing Precision**: ₹572 crores deployed in just 8 minutes during critical manipulation window

### Market Impact
- **Retail Harm**: 1.6 million retail options traders affected by artificial pricing
- **Price Distortion**: BANKNIFTY artificially moved 1,148 points through manipulation
- **Systemic Risk**: Single entity controlling settlement outcomes for major index

## Analytical Framework

### Phase I Analysis (Morning Manipulation)
Tracks how Jane Street artificially supported index levels through massive buying while simultaneously building bearish options positions at artificially favorable prices.

### Phase II Analysis (Afternoon Liquidation)  
Maps the systematic reversal of morning positions, creating downward pressure on the index to benefit the larger options positions.

### Options Strategy Analysis
Reconstructs the precise put/call combinations used, delta exposure progression, and how options positioning was coordinated with underlying market manipulation.

### Profit Flow Analysis
Traces money flow from manipulation costs through to final profits, validating that underlying losses were deliberate costs to generate options profits.

## Key Insights

### Strategy Innovation
Jane Street created a new form of market manipulation - "settlement price derivatives" - where they manufactured predetermined options outcomes through temporary underlying price distortion.

### Regulatory Gaps
The manipulation exploited unclear rules around cross-segment coordination, using Indian entities for cash trading while FPI entities handled derivatives to circumvent regulatory restrictions.

### Market Structure Vulnerabilities
The case exposes how extreme options-to-underlying volume ratios create systematic manipulation opportunities that traditional surveillance systems may miss.

### Detection Challenges
The manipulation was sophisticated enough to operate for 1.4 years before detection, suggesting existing market surveillance frameworks need enhancement for cross-asset manipulation patterns.

## Model Output

The analysis produces complete forensic reconstruction showing exactly how Jane Street systematically exploited market structure inefficiencies to transfer wealth from retail traders to themselves through coordinated cross-asset manipulation strategies.
