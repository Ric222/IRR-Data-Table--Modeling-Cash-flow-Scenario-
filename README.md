# Using IRR with Data Tables--Modeling Cash flow Scenarios in Excel   🤑

### Objective

To simulate multiple cash flow scenarios and calculate rate of return on investment

### Problem Statement

Mrs Shelly wants to purchase a farm. But she has a problem. She wants to know if the farm is worth her investment. So she prepared all the cash-flows (purchase, opex every year, vegetable sales and terminal value) as given in excel.

She wants to calculate the potential return on investment

Since, we have a series of estimated cash-flows, we can easily calculate the rate of return using **XIRR** function.

#### What-if the purchase price changes?

Shelly thinks both purchase price and terminal value can change at any time.

Assuming we have the percentage changes in cells like below,

![changes-in-purchase-and-terminal-values](https://github.com/Ric222/IRR-Data-Table--Modeling-Cash-flow-Scenario-/assets/104567667/f18e7018-d562-45fa-8ddb-bec63f59e3dc)

We can calculate **IRR values for all possible scenarios using Data Tables** in Excel which is a better way than writing XIRR formula for each scenario.




![cashflow](https://github.com/Ric222/IRR-Data-Table--Modeling-Cash-flow-Scenario-/assets/104567667/6d7c7e0e-f563-409f-9ef2-cc5b96fdc98d)

### Result

Looking at the table, we can conclude that if Shelly can negotiate the purchase price down to 15% and sell it off with a terminal value marked up by 10% from intial termial value, she will get the **best return as 10.48%**.

