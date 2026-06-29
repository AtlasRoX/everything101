# Banking 101

> *Banking is the business activity of accepting and safeguarding money deposits owned by other individuals and entities, and then lending this money out to earn a profit.*

---

## The Big Picture

When you deposit $1,000 into your bank account, does the bank keep your cash sitting in a secure vault waiting for you to withdraw it?

No. If they did, they could not afford to pay interest or build branches. 

Instead, the moment you walk out the door, the bank lends most of your money to someone else who wants to buy a house, start a business, or pay for college. They keep only a tiny fraction of your deposit in reserve. 

This is the system of **fractional reserve banking**. It is the engine of modern money creation, but it also makes banks inherently fragile, requiring government regulation and central bank oversight to prevent panics.

This article introduces commercial vs. investment banking, the mechanics of fractional reserve banking, and the role of the Central Bank.

---

## Commercial vs. Investment Banking

The banking sector is divided into two primary types of institutions:

- **Commercial Banks (Retail/Business):** The banks you interact with daily. They take deposits from households and make loans to individuals and local businesses. (e.g., Chase, Barclays).
- **Investment Banks (Corporate/Markets):** They do not take everyday deposits. Instead, they help giant corporations and governments raise money by issuing stocks and bonds, and facilitate major corporate mergers and acquisitions. (e.g., Goldman Sachs, Morgan Stanley).

---

## Fractional Reserve Banking: Money Creation

How do banks make money? They use **fractional reserve banking**.

If a bank is required by the central bank to keep a **10% reserve requirement**:

```
 ┌────────────────────────────────────────────────────────┐
 │            1. Customer deposits $1,000                 │
 └──────────────────────────┬─────────────────────────────┘
                            ▼
 ┌────────────────────────────────────────────────────────┐
 │   2. Bank holds $100 (10%) & lends $900 to Borrower A  │
 └──────────────────────────┬─────────────────────────────┘
                            ▼
 ┌────────────────────────────────────────────────────────┐
 │ 3. Borrower A spends $900 at Store B; Store B deposits │
 │    the $900 into another bank                          │
 └──────────────────────────┬─────────────────────────────┘
                            ▼
 ┌────────────────────────────────────────────────────────┐
 │ 4. Second bank holds $90 (10%) and lends $810 to       │
 │    Borrower C                                          │
 └──────────────────────────▲─────────────────────────────┘
                            │
                            └──── [The cycle repeats] ────┘
```

Through this lending loop, the initial deposit of $1,000 can turn into thousands of dollars of new loans in the economy. **Commercial banks create the majority of the money supply in modern economies through lending.**

---

## The Risk: Bank Runs

Because banks lend out most of their deposits, they do not have enough cash to pay back all depositors at once. 
- If a rumor spreads that a bank is going bankrupt, thousands of customers will panic and rush to withdraw their money simultaneously. 
- This is a **bank run**. Even a perfectly healthy bank can collapse during a run because its assets are tied up in long-term loans that cannot be quickly converted into cash.

---

## The Central Bank: The Watchdog & Savior

To protect the financial system, governments establish a **Central Bank** (e.g., the Federal Reserve in the US). The central bank has two main roles:

1. **Lender of Last Resort:** If a healthy commercial bank faces a sudden bank run, the central bank will lend them cash immediately to pay depositors, stopping the panic.
2. **Monetary Policy:** Controlling the money supply and interest rates to manage inflation and support employment. (See [Macroeconomics101](../Economics/Macroeconomics101.md)).
   - **Reserve Requirements:** Setting the percentage of deposits banks must keep in reserve.
   - **Discount Rate:** The interest rate the central bank charges commercial banks to borrow money.

---

## Key Terms

- **Commercial Bank:** A financial institution accepting deposits and making loans.
- **Investment Bank:** A financial institution helping corporations raise capital and execute mergers.
- **Fractional Reserve Banking:** A banking system where only a fraction of bank deposits are backed by actual cash on hand.
- **Reserve Requirement:** The minimum percentage of deposits a bank must hold.
- **Bank Run:** A financial panic where depositors rush to withdraw cash from a bank.
- **Lender of Last Resort:** The role of the central bank to provide emergency loans to failing financial institutions.

---

## Further Reading

- [Money101](./Money101.md) — The history and functions of currency
- [Interest101](./Interest101.md) — How interest rates drive commercial banking profits
- [Macroeconomics101](../Economics/Macroeconomics101.md) — How central banks use the banking sector to conduct monetary policy
