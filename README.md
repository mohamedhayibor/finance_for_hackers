# Developers Guide to Finance

This won't get you a Finance receipt (bachelors), but it will be very close.

It exposes the 10 useful formulas and concepts in finance that you need in your day to day life. If you are a freelance programmer these simple formulas will help you determine whether to take on a project or not, whether go out and party or stay up all night programming...

> As you could get the formulas with a straight google, we'll focus more on the explanation and situations you might need them.

### Future Value [FV]

> The value of an asset at a specific point in time in the future that is equivalent in value to a specific amount today. 

### Present Value [PV]

> today's value of tomorrow's cash flow. (inverse of FV)

If you are selling anything today (laptop, business...) you would want to calculate the present value and ideally sell it at a price higher than that amount.

The inverse relationship between (future value or payment and interest rate) is the reason why "when rates go up, prices go down and vice versa). By the way, feel pround, some finance graduates can't explain this concept.

### Net Present Value [NPV]

> This discounts all future cash flows to the present and then determines if the present value of the inflows is greater or less than your initial investment. Tip: When choosing from a bunch of project, pick the one with the highest NPV.

As the concept is pretty close to PV, NPV determines how much your individual projects are worth today.

### Payment [PMT]

> a type of annuity (series of equal cash payments at regular intervals).

If you taking any types of loans (car, home, laptop), this is the amount you owe to the end of each period. (usually monthly)

### Return On Investment [ROI]

No matter your background you have to understand this concept. It applies to almost anything you do in life. It is the mostly 

> As the name implies it is the percentage change of gain or loss compared with your original investment.

### Internal rate of return [IRR]

> The discount rate that produces a zero net present value for a given set of cash flows.


### PayBack Period [PP]

> The amount of time needed to recover the initial investment.

### Profitability ratios

> The ratio of the present value of a project's positive cash flows to the present value of its negative cash flows.


### Leverate ratio [LR]

> The degree to which borrowed money is used to make money.

This is a double edge sword and dangerous if neglected. The more leverage, the more risk the more it can be in your favor or ruin you.

### Rule of 72

> deternmines how long it takes to double your money at a specific rate.

This is not talked about often but is super useful when making a mental calculation or straight operation from a REPL.

### Effective Annual Rate (EAR)

When you reading something from your bank, they are most likely giving you the annual percentage rates (APRs aka advertised interest rates). They are stated on an annual basis and if you are making payments daily, weekly, montly or quarterly that's not the rate you are actually paying for. So do your homework and calculate the Effective annual rate (EAR)

> the rate of interest actually paid or earned per year and depends on the number of compounding periods. (Takes into account the interest earned on interest)

### Burn Rate (Bleed rate)

> The rate at which your idea (startup) will burn up funds provided by angels or venture capitalists.

# Terms that are useful to know 

Growth rate: The annual percentage increase (of value, worth, ...)

Perpetuity: Infinite series of regular and equal payments.

> Also when you hear the term risk in a finance , they are talking about the standard deviation (square root of the variance of the distribution of actual returns of actual returns from their mean.

## Libraries

* [Javascript implementation](https://github.com/essamjoubori/finance.js)
* [Rust implementation](https://github.com/mohamedhayibor/finance)

# License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
