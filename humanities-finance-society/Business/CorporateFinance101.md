# Corporate Finance 101

> *Corporate finance is the area of finance dealing with the sources of funding and the capital structure of corporations, the actions that managers take to increase the value of the firm to the shareholders, and the tools and analysis used to allocate financial resources.*

---

## The Big Picture

Imagine you are the CEO of a successful retail chain:
- You want to build a new flagship store in Paris. It will cost $10 million to build, but it will bring in $1 million a year in profit for the next twenty years. Should you do it? 
- Where do you get the $10 million? Do you take out a loan from a bank, or do you sell shares of your company to the public?
- How much cash must you keep in the bank to pay your suppliers next week?

These are the three core questions of **corporate finance**:
1. **The Investment Decision (Capital Budgeting):** What projects should the firm invest in?
2. **The Financing Decision (Capital Structure):** How do we pay for those projects?
3. **The Liquidity Decision (Working Capital):** How do we manage day-to-day cash flow?

---

## The Investment Decision: Time Value of Money & NPV

A dollar today is worth more than a dollar tomorrow. Why? Because you can invest a dollar today to earn interest. 

Therefore, a business cannot simply add up future profits to decide if a project is worth investing in. It must use **discounting** to calculate the **Net Present Value (NPV)** of a project:

- **Present Value (PV):** The value today of a sum of money to be received in the future.
- **Net Present Value (NPV):** The present value of all future cash inflows from a project, minus the initial cost of the project.

$$\text{NPV} = \sum \frac{\text{Cash Flow}_t}{(1 + r)^t} - \text{Initial Cost}$$

Where $r$ is the discount rate (the cost of capital) and $t$ is the year.

> **Rule of Capital Budgeting:** If a project has an **NPV > 0**, it creates value for the firm and should be executed. If **NPV < 0**, the project destroys value and should be rejected.

---

## The Financing Decision: Debt vs. Equity

To raise money for investments, a firm has two primary choices. This mix is called its **capital structure**:

```
                              ┌─────────────────────────┐
                              │    CAPITAL STRUCTURE    │
                              └────────────┬────────────┘
                                           │
         ┌─────────────────────────────────┴─────────────────────────────────┐
         ▼                                                                   ▼
┌──────────────────┐                                                ┌──────────────────┐
│       DEBT       │                                                │      EQUITY      │
│ Borrowing money  │                                                │ Selling shares   │
│ (Loans, Bonds)   │                                                │  (Stock, VC)     │
└────────┬─────────┘                                                └────────┬─────────┘
         │                                                                   │
         ▼                                                                   ▼
┌──────────────────┐                                                ┌──────────────────┐
│ Pay fixed interest│                                               │ No interest, but │
│ but retain full  │                                                │ share profits &  │
│ ownership        │                                                │ ownership control│
└──────────────────┘                                                └──────────────────┘
```

### 1. Debt Financing
Borrowing money that must be paid back over time with a fixed interest rate.
- **Pros:** No dilution of ownership. Interest payments are tax-deductible.
- **Cons:** High risk. If the firm has a bad month, it must still pay the interest, potentially leading to bankruptcy.

### 2. Equity Financing
Selling ownership shares of the company to investors.
- **Pros:** Low risk. There is no debt to repay, and if the firm fails, the investors lose their money (no bankruptcy risk).
- **Cons:** Dilutes ownership. The founders must share future profits and answer to new board members.

---

## Working Capital: Day-to-Day Survival

While long-term projects are important, a company will go bankrupt if it cannot pay its electricity bill next week. 

Managing **Working Capital** ensures the firm has enough short-term liquidity:

$$\text{Net Working Capital} = \text{Current Assets} - \text{Current Liabilities}$$

- **Current Assets:** Cash, inventory, and accounts receivable (money customers owe you).
- **Current Liabilities:** Accounts payable (money you owe suppliers) and short-term debt.

A corporate finance manager must balance safety (keeping lots of cash in the bank) with efficiency (investing idle cash to earn returns).

---

## Key Terms

- **Corporate Finance:** The management of a corporation's assets, liabilities, and investments.
- **Capital Budgeting:** The process of planning and managing a firm's long-term investments.
- **Net Present Value (NPV):** The difference between the present value of cash inflows and outflows.
- **Capital Structure:** The mix of debt and equity used to finance a firm's operations.
- **Debt Financing:** Raising capital by borrowing money.
- **Equity Financing:** Raising capital by selling shares of ownership.
- **Working Capital:** Short-term financial resources needed for day-to-day operations.

---

## Further Reading

- [Accounting101](./Accounting101.md) — The financial statements corporate finance relies on
- [Startup101](./Startup101.md) — The financing lifecycle of early-stage firms
- [Capital101](../Economics/Capital101.md) — The physical assets corporate finance budgets for
