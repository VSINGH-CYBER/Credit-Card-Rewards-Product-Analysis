# Rewards Transparency Problem Analysis

## Problem Overview

Credit card reward programs are a key driver of customer engagement and card usage. However, many financial institutions only calculate and display rewards after a transaction has fully settled. 

Between the time a purchase is authorized and when it settles, customers typically see a "pending transcation" but do not see the rewards asssociated with that purchase. If the final transaction amount changes due to factors such as tips, merchant category adjustments, or even settlement differences, the reward calculation may also change. 

## Current Transaction Flow

A typicial credit card transaction follows this process:

1. Customer makes a purchase using their credit card.
2. The transaction is authorized by the issuing bank.
3. The transaction then appears in the customer's account as a **pending transaction**.
4. The merhcant submits the final transaction for settlement.
5. The transaction settles and the final purchase amount is confirmed.
6. The rewards engine calculates points or cashback based on the final transaction data.
7. Rewards are then displayed in the customer's account.

## Customer Pain Points

Several pain points can arise from the delay between transaction authorization and reward calculation:

| Customer Experience Issue | Description |
|---------------------------|-------------|
| Lack of transparency | Customers cannot immediately see the rewards associated with the purchase. |
| Changing transcation amounts | Tips or adjustments can change the final transaction value, leading to different reward totals than expected. |
| Perceived reward inaccuracies | Customers may believe rewards wereincorrectly caluculated. |
| Delayed gratification | Immediate reward feedback can increase engagement, but the current system delays this feedback. |
