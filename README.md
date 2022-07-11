# Actuarial-Excel-Project-5-Income-Statement

Excel Project #5
 

As an actuary, you may encounter working with balance sheets and income statements. It is very helpful to be familiar with how they work. This project explores creating a net income projection based on inputted assumptions and scenarios.

If you need an income statement and balance sheet refresher before starting, check out Brea’s Terminology video below!


Your Task

You are given the completed income statement for 2021. Click here to download it.

Your task is to help project the net income for the years from 2022-2025 (inclusive) by using the following default annual change assumptions for each line on the income statement:

Gross Premiums will increase by 3% each year.
Premiums Ceded to Reinsurers will increase by 1% each year.
Investment Income will increase by 0.2% each year.
Gross Claims will decrease by 1% each year.
Benefits will increase by 1% each year.
Equipment expenses will increase by 0.5% each year.
Claims and Expenses Ceded to Reinsurers will increase by 0.9% each year.
Acquisition Costs Amortization increase by 2% each year.
Change in Insurance Liabilities decrease by 0.7% each year.
The above assumptions are the default assumptions for your tool, however, your tool should be able to accept a user’s input relating to the direction of the annual change (increase/decrease/no change) and a user’s input for the percentage change that is to be assumed in the projections for EACH of the above income statement line items.

That means that a user should be able to change the annual change assumptions, and that your tool should not only work for the default assumptions above, but also for any annual change assumption that a user inputs for each income statement line item.

Note: “No change” means that there is a 0% annual change in the projected values from one year to the next.

Lastly, your tool should also include a “interest rate” input method to implement the following scenarios:

If interest rates are 2-4% (inclusive), then the Investment Income annual change assumption will decrease by 0.25% (multiplicative).
If interest rates are 5-7% (inclusive), then the Investment Income annual change assumption will increase by 0.625% (multiplicative).
If interest rates are 2-4% (inclusive), then the Gross Claims annual change assumption will increase by 1% (multiplicative).
If interest rates are 2-4% (inclusive), then the Change in Insurance Liabilities annual change assumption will increase by 1.5% (multiplicative).
If interest rates are 2-4% (inclusive), then the Equipment Expenses annual change assumption will increase by 2% (multiplicative).
If interest rates are 5-7% (inclusive), then the Gross Claims annual change assumption will decrease by 0.7% (multiplicative).
Example: If the interest rate is set to 6%, the Investment Income would change from 0.02% to 0.2012500%. This is due to the conditions set in the second bullet above. You take the default annual change of assumption for Investment Income and multiply it by the percentage stated. 

      0.2% * 1.00625 = 0.2012500%

An interest rate of 6% would also affect Gross Claims as stated in the last bullet above. The annual change assumption would change from 1% to 0.9930000%. 


