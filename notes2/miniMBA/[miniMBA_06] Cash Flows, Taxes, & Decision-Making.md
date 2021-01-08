#  [miniMBA_06] Cash Flows, Taxes, & Decision-Making

[toc]

### A Systematic Approach to Decision-Making

Making good decisions requires a systematic approach. While such an approach can be useful in many situations, it is especially helpful when making investment decisions.

Investment is a broad term which could refer to many things, including but not limited to: the purchase of another company, the purchase of a machine, or even research and development or training costs to develop a stronger workforce.





The systematic approach outlined in this unit includes 9 steps:

1. **Establish Goal/Objective** - What is your organization trying to accomplish? This step is imperative because it drives the rest of the process.
2. **Specify Decision Criteria** - what conditions need to be met in order for an investment to further your organization's goals?
3. **Determine How to Measure Criteria** - Determine how to measure whether and to what extent an investment meets the criteria you specified.
4. **Develop Model** - Create a model which helps you accomplish step 3.
5. **Gather/Input Data into Model** - Collect the necessary data to use your model.
6. **Analyze Model** - Assess the result and determine if the investment would help your organization meet its goal/objective. At this point, you may realize you need more information or that another model might be better. If so, you many need to revisit earlier steps.
7. **Make & Communicate Decision** - Based on your analysis, make your decision and share it with others.
8. **Implement Decision** - Put your decision to the test!
9. **Evaluate Decision** - Did the results turn out as expected? How could you use the results to help make a better decision the next time?

***

### Time Value of Money and Modeling Basics

When evaluating alternative investments, it is imperative to factor in the time value of money.

- The time value of money suggests that because money can be invested and earn a return, there is a time value to it. A dollar in your hand today is worth more than a dollar you will receive at some point in the future because a dollar in hand can be invested and turned into more money starting now.
- It is not enough to know that one investment will generate higher cash inflows than another; the timing of those cash flows matters.



##### Present Value

Present value is a formula used to compare cash flows that won't occur at the same time by expressing their value in economically equivalent terms. The way that accountants do this is by valuing future cash flows in terms of today's dollars. Below is the formula for present value where **'future value'** is the amount of the expected future cash flow, **'r'** is the annual interest rate (discount rate), and **'n'** is the number of periods (usually years) until the future cash flow is expected to occur. 
$$
\text{Presnet Value}=\frac{\text{Future Value}}{(1+r)^n}
$$

##### Calculating Present Value

- Tools such as Microsoft Excel or Google Sheets can be used to calculate present value. 
- Any time you set up a model (Excel sheet), make it formula based so that it can be quickly adapted as facts and assumptions change.
- When using the template included in the exercise files, yellow cells are where we input our data or assumptions. We can change these yellow cells as facts or assumptions change. On the other hand, blue cells contain formulas that use the data we input into the yellow cells. Setting up a formula in this way means that the blue cells will automatically update whenever we change any of the information input into the yellow cells, saving a lot of time and effort.

***

### Goals, Decision Criteria, & Measuring Value

The first three steps of the systematic approach to decision-making process are to establish the goal/objective, specify decision criteria, and determine how to measure that criteria. In this lesson, you took a closer look at each of these steps and learned about the concept of net present value.

##### Setting the Goal/Objective

- Identifying the goal or objective is important because this information guides us when we are specifying what criteria need to be met before choosing an investment.

##### Specifying Decision Criteria

- After the goal/objective has been established, you must specify criteria that need to be met in order for an investment to be consistent with those goals. This is known as a **decision rule**.
- If the decision rule is met, you would make the investment; if it is not met, you would not make the investment.
- The decision criteria should be stated in terms of the goal/objective, so if the goal is maximizing firm value, then the decision criteria should be framed in terms of organizational value.

##### Determining How to Measure Criteria

- In this step, you need to determine whether and to what extent each alternative investment meets the decision rule you set.
- There are many ways to measure criteria, but some may be more effective than others.
- - - Example: If the objective is to maximize organizational value, there are several ways to measure this:
    - - 1. Measure in terms of how quickly you recoup your initial investment so the investment that has the shortest payback period is more valuable. The flaw with this method is that it ignores cash flows beyond those that allow the company to recoup its initial investment.
        2. Measure in terms of the total cash generated by the investment. The flaw with this method is that it ignores the timing of cash flows.
        3. Measure using **net present value.** This method addresses the weaknesses of the first two, and is therefore the best of these three options for measuring the criteria of maximizing organizational value.

##### Net Present Value

- Net present value is an extension of the present value concept you learned in Lesson 2.
- Net present value tells us whether the future cash flows expected from an investment are worth more than the cost of the investment.
- The formula for net present value can be seen below. In this formula, negative Cash Flow0, represents the initial cash outflow required to make the investment; the remaining terms represent the present value formula.

$$
\text{Net Present Value}=-\text{Cash Flow}_0+\frac{\text{Cash Flow}_1}{(1+r)^1}+\frac{\text{Cash Flow}_2}{(1+r)^2}+...+\frac{\text{Cash Flow}_n}{(1+r)^n}
$$

- When computing net present value, you are really adding up the present values of the expected future cash flows and netting the total against the initial cost of the investment.
- A positive net present value it means the value of the money coming in from an investment is greater than the value of the money that has to go out for the investment.
- A negative net present value means the cost of the investment is greater than the value of the money coming in from that investment.

***

### Modeling Net Present Value

Determining net present value can be difficult. In this lesson, you practiced calculating net present value using a simpler Excel model. To use this model, you need the following information:

- Discount rate
- Each investment's cash flows starting in period 0 (the time you acquire the investment)



Below are some helpful tips for using the model:

- You can click on the blue cell to see the formula for net present value. This formula discounts or finds the present value of each of the future cash flows you input for each period using your discount rate input, adding them up, and then netting out the initial investment input for period 0.
- Only input data into the yellow cells. 
- Always input the initial investment as a negative number since it represents a cash outflow. Future cash flows should then be shown as positive numbers.

***

### Cash Flows

Cash flows can be broken into 3 phases:

1. Initial Investment Phase - when you make the initial cash outlay to purchase the investment
2. Operating Phase - encompasses the period in which you hold the investment
3. Wind-Up Phase - the organization severs its ownership interest or otherwise abandons the investment





For each phase, you must think about how the cash flows will change as a result of the investment.

- In the initial investment phase, look at the cash outflow that will be needed to acquire the investment.
- In the operating and wind-up phases, think about who in the organization would be able to estimate the effect that the investment will have on the organization’s cash revenues and cash expenditures.
- These types of cash flows are known as pre-tax cash flows.
- It is important to consider taxes when calculating the value of an investment.

***

### Ignoring Taxes Could Lead to Bad Decisions

If an investment will increase an organization’s taxable income, that means the investment will result in additional cash outflows to pay taxes. These additional cash outflows will reduce the value created by the investment, and therefore, must be factored in when calculating net present value.



- Taxable income = Revenues - Costs to Produce Revenues - Depreciation Expense
- You cannot multiply before tax cash flows by a tax rate to calculate additional cash flow related to taxes. This is because taxable income is often different from the cash flows for a particular period. For instance, some cash flows are not immediately deductible.

##### Taxes in the Initial Investment Phase

- The initial cash outflow required to invest in a piece of machinery or something similar generally results in what is known as a **capitalized cost.**
- A capitalized cost means that without a special tax provision, you do not get an immediate tax deduction for the cash you paid to acquire the investment. Instead, you get to expense this cost, through what we call **depreciation expense**, gradually over the investment’s useful life.
- In sum, while the cash outflow to acquire the investment occurs at time 0, this cash flow won’t have an impact on taxable income until later periods.

##### Taxes in the Operating Phase

In this phase, taxable income will change because of the investment’s predicted effect on revenues and production costs.

- As revenues go up, taxable income goes up too;
- At the same time, production costs will reduce taxable income;
- Taxable income will also decrease as the organization starts depreciating the cost of the initial investment.

##### Taxes in the Wind-Up Phase

- In the case of an investment like a piece of machinery, the investment may end when you sell or otherwise get rid of the equipment.
- For tax purposes, gains recognized on the sale of property generally increase taxable income. We can compute gain as subtracting an organization’s basis in property from the amount it receives from a buyer for the property.
- An organization’s basis in property is equal to its initial investment in that property minus the total depreciation claimed on the tax return with respect to the property.

***

### A Final Example & Unit Wrap-Up

Valuing investments is not a certain process. Because net present value is based on several assumptions and estimates, there’s a lot of room for error. To help mitigate this risk, you can:

1. Ask an independent party to review your assumptions and calculations.
2. Perform sensitivity analyses to see what happens if you tweak assumptions.
3. Evaluate the results of your decisions and use the feedback to make better decisions in the future.



##### The Timing of Depreciation

- The total amount of depreciation expense you can deduct on an investment will be the same no matter how much is deducted each period. The difference is that by allowing taxpayers to claim more depreciation expense earlier in time, the timing of the cash tax savings associated with these deductions is also accelerated.
- The time value of money tells us that money is more valuable the sooner we receive it. Therefore, it is unsurprising that accelerating depreciation deductions increases the net present value of investments, making them more attractive.