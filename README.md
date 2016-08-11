# Finance for Hackers :moneybag: :moneybag:

<h1 align="center">
    <br>
    <img width="600" height="400" src="https://cdn.rawgit.com/mohamedhayibor/finance_for_hackers/master/media/logo.jpeg" alt="finance for hackers">
    <br>
    <br>
</h1>

> Photo credit by [Didier Weemaels](https://unsplash.com/@didwee)

This won't get you a Finance receipt (bachelors), but it will be very close.

It exposes the 10 useful formulas and concepts in finance that you need in your day to day life. If you are a freelance programmer these simple formulas will help you determine whether to take on a project or not, whether to go out and party or stay up all night programming...

> As you could get the formulas with a straight google, we'll focus more on the explanation and situations you might need them.

### Future Value [FV]

> The value of an asset at a specific point in time in the future that is equivalent in value to a specific amount today. 

Lets say you have a $1,000.00 at the bank earning you 1% every year. Well turns out that it will be worth $1,030.30 in 3 years. These two amounts are equivalent to each other. The difference is the reward for waiting.

If you do this type of exercise over longer compounding periods, you will notice that future values grow faster and faster, that's because of the compounding of interest (the most powerful force in the world).

The compounding effect is not only for monetary worth of an asset in the future but also learning (rate), growth of a company, population...

### Present Value [PV]

> today's value of tomorrow's cash flow. (inverse of FV)

If you are selling anything today (laptop, business...), you would want to calculate the present value and ideally sell it at a price higher than that amount.

The inverse relationship between (future value or payment and interest rate) is the reason why "when rates go up, prices go down and vice versa). By the way, feel pround, some finance graduates can't explain this concept.

### Net Present Value [NPV]

> This discounts all future cash flows to the present and then determines if the present value of the inflows is greater or less than your initial investment. Tip: When choosing from a bunch of projects, pick the one with the highest NPV.

As the concept is pretty close to PV, NPV determines how much your individual projects are worth today.

### Payment [PMT]

> a type of annuity (series of equal cash payments at regular intervals).

If you taking any types of loans (car, home, laptop), this is the amount you owe at the end of each period. (usually monthly)

### Return On Investment [ROI]

No matter your background you have to understand this concept. It applies to almost anything you do in life. It is the mostly used metric to determine how profitable an investement or venture is.

> As the name implies, it is the percentage change of gain or loss compared with your original investment.

### Internal rate of return [IRR]

> The discount rate that produces a zero net present value for a given set of cash flows.

### PayBack Period [PP]

> The amount of time needed to recover from an initial investment.

### Profitability ratio

> The ratio of the present value of a project's positive cash flows to the present value of its negative cash flows.

### Leverate ratio [LR]

> The degree to which borrowed money is used to make money.

This is a double edge sword and dangerous if neglected. The more leverage, the more risk, the more it can be in your favor or ruin you.

### Rule of 72

> deternmines how long it takes to double your money at a specific rate.

This is not talked about often but is super useful when making a mental calculation or straight operation from a REPL.

### Effective Annual Rate [EAR]

When you reading something from your bank, they are most likely giving you the annual percentage rates (APRs aka advertised interest rates). They are stated on an annual basis and if you are making payments daily, weekly, montly or quarterly that's not the rate you are actually paying for. So do your homework and calculate the Effective annual rate (EAR)

> the rate of interest actually paid or earned per year and depends on the number of compounding periods. (Takes into account the interest earned on interest)

## Useful terms to know 

* Growth rate: The annual percentage increase (of value, worth, ...)
* Burn Rate (Bleed rate): the rate at which your idea (startup) will burn up funds provided by angels or venture capitalists.
* Perpetuity: Infinite series of regular and equal payments.

> Also when you hear the term risk in a finance setting, they are talking about the standard deviation (square root of the variance of the distribution of actual returns of actual returns from their mean).

## Libraries

* [Javascript implementation](https://github.com/essamjoubori/finance.js)
* [Rust implementation](https://github.com/mohamedhayibor/finance)

# License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
