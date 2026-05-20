## Purpose
This paper aims to derive and empirically evaluate market-observable feasibility bounds for option-hedged collateralized lending against volatile liquid assets, using crypto-collateralized BNPL-like lending as the motivating application.

## Design/methodology/approach
The paper develops an algebraic framework for a secured loan backed by crypto collateral and hedged with listed put options. It derives market-observable feasibility bounds linking loan-to-value, the collateral shortfall threshold, option strike, option premium, maturity, merchant fee revenue and a bounded-loss budget. The bounds are tested using historical ETH put option data from Deribit and ETH spot prices from January 2021 to August 2025.

## Findings
The paper shows that feasibility can be converted into market-observable bounds that support loan-origination decisions using current collateral prices, option strikes, option premiums, maturity, LTV, merchant fee revenue and loss tolerance. In the ETH application, feasibility is driven mainly by merchant fee revenue, maturity and the market price of downside protection. Higher fees and shorter maturities widen feasible LTV ranges. Although many individual quotes are infeasible, day-level availability is substantially stronger, suggesting that option chains often contain at least one implementable hedge. Zero-loss structures require conservative LTVs, while bounded-loss structures expand feasibility only modestly.

## Research limitations/implications
The empirical analysis is limited to ETH options on Deribit and does not model execution frictions.

## Practical implications
The framework provides lenders with a market-implied origination screen for assessing whether collateralized BNPL loans can be supported by available option hedges.

## Originality/value
The paper converts volatile-collateral downside risk into transparent algebraic feasibility bounds that can be tested directly against observable option prices.

## Plain Language Summary
This paper studies buy-now-pay-later loans in which a customer pledges a volatile asset, such as cryptocurrency, as collateral. The merchant is paid upfront, but the lender faces losses if the collateral falls sharply before repayment. The paper shows how put options can protect against this risk and derives market-based rules for deciding when such loans are economically feasible. Using ETH price and option data, it finds that feasibility improves for shorter loans, higher merchant fees, and cheaper downside protection. The framework helps lenders use option-market data to decide whether a collateralized BNPL loan can be safely originated.

